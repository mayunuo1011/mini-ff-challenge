This is # university of Edinburgh(UoE) Social Data Science Mini Future Family Coding Challenge 2025

The project aims to predict the academic outcome(GPA) using supervised machine learning models.

It mainly includes 4 parts:

## 1 Data Pre-processing
Winsorization to handle extreme values
Median imputation for missing and non-finite values

## 2 Feature Selection

LASSO regression (alpha = 0.8) was used for feature selection.
The optimal lambda was chosen using 5-fold cross-validation (lambda.1se rule).

## 3 Model Building

A stacking ensemble model was built：Random Forest & XGBoost + Ridge Regression

To reduce overfitting:
- 10-fold Out-of-Fold (OOF) cross-validation
- Reduced tree depth
- Regularization techniques

## 4 Model Performance

R² = 0.159

The highest result among the course


## Team Member:
Yunuo Ma, Xinzhi Li, Jade Shi
