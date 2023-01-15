# GLM_Classifier_Intro

## Implementing GLM_Classifier Machine Learning Model

GBM Classifier
* n_estimators - No of Trees in the Model
* max_features - The number of features to consider while searching for a best split.Thumb Rule to have Square root of no of Columns
* max_depth - Maximum Depth of Tree and can be used to control overfiting
* min_samples_leaf - Minimum samples (or observations) required in a terminal node or leaf.In general we need to have lower values for it for Imbalanced problems
* subsample- The fraction of samples to be used for fitting the individual base learners
* learning_rate - Learning rate shrinks the contribution of each tree by learning_rate. There is a trade-off between learning_rate and n_estimators
