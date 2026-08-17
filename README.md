# Telco Customer Churn Prediction

## Project Overview

This project focuses on predicting customer churn using machine learning.

Two classification models were developed and compared:

- XGBoost
- Multilayer Perceptron (MLP)

GridSearchCV with 5-Fold Stratified Cross-Validation was used for
hyperparameter optimization.

## Dataset

Telco Customer Churn Dataset:

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

## Methodology

1. Data Loading
2. Exploratory Data Analysis
3. Data Preprocessing
4. Train-Test Split
5. 5-Fold Stratified Cross-Validation
6. GridSearchCV
7. XGBoost
8. MLP
9. Model Evaluation
10. Confusion Matrix
11. ROC Curve and AUC
12. Feature Importance
13. Model Comparison

## Results

| Metric | XGBoost | MLP |
|---|---:|---:|
| Accuracy | 0.808 | 0.793 |
| Precision | 0.676 | 0.620 |
| Recall | 0.529 | 0.572 |
| F1-score | 0.594 | 0.595 |
| AUC | 0.845 | 0.841 |

## Conclusion

XGBoost achieved higher accuracy, precision and AUC, while MLP achieved
slightly higher recall and F1-score. Therefore, XGBoost provides better
overall performance, while MLP is slightly better at identifying churn
customers based on recall and F1-score.
