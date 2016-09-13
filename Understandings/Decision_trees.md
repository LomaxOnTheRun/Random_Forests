#Decision trees

These are 'trees' made of a single *root* node, which splits into two or more branches based on an attribute of the population in the root node. These branches then further split using other attributes. This continues until a certain condition is met, such as that all *leaf* (end) nodes are completely homogenous.

There are two types of decision trees in machine learning:
  1. **Classification trees**, when targets fall into discrete labels
  2. **Regression trees**, when targets have continous values

Both of these have the same terminology applied to its component parts:

![Decision tree terminology, from https://www.analyticsvidhya.com/blog/2016/04/complete-tutorial-tree-based-modeling-scratch-in-python/](/images/Decision_Tree_Terminology.png)

Each time a branch splits, the tree increases the homogeneity of the end nodes. How we choose to split the node into sub-nodes is up to us, but here are 4 examples of how we can do it:
  1. Gini index
  2. Chi-square
  3. Information gain
  4. Reduction in variance
