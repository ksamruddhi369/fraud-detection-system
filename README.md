# 🔍 Fraud Detection System

## Overview
ML-powered credit card fraud detection system built on 284,807 real transactions.

## Problem
Only 0.17% of transactions are fraud — making accuracy a misleading metric.

## Solution
- Applied **SMOTE** to fix class imbalance
- Trained 3 models: Logistic Regression, Random Forest, XGBoost
- Used **SHAP** to explain why each transaction was flagged

## Results
| Model | AUC-ROC | F1 Score |
|---|---|---|
| Logistic Regression | 0.972 | 0.097 |
| Random Forest | 0.979 | 0.845 |
| XGBoost | 0.974 | 0.522 |

✅ Best Model: Random Forest (AUC = 0.979)

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, XGBoost, SHAP, Matplotlib, Seaborn

## Dataset
Kaggle Credit Card Fraud Detection — 284,807 transactions
