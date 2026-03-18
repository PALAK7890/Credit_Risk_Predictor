# Credit Risk Predictor

## Problem
Predict whether a loan applicant will default based on financial history.

## Dataset
1030 customers with 12 features including credit score,
income, missed payments, and debt-to-income ratio.

## What I did
- Removed duplicates and outliers
- Handled missing values and inconsistent categories
- Compared Logistic Regression, Decision Tree, Random Forest

## Results
| Model               | Accuracy | ROC-AUC | F1   |
|---------------------|----------|---------|------|
| Logistic Regression | 0.70     | 0.70    | 0.70 |
| Decision Tree       | 0.73     | 0.73    | 0.73 |
| Random Forest       | 0.71     | 0.71    | 0.71 |

## Best Model
Decision Tree — highest recall on defaulters (0.71)
which matters most in a banking context.
