 # Customer Churn Analysis

 ## Description

This project performs an in-depth Customer Churn Analysis using a telecom dataset. The analysis identifies key factors that influence customer retention and churn behavior. Through exploratory data analysis (EDA), visualization, and feature correlation, it reveals which customer demographics and service patterns are most associated with churn.

## Purpose

The goal of this project is to understand why customers leave and provide actionable insights to help the business improve retention.

## Objectives:
Analyze demographic and usage patterns related to customer churn.
Identify high-risk customer segments.
Provide data-driven strategies to reduce churn rates and improve customer loyalty.

##  Tech Stack

Python
pandas — Data cleaning and manipulation
numpy — Statistical analysis
matplotlib, seaborn — Data visualization
scikit-learn — (if included) modeling and prediction
Jupyter Notebook — For interactive exploration and reporting
<img width="887" height="560" alt="Screenshot 2026-02-11 163439" src="https://github.com/user-attachments/assets/921992e5-e44d-456e-ae2b-0238f7d1339d" />

# how to use this code 

Open the ChurnProject.ipynb file in Jupyter Notebook and upload your new customer CSV file (same format).
Press **Shift + Enter** to run each cell or go to **Kernel → Restart & Run All** to run everything at once.
After it finishes, scroll down to see which customers are predicted to leave.


 ## Features / Highlights
Data Cleaning & Preprocessing
Handled missing and blank values.
Converted categorical variables and binary columns (Yes/No, 0/1).
Exploratory Data Analysis (EDA)
Visualized churn distribution and demographics (Gender, Senior Citizen, Tenure).
Analyzed service usage and contract type impact on churn.

## Key Insights & Findings:
● ###	Contract Type and Churn:
○	Customers on month-to-month contracts exhibit the highest churn rate, with 42% of such customers likely to churn.
○	In contrast, customers on one-year and two-year contracts have churn rates of 11% and 3%, respectively.
○	Implication: Longer contract periods serve as a strong retention tool, as customers with extended commitments are far less likely to leave.
●	### Payment Methods and Churn:
○	Customers paying via electronic checks show the highest churn rate at 45%, while those using credit cards, bank transfers, or mailed checks have significantly lower churn rates, averaging around 15-18%.
○	Implication: The convenience, security, and trust issues related to electronic payments might be contributing factors. Encouraging customers to switch to more stable payment methods could reduce churn.
●	### Churn by Tenure:
○	Customers with less than one year of tenure are the most likely to churn, with a 50% churn rate. Those with 1-3 years of tenure show a decreasing churn trend at 35%, while customers who have been with the company for more than three years have a churn rate of just 15%.
○	Implication: Engaging customers early in their journey, especially within the first year, is critical for retention.
●	### Churn by Internet Service Type:
○	Customers using Fiber Optic services show a higher churn rate of 30%, compared to DSL customers with a churn rate of 20%.
○	Implication: This could be due to increased competition or dissatisfaction with service quality. Understanding customer satisfaction with service speed and reliability may help retain fiber optic users.
●	Senior Citizens and Churn:
○	The analysis reveals that senior citizens (aged 65+) have a churn rate of 41%, compared to a 26% churn rate among non-senior citizens.
○	Implication: Special retention programs and targeted customer service for senior customers may help reduce churn in this demographic.


## Visualization
Bar charts, stacked plots, and heatmaps showing churn behavior and trends.

 ## Business Problem

Customer churn is a major challenge in subscription-based industries like telecom. Retaining customers is significantly more cost-effective than acquiring new ones. However, identifying which customers are likely to churn and why is complex without data-driven insights.

## Business Impact
This analysis enables organizations to:
Reduce Customer Churn: Identify at-risk customers early and implement targeted retention strategies.
Optimize Marketing Spend: Focus on high-value customer segments more likely to stay.
Enhance Customer Satisfaction: Improve services and support for high-churn demographics.
Drive Profitability: Lower churn directly contributes to long-term revenue stability.

## Insights Summary
Churn Rate: ~26.5%
High-Risk Groups: Senior citizens, customers with shorter tenure, and those on month-to-month contracts.
Retention Strategy: Offer loyalty discounts, long-term contract incentives, and better customer support for vulnerable groups.




https://github.com/SaloniVerma7/Customer-Churn-Analysis/blob/main/Reason%20of%20Customer%20Churn.png




