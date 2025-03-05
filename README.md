## Anomaly Detection in Credit Card Transactions

## Overview
This project uses an Isolation Forest model to detect anomalies in credit card transactions. The goal is to identify fraudulent transactions in a highly imbalanced dataset.

## Dataset
- **Source:** [Credit Card Fraud Detection Dataset on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- The dataset contains 284,807 transactions, with 492 cases of fraud.
- Features include anonymized transaction details and the 'Class' label (1 = fraud, 0 = non-fraud).

## Approach
1. Data preprocessing with feature scaling.
2. Visualization of transaction data.
3. Anomaly detection using Isolation Forest.
4. Hyperparameter tuning with GridSearchCV.
5. Model evaluation using classification metrics and ROC curve.

## Installation
- Clone the repository.
- Install dependencies with `pip install -r requirements.txt`.

## How to Run
- Execute the Python script `anomaly_detection.py`.

## Results
- Achieved high accuracy in detecting fraudulent transactions.
- The ROC curve visualizes the model's performance.
