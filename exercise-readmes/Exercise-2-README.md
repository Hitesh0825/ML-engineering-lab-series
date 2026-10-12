# Exercise 2: Logistic Regression — Bank Marketing

## Objective
Predict whether a customer subscribes to a term deposit.

## Dataset
`data/raw/bank_marketing.csv`

## Workflow
- Prepare the binary target and selected features.
- Encode categorical variables and scale numeric features.
- Train a class-weighted Logistic Regression model.
- Evaluate classification metrics and ROC-AUC.
- Evaluate recall at a threshold of 0.35.

## Verified Results
- ROC-AUC: 0.8769 — PASS (target >= 0.78)
- Recall at threshold 0.35: 0.8552 — PASS (target >= 0.70)

## Notebook
`notebooks/02_logistic_regression.ipynb`

## Output
`outputs/exercise2_predictions.csv`
