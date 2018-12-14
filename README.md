# Credit Card Fraud Detection
# Introduction
The dataset contains 284,807 transactions made by credit cards during two days of September 2013 by european cardholders.
Credit card companies need to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
# Goal
Build a predictive model to identify fraudulent credit card transactions (supervised binary classification problem).
# Data
According to the Kaggle 'Overview' tab:
Features V1, V2, ... V28 are the principal components obtained by PCA
Feature 'Time' contains the seconds elapsed between a transaction and the first transaction in the dataset
Feature 'Amount' is the transaction Amount
Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
# Metric
The dataset is highly unbalanced:
  - 492 fraudulent transactions vs. 284,315 genuines
  - So the positive class (Frauds) account for 0.172% of all transactions.
  - First, we want to catch frauds. It means: minimizing the False Negative rate
# Recall
Then we want to minimize the False Positive rate
# Precision
The Area under the Precision-Recall curve is the compromise metrics in this Precision-Recall trade-off.
