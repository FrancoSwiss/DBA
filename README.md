# DBA - Corresponding Jupyter Notebook to my DBA thesis:

EDA (Exploratory Data Analysis)
- Visualize feature vs. churn.
- Can we find patterrns in churn (e.g. Balance > mean)?
- Are women more likely to churn than men?
- Do we have highly correlated (>0.95) features?

The 4 Problems with Data
- Do we replace NaN's with mean or median?
- Do we have a normal or non-normal distribution in NaN features?
- Do we have a gender pattern in NaN?
- Checking for outliers / errors with IQR * 3
- Cardinality and rare values are ignored.
- Categorical encoding of gender

Normalization
- Should we use normalization or standardization?

Binary Classification Logistic Regression
- C = 0.95 where C is the inverse of regularization strenght. Large values of C give more freedom (hihgher variance).
- L2 regularization adds a penalty to the cost function -> in less extreme weight values.
- Class weight = "balanced" will automatically weigh classes proportional to their frequency
- Random state = 12 for the pseudorandom number generator.

K-fold Cross Validation
- 3 fold Cross Validation with 68% accuracy and a low standard deviation of 1.62%

Confusion Matrix
- Equal specificity (recall 0) and sensitivity (recall 1) of 0.71 which is OK.

Area Under ROC Curve
- With 71% just OK / descent.

Diagnosing Bias and Variance Problems with Learning Curves
- As expected, we get a high bias and low variance with Logistic Regression

Extract Intercept and Coefficients from Logistic Regression
- intercept_ and coef_ for Tableau

Jupyter Notebook in GitHub now.
