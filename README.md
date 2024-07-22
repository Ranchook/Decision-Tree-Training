# Decision Tree Training
2nd Class exercise in intro ML and data science course - training a decision tree and comparing a 2 dimensonal dataset with a multi dimensional dataset.

Decision trees are a type of supervised learning algorithm used for classification and regression tasks. They work by recursively splitting the data into subsets based on feature values, creating a tree-like model of decisions. Each internal node represents a decision based on a feature, each branch represents an outcome of the decision, and each leaf node represents a class label or a continuous value.

In this class exercise we were asked to train a decision tree on 2 different data sets: Iris (2d dataset) and Spectral (multi-dimensional dataset).
We examined the influence of different parameters on the accuracy of the tree and carefully chose the optimal values.

I wrote it in two different notebooks for convenience purposes, the functions are the same in each notebook. 

## The exercise

The 2 datasets will be split - 70% for training and 30% for test.

The following paramters will be fixed: criterion=entropy, cv=3 (cross validation), n_jobs = 4 (number of parallel jobs)

1. Examine the influnce of different parameters of the decision tree:
                   a. Check the influence of the parameter "max_depth".
                   b. Check the influence of the parameter "min_samples_leaf".
                   c. Check the influence of the parameter "max_leaf_nodes".
2. Choose the optimal value of each paramter and run it all together.
