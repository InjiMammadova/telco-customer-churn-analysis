# Telco Customer Churn Prediction

## Overview
This project analyzes customer churn behavior in a telecommunications company and develops machine learning models to predict which customers are likely to leave.

The objective is to both predict churn and identify the key drivers behind customer attrition in order to support data-driven retention strategies.

---

## Business Problem
Customer churn is a critical challenge in subscription-based businesses, directly impacting revenue and long-term growth.

This project aims to:
- Identify high-risk customers  
- Understand the main drivers of churn  
- Support data-driven decision-making  

---

## Methodology

The analysis follows a structured end-to-end workflow:

1. Data Cleaning and Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Model Development and Comparison  
5. Model Evaluation  

---

## Models Implemented

- Decision Tree (CART)  
- Random Forest (Hyperparameter Optimized)  
- CatBoost (Final Model)  

---

## Model Performance

- CatBoost achieved the highest AUC (≈ 0.845), showing strong ability to rank customers by churn risk  

- Random Forest achieved the highest Recall (0.773) and F1-score (0.636), making it more effective at identifying churners  

- Decision Tree models showed lower performance, indicating limited ability to capture complex patterns  

This demonstrates a trade-off between:
- maximizing detection of churners (Recall)  
- accurately ranking churn probability (AUC)  

---

## Model Stability

The final model (CatBoost) achieved a cross-validated AUC of approximately 0.846 with low standard deviation, indicating strong model stability and generalization  

---

## Key Drivers of Churn

Churn is primarily driven by:

- Customer tenure (early-stage customers are more likely to churn)  
- Pricing (higher monthly charges increase churn risk)  
- Contract type (month-to-month contracts increase churn)  
- Service features (service quality and availability affect retention)  

---

## Business Insights

- Customers with short tenure are at highest risk  
- Month-to-month contracts significantly increase churn probability  
- Higher pricing correlates with increased churn  
- Lower service engagement is associated with churn  

---

## Recommendations

- Improve early-stage customer engagement  
- Encourage long-term contracts through incentives  
- Optimize pricing strategy  
- Enhance service quality and bundled offerings  

---

## Project Structure

telco-customer-churn-analysis/

- telco_churn_analysis.ipynb  
- telco_churn_analysis.html  
- telco_customer_churn.csv  
- README.md  

---

## Tools and Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- CatBoost  
- Jupyter Notebook  

---

## Key Takeaway

Churn is predictable and driven by clear behavioral and business factors.

This project demonstrates how machine learning can be used not only to predict churn but also to generate actionable insights for improving customer retention.
