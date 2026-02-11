# Retail Order Prioritization Dashboard

## Project Overview

This project uses a structured retail transaction dataset to develop a data-driven order prioritization and cost-efficiency dashboard. The objective is to analyze transaction patterns and identify which orders contribute the most business value, how spending behavior varies across customers and categories, and how operational focus can be optimized.

The system is designed to support:

- Revenue concentration analysis  
- Customer value segmentation  
- Pricing and quantity behavior analysis  
- Strategic order prioritization decisions  

This project focuses on transforming raw transaction data into actionable business insights for smarter retail and e-commerce operations.

---

## Dataset Source

The dataset used in this project is publicly available on Kaggle:

Retail Store Sales (Dirty for Data Cleaning)  
https://www.kaggle.com/datasets/ahmedmohamed2003/retail-store-sales-dirty-for-data-cleaning

---

## File Details

- Dataset Name: Retail Transaction Dataset  
- Total Records: ~12,600 transactions  
- Primary Identifier: Transaction ID  
- Time Component: Transaction Date  

---

## Data Dictionary

| Column Name      | Description                                                        | Data Type   |
|------------------|--------------------------------------------------------------------|------------|
| Transaction ID   | Unique identifier for each transaction                             | String     |
| Customer ID      | Unique identifier for each customer (25 unique customers)          | String     |
| Category         | Category of the purchased item (8 categories)                      | Categorical|
| Item             | Name of the purchased item (200 unique items; ~10% missing values) | String     |
| Price Per Unit   | Static price of a single unit of the item                          | Float      |
| Quantity         | Number of units purchased in the transaction                       | Integer    |
| Total Spent      | Total amount spent in the transaction                              | Float      |
| Payment Method   | Method of payment (Cash, Digital Wallet, Other)                    | Categorical|
| Location         | Transaction channel (Online / In-store)                            | Categorical|
| Transaction Date | Date of the transaction                                            | Date       |

---

## Planned Analysis Areas

### 1. Revenue Concentration Analysis
Evaluate whether a small percentage of customers or transactions contribute a large share of total revenue.

### 2. High-Value Transaction Identification
Define thresholds for high-impact transactions based on Total Spent and Quantity.

### 3. Customer Value Segmentation
Identify high-spending customers and analyze spending patterns across the 25 unique customers.

### 4. Category Performance
Analyze revenue distribution across product categories and examine differences in purchasing behavior.

### 5. Channel and Payment Insights
Compare transaction value patterns across Online vs In-store purchases and across different payment methods.

---

## Proposed KPIs (To Be Computed)

- High-Value Transaction Contribution (%)
- Average Order Value (AOV)
- Revenue Share by Customer
- Revenue Share by Category
- Online vs In-store Revenue Ratio
- Payment Method Revenue Distribution

Final KPI values will be computed during the analysis phase.

---

## Data Cleaning Notes (Planned)

- Handle missing values in Item, Price Per Unit, Quantity, and Total Spent  
- Convert Transaction Date to datetime format  
- Validate consistency between Price Per Unit × Quantity and Total Spent  
- Identify and evaluate potential outliers  

---

## Intended Outcome

The final dashboard aims to provide:

- A clear visualization of revenue distribution  
- Insight into high-impact transactions  
- Decision-support thresholds for order prioritization  
- A framework for improving operational efficiency using transaction-level data  

---

## Status

Project currently in development.  
All findings, thresholds, and statistical results will be generated after full exploratory data analysis and dashboard implementation.
