# Telecommunication Customer Churn Analysis & EDA
## Project Overview
Customer churn is one of the most critical metrics for any telecommunication company. This project involves a deep-dive Exploratory Data Analysis (EDA) on a Telco dataset to identify the key factors that lead to customer attrition. By analyzing demographics, account information, and service usage patterns, this project aims to provide actionable insights that can help a business reduce churn and improve customer retention strategies.

## Dataset Description
The dataset contains 7,043 customer records with 21 features. Key attributes include:

- Demographics: Gender, Senior Citizen status, Partner, and Dependents.

- Services: Phone service, multiple lines, internet service (DSL/Fiber optic), and security add-ons like Online Security, Tech Support, and Streaming.

- Account Info: Tenure, Contract type (Month-to-month, One year, Two year), Payment Method, and Paperless Billing.

- Financials: Monthly Charges and Total Charges.

- Target: Churn (Whether the customer left within the last month).

## Visualizations & Their Purpose
In this project, I utilized various visualization techniques to uncover patterns in the data:

- 1.Churn Distribution (Count Plots):

  Purpose: To understand the class imbalance between churned and retained customers. This sets the baseline for the entire analysis.

- 2.Contract Type vs. Churn:

  Purpose: To analyze how different contract terms (e.g., Month-to-month vs. Two-year) impact loyalty. Usually, short-term contracts show significantly higher churn rates.

- 3.Tenure & Monthly Charges (Histograms/KDE Plots):

  Purpose: To identify if "newer" customers are more likely to leave and to see if higher monthly costs are a driving factor for attrition.

- 4.Service Utilization (Bar Charts):

  Purpose: To compare churn rates across different services (like Fiber Optic vs. DSL). This helps identify if specific service issues or pricing are causing customers to leave.

- 5.Payment Method Analysis:

  Purpose: To determine if certain payment methods (like Electronic Checks) correlate with higher churn compared to automatic credit card or bank transfers.

## Tech Stack
- Language: Python

- Libraries: Pandas (Data Manipulation), Matplotlib & Seaborn (Data Visualization), NumPy (Numerical Operations)

- Environment: Jupyter Notebook / Google Colab 

## Key Business Insights (Project Highlights)
- High-Risk Segments: Identified that customers on Month-to-month contracts and those using Fiber Optic internet service have higher churn tendencies.

- Retention Factors: Long-term contracts and additional security services (Online Security, Tech Support) significantly increase customer stickiness.

- Financial Impact: Analyzed the relationship between TotalCharges and Tenure to show how long-term retention directly correlates with increased Customer Lifetime Value (CLV).
