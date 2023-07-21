RFECV is an extension of RFE that adds cross-validation to the feature selection process.


- Instead of using a fixed number of features as in RFE, RFECV performs feature selection using cross-validation to determine the optimal number of features.

- It evaluates the model's performance on different subsets of features using cross-validation, and the number of features that provides the best cross-validation score is selected.