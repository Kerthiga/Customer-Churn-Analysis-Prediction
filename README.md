# Customer Churn Prediction & Analysis

## Problem Statement
The goal of this project is to analyze customer churn behavior and predict customers who are likely to leave, helping businesses improve customer retention strategies.

---

## Dataset
The Telco Customer Churn dataset includes:
- Customer demographics
- Services subscribed
- Tenure (duration with company)
- Monthly & total charges
- Churn status (Yes/No)

  Dataset link : https://www.kaggle.com/datasets/blastchar/telco-customer-churn

---

## Tools & Technologies
- Python (Pandas, NumPy, Matplotlib)
- Scikit-learn (Machine Learning)
- Power BI (Dashboard & Visualization)

---

## Exploratory Data Analysis (EDA)
- Customers with **low tenure (0–6 months)** have higher churn
- **Month-to-month contracts** show the highest churn rate
- **Higher monthly charges** increase churn probability
- **Electronic check users** churn more frequently

---

## Machine Learning Models

| Model                  | Accuracy |
|-----------------------|----------|
| Logistic Regression   | 78.75%   |
| Random Forest         | 78.61%   |

--> Both models show similar performance (~78%), indicating stable prediction capability.

--> Logistic Regression is preferred due to:
- Simplicity  
- Faster performance  
- Better interpretability  

---

## Churn Risk Segmentation
Customers are categorized based on churn probability:
- Very High Risk (≥ 90%)
- High Risk (80–89%)
- Medium Risk (50–79%)
- Low Risk (< 50%)

---

## Dashboard (Power BI)
The dashboard includes:
- Key KPIs (Churn Rate, Total Customers, Accuracy)
- Churn by Contract Type
- Churn by Payment Method
- Churn by Tenure Group
- Top 5 High-Risk Customers

---

## Key Insights
- New customers are more likely to churn  
- Month-to-month contracts drive maximum churn  
- High charges increase churn risk  
- Payment method influences customer retention  

---

## Dashboard Preview
<img width="1283" height="712" alt="Screenshot 2026-04-08 133521" src="https://github.com/user-attachments/assets/50b5733d-b231-4ef4-a2d6-b088c5b8e58f" />

