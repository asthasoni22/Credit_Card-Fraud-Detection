# Credit Card Fraud Detection Project

Welcome to the Credit Card Fraud Detection Project repository. This project was developed during the Interestship 5.0 program by the Clique Community. The primary objective is to detect fraudulent credit card transactions using various data science and machine learning techniques.

## Introduction

This project aims to identify fraudulent credit card transactions by analyzing transaction data and implementing multiple machine learning models. The goal is to enhance the accuracy and reliability of fraud detection systems.

## Dataset Overview

The dataset comprises credit card transactions with the following features:

- **Time**: Seconds elapsed between each transaction and the first transaction.
- **V1-V28**: Anonymized features resulting from Principal Component Analysis (PCA).
- **Amount**: Transaction amount.
- **Class**: Binary label indicating whether the transaction is fraudulent (1) or not (0).

*Note: The dataset is highly imbalanced, with a small fraction of transactions labeled as fraudulent.*

## Data Processing

Data processing steps include:

- **Handling Missing Values**: Identifying and imputing or removing missing data.
- **Feature Scaling**: Standardizing features like 'Time' and 'Amount' to ensure uniformity.
- **Data Splitting**: Dividing the dataset into training and testing sets.
- **Data Imputation**: Replacing missing values with appropriate substitutes.
- **Normalization**: Scaling features to a standard range.

## Models Implemented

The following machine learning models were implemented:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Support Vector Machine (SVM)
- LightGBM
- XGBoost

Among these, Logistic Regression achieved the highest accuracy in detecting fraudulent transactions.

## Evaluation Metrics

To assess model performance, the following metrics were utilized:

- **ROC Curves**: Evaluating the true positive rate against the false positive rate.
- **Precision-Recall Curves**: Measuring the trade-off between precision and recall.
- **Confusion Matrices**: Summarizing the correct and incorrect classifications.

## SHAP Analysis

SHAP (SHapley Additive exPlanations) analysis was conducted to interpret model predictions by determining feature importance. This analysis provided insights into which features significantly influenced the model's decisions.

[Check out my Medium blog](https://medium.com/@asthasoni161/my-experience-with-interestship-5-0-e7bc40d76efa)
