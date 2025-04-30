# 🛡️ Fraudulent Insurance Claim Detection

This repository contains the implementation of a machine learning pipeline to detect fraudulent insurance claims using structured customer, vehicle, and claim data. The goal is to assist Global Insure in automating the identification of potentially fraudulent claims and reducing manual investigation effort.

---

## 📌 Project Overview

Insurance fraud is a significant source of loss for insurers, often going undetected due to the reliance on manual reviews. This project uses historical data to build predictive models that classify whether an insurance claim is **fraudulent** or **legitimate** based on:

- Policy details
- Incident specifics
- Vehicle and claimant attributes
- Claim amount and timing

---

## 🧠 Techniques Used

- **Exploratory Data Analysis (EDA)**: Histograms, Boxplots, Correlation heatmaps
- **Data Cleaning & Feature Engineering**: Outlier handling, imputation, dummy encoding, derived features
- **Modeling**:
  - Logistic Regression (with RFECV for feature selection)
  - Random Forest (with GridSearchCV tuning)
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, ROC-AUC, Confusion Matrix
- **Business Insights & Reporting**: Actionable recommendations and clear visuals

---

## 📊 Key Results

| Metric                      | Logistic Regression | Random Forest |
|----------------------------|---------------------|----------------|
| **Accuracy (Train)**       | 81.8%               | 85.9%          |
| **Accuracy (Validation)**  | 81.0%               | 76.3%          |
| **F1 Score (Validation)**  | 0.63                | 0.58           |
| **Sensitivity (Recall)**   | 0.66                | 0.68           |
| **Specificity**            | 0.86                | 0.79           |

📈 Feature importance and cutoff optimization were key to performance gains.

---
