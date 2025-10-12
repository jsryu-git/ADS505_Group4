# ADS505_Group4

## Telco Customer Churn (IBM)
Link to dataset: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

### Project Overview

Business goal: Identify customers at elevated risk of churn and provide targeted, measurable ways to keep them.

Approach: Supervised learning on the Telco Customer Churn dataset; compared Logistic Regression, Random Forest, XGBoost via 5-fold Stratified GridSearchCV (scoring = ROC-AUC). Selected the best model, validated on a 30% holdout test set, chose an operating threshold for recall-oriented retention, and extracted drivers with permutation importance.
