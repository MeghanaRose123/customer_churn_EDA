# customer_churn_EDA
Exploratory data analysis on telecom customer churn finding why 1 in 4 customers leave using Python and Seaborn
# Customer Churn Analysis — Telecom Dataset

## Problem Statement
A telecom company is losing 1 in 4 customers. 
This project analyzes customer data to find 
who is churning and why.

## Dataset
- Source: Kaggle Telco Customer Churn
- Rows: 7032 customers
- Columns: 21 features including contract type, 
tenure, monthly charges

## Key Business Insights
1. Overall churn rate is 26.58%
2. Month-to-month customers churn at 42.7% vs 
   only 2.8% for 2-year contract customers
3. Churned customers stayed an average of 18 months 
   vs 37 months for loyal customers
4. Churned customers paid an average of ₹74/month 
   vs ₹61 for loyal customers

## Recommendations
- Push customers toward longer contracts
- Offer loyalty discounts to high-paying 
  month-to-month customers
- Focus retention efforts on customers 
  in their first 18 months

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

## Model Results
| Model | Accuracy | Recall |
|-------|----------|--------|
| Logistic Regression | 78.7% | 0.50 |
| Random Forest | 77.8% | 0.47 |
| Tuned Random Forest | 78.5% | 0.47 |

Best Model: Logistic Regression
Top 3 Features: Total Charges, Tenure, Monthly Charges
