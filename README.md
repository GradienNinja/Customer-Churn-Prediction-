# Customer Churn Prediction using Logistic Regression

## Overview
This project focuses on predicting customer churn using Logistic Regression.  
The goal was not only to achieve good accuracy, but to understand how preprocessing, scaling, and feature interpretation affect model behavior.

## Dataset
The dataset contains customer demographic information, behavioral usage metrics, subscription details, and contract information.  
Target variable: **Churn (0 = No, 1 = Yes)**.

## Preprocessing
- Categorical features were handled using **One-Hot Encoding**
- Numerical features were scaled using **StandardScaler**
- Train–test split was performed before scaling to avoid data leakage
- Feature preprocessing was done manually to better understand each step

## Model
- Algorithm: **Logistic Regression**
- Evaluation metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix

## Key Insights
The model identifies **payment delay** and **frequent support calls** as the strongest churn drivers.  
Behavioral signals dominate demographic ones.  
**Long-term contracts** and **high usage frequency** significantly reduce churn, while **tenure alone is not protective unless supported by contract commitment**.

## Result
The model achieved approximately **83% accuracy** with balanced precision and recall across both classes.

## Learning Outcome
This project helped solidify understanding of:
- Proper preprocessing pipelines
- Feature scaling and data leakage
- Interpreting logistic regression coefficients
- Translating model output into business insights
