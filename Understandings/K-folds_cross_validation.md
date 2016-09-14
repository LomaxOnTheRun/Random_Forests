#K-folds cross validation

Cross validation is a methodology by which you take a portion of the data available, and set it aside as *test* data. The remainder of the data remains as *training* data. You then train your model using the training data, and test its accuracy by using the test data you've put aside.

K-folds cross validation breaks the data up into K subsets. For each of these subsets, a new model is trained using the rest of the data as training data, and the subset is used as test data. This allows you to build K models, each with a test dataset which it has never seen before. Averaging the accuracy of these models gives a better idea of the actual accuracy of the training methods and hyperparameters for your models.

![Taken from https://upload.wikimedia.org/wikipedia/commons/f/f2/K-fold_cross_validation.jpg](/images/K-fold_cross_validation.jpg)

