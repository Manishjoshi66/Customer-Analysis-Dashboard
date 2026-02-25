👇

 # 🛒 Customer Shopping Behavior Analysis
 ## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective is to uncover actionable business insights related to spending patterns, customer segmentation, subscription behavior, and product performance.

The analysis was performed using Python (Pandas), PostgreSQL (SQL), and Power BI to create a complete end-to-end data analytics workflow.

# DataSet Used 
<a href ="https://github.com/Manishjoshi66/Customer-Analysis-Dashboard/blob/main/customer_shopping_behavior.xlsx.csv">Dataset</a><br>
<a href ="https://github.com/Manishjoshi66/Customer-Analysis-Dashboard/blob/main/customer_behaviour.pdf">DashBoard</a>

## 📊 Dataset Summary

Rows: 3,900

Columns: 18

Key Features:

Customer demographics (Age, Gender, Location, Subscription Status)

Purchase details (Item, Category, Amount, Season, Size, Color)

Behavioral metrics (Discount Applied, Previous Purchases, Frequency, Review Rating, Shipping Type)

Missing Values: 37 values in Review Rating (handled using median imputation per category)

## 🐍 Data Cleaning & Preparation (Python)

Data loading and initial exploration

Handling missing values

Column standardization (snake_case formatting)

Feature engineering:

Created age_group

Created purchase_frequency_days

Removed redundant columns

Loaded cleaned dataset into PostgreSQL for SQL analysis

## 🗄️ Business Analysis using SQL(KPI's)

Revenue comparison by gender

High-spending customers using discounts

Top 5 products by rating

Average purchase comparison (Standard vs Express shipping)

Subscribers vs Non-Subscribers revenue comparison

Discount-dependent products

Customer Segmentation:

New (1 purchase)

Returning (2–10 purchases)

Loyal (>10 purchases)

Top 3 products per category

Repeat buyers & subscription relationship

Revenue contribution by age group

## 📈 Power BI Dashboard

An interactive dashboard was created to visualize:

Total Customers

Average Purchase Amount

Average Review Rating

Revenue by Category

Revenue & Sales by Age Group

Subscription Distribution

Shipping Type Comparison

The dashboard provides clear business insights for decision-making.

💡 Business Recommendations

Promote subscription-based benefits

Implement loyalty reward programs

Optimize discount strategies

Highlight top-rated & high-performing products

Focus marketing on high-revenue age groups

🛠️ Tools & Technologies

Python (Pandas, SQLAlchemy)

PostgreSQL

Power BI

Jupyter Notebook


## Dashboard
<img width="703" height="502" alt="Screenshot 2026-02-24 153212" src="https://github.com/user-attachments/assets/53b7a324-7dea-4b74-b1f3-f607fe5f3d4b" /> 

