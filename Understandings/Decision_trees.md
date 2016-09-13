#Decision trees

These are 'trees' made of a single *root* node, which splits into two or more branches based on an attribute of the population in the root node. These branches then further split using other attributes. This continues until a condition is met, usually that there is a maximum population left in a *leaf* (end) node. This maximum population would be 1 for a completely sorted total population.

There are two types of decision trees in machine learning:
  1. **Classification trees**, when targets fall into discrete labels
  2. **Regression trees**, when targets have continous values

Each time a branch splits, the tree increases the homogeneity of the end nodes. How we choose to split the node into sub-nodes is up to us, but here are 4 examples of how we can do it:
  1. Gini index
  2. Chi-square
  3. Information gain
  4. Reduction in variance
