# Portuguese Banking Institution Term Deposit Prediction

## Introduction
This project predicts client subscription to term deposits based on telephonic marketing data from a Portuguese bank.

## Problem Statement
Telephonic marketing is costly. Predicting likely subscribers can optimize campaign efficiency. The goal is to predict client subscription to a term deposit ('y').

## Data Understanding
The dataset includes telephonic marketing campaign data from May 2008 to November 2010, with attributes such as age, job, marital status, education, default status, balance, loans, contact type, contact duration, campaign details, and previous outcomes.

## Model Selection
We evaluated multiple models:
| Model  | Accuracy(%) |
| ------------- | ------------- |
| Logistic Regression  | 77  |
| Decision Tree  | 90  |
|  Random Forest  | 89   |
|  SVM  | 80   |
|  KNN  |  86  |
|  Naive Bayes  | 75   |
The Decision Tree model achieved the highest accuracy of 90%.

## Conclusion
The Decision Tree model outperformed other models in predicting term deposit subscriptions. Implementing this model can help the bank optimize its telephonic marketing campaigns, reducing costs and improving efficiency by targeting the most likely subscribers.
