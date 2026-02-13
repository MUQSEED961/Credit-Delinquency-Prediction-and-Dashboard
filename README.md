# Credit Delinquency Risk Analysis & Power BI Dashboard

## 📌 Project Overview
This project analyzes customer financial data to identify delinquency risk using classification models and presents insights through an interactive Power BI dashboard.

The objective is to support collections strategy and risk management through data-driven decision-making.

---

## 🎯 Business Problem
Financial institutions must identify customers at risk of delinquency to minimize losses and improve collections efficiency.  
This project builds predictive models and visual analytics to help understand key risk drivers and portfolio behavior.

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy)
- Scikit-learn
- XGBoost
- Machine Learning Models:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - XGBoost
- Power BI (Interactive Dashboard)

---

## 📊 Dataset Features
Key variables used:
- Age
- Income
- Credit Score
- Credit Utilization
- Missed Payments
- Debt-to-Income Ratio
- Loan Balance
- Account Tenure
- Location
- Delinquent_Account (Target Variable)

---

## 🤖 Models Implemented
The following classification models were trained and evaluated:

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier
- Gradient Boosting Classifier

Evaluation Metrics:
- Accuracy
- F1 Score
- ROC-AUC Score
- Confusion Matrix

---

## 📈 Key Insights
- Lower credit score segments show higher delinquency rates.
- Higher debt-to-income ratio is associated with increased default risk.
- Loan exposure varies significantly across income segments.
- Model comparison highlights trade-offs between performance metrics.

---

## 📊 Power BI Dashboard Overview

### Page 1 – Delinquency Risk Dashboard
- Customer Distribution
- Delinquency Rate Trend
- Loan Exposure Analysis
- Credit Score Segmentation
- Geographic Risk Distribution
- Financial Stress Trend

### Page 2 – Model Performance Dashboard
- Model Comparison KPIs
- Accuracy, F1 Score, ROC-AUC
- Confusion Matrix Summary

---

## 📂 Repository Structure
---

├── delinquency_model.ipynb
├── model_metrics.csv
├── PowerBI_Dashboard.pbix
└── README.md


---

## 🚀 Project Outcome
This project demonstrates an end-to-end analytics workflow:
Data preprocessing → Predictive modeling → Performance evaluation → Executive dashboard reporting.

