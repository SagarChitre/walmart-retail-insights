# Walmart Sales Analytics

## 📊 Project Overview

This project analyzes a dataset of 10,000+ Walmart sales transactions to uncover key business insights across multiple dimensions including revenue trends, customer behavior, product performance, and operational efficiency. The analysis addresses critical business questions that drive strategic decision-making in retail operations.

## 🗃️ Dataset Information

**Source**: Kaggle - Walmart 10K Sales Dataset  
**Records**: 10,000+ transactions  
**Time Period**: 2022-2023  

## 🛠️ Technical Implementation

### Technologies Used
- **Database**: MySQL
- **IDE**: MySQL Workbench
- **Language**: SQL
- **Analysis**: Advanced SQL functions, CTEs, Window functions

### Key SQL Techniques Demonstrated
- Complex JOINs and subqueries
- Window functions (RANK, ROW_NUMBER)
- Common Table Expressions (CTEs)
- Date/Time manipulation and conversion
- Aggregate functions and GROUP BY operations
- CASE statements for conditional logic

### Dataset Schema
'''
invoice_id int64
Branch object
City object
category object
unit_price float64
quantity float64
date object
time object
payment_method object
rating float64
profit_margin float64
'''

## 🎯 Business Problems Solved

### 1. Operational Infrastructure Analysis
- **Branch Network Assessment**: Total number of distinct branches
- **Payment Infrastructure**: Types of payment methods accepted

### 2. Customer Behavior & Transaction Analysis  
- **Payment Preferences**: Transaction patterns by payment method
- **Regional Payment Trends**: Most common payment methods per branch

### 3. Product Performance & Category Analysis
- **Category Excellence**: Highest-rated categories by branch
- **Geographic Performance**: Category ratings across different cities
- **Profitability Analysis**: Total profit and popularity by category

### 4. Operational Efficiency & Resource Management
- **Peak Day Identification**: Busiest transaction days per branch
- **Shift Analysis**: Sales distribution across Morning/Afternoon/Evening shifts

### 5. Strategic Performance & Trend Analysis
- **Revenue Decline Analysis**: Year-over-year performance comparison
- **Performance Monitoring**: Identification of underperforming branches


## 📈 Key Insights & Findings

### Revenue & Profitability
- Calculated total profit using formula: `unit_price × quantity × profit_margin`
- Identified most profitable product categories
- Analyzed transaction volume vs. profitability correlation

### Operational Efficiency
- Determined optimal staffing requirements based on peak days
- Analyzed shift-wise sales distribution for resource allocation
- Identified payment method preferences for infrastructure optimization

### Performance Monitoring
- Year-over-year revenue comparison revealing performance trends
- Branch-wise category performance analysis
- Customer satisfaction metrics across different locations

### Setup Instructions
1. Download the 'Walmart.csv' dataset mentioned in the repository.

2. Import the dataset in your IDE for python and proceed with the steps mentioned in 'python.ipynb' file. This file includes Exploratory Data Analysis, Data Cleaning and establishing connection with MySQL.

3. After completing the previous step, use a sql editor (MySQL Workbench or Command Prompt) to execute the queries in 'Analysis.txt' file where every operation and it's business impact is explained.

## 📊 Business Impact

This analysis provides actionable insights for:
- **Inventory Management**: Optimizing stock levels based on category performance
- **Staffing Decisions**: Aligning workforce with peak business periods  
- **Payment Infrastructure**: Optimizing payment systems based on customer preferences
- **Strategic Planning**: Identifying underperforming locations for intervention
- **Customer Experience**: Improving satisfaction through data-driven decisions
