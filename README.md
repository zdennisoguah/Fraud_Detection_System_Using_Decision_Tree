# Credit card Fraud Detection System Using Decision Tree Algorithm
### About
This repository contains the implementation of a binary tree classification model for fraud detection. The model is designed to predict whether a transaction is fraudulent based on various features.

Fraud detection is critical in various industries, especially in financial transactions. This binary tree classification model is built to identify potentially fraudulent transactions by learning patterns from historical data.

## Features
The model uses a set of features to make predictions. These features and their importance include:

+ Variable: isHighRiskCountry    Importance: 0.461
+ Variable: isForeignTransaction Importance: 0.007
+ Variable: Transaction_amount   Importance: 0.072
+ Variable: Total Number of declines/day Importance: 0.209
+ Variable: Is declined          Importance: 0.0
+ Variable: Daily_chargeback_avg_amt Importance: 0.0
+ Variable: Average Amount/transaction/day Importance: 0.039
+ Variable: 6_month_avg_chbk_amt Importance: 0.008
+ Variable: 6-month_chbk_freq    Importance: 0.204

> # Binary tree
![image](https://github.com/zdennisoguah/Fraud_Detection_System_Using_Decision_Tree/assets/15913685/64e73a3d-f39d-4a14-ad2b-1e080b82fff4)

## Model Training
The model is trained using historical data split into a training dataset and a test dataset

## Evaluation
The model's performance is evaluated using various metrics, such as confusion matrix, accuracy, precision, recall, and ROC-AUC score.

## Results
+ Precision score: 0.9590163934426229
+ Average precision-recall score(AP): 0.86
+ Recall: 0.8796992481203008
+ ROC-AUC-score: 0.9929142476444275
+ F1 score: 0.9176470588235294

