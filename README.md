# Financial-Risk-Analysis-with-Python-Goldman-Sachs-Financial-Analysis-Dataset-

## 🎯 Project Objective

The primary objective of this project is to perform an end-to-end financial transaction and risk analysis using Python. The project focuses on transforming raw banking transaction data into actionable insights by:

Cleaning and standardizing financial data

Analyzing transactional behavior over time

Profiling customers based on activity, balance, and inflow patterns

Identifying dormant accounts and high-risk financial behavior

Detecting anomalies and potential financial risks

Supporting insights with statistical hypothesis testing and visual analytics

This project demonstrates how data analytics can support risk monitoring, customer segmentation, and decision-making in a financial institution.


## Goldman Sachs Raw Dataset Used :
- <a href="https://github.com/laganmehra875/Financial-Risk-Analysis-with-Python-Goldman-Sachs-Financial-Analysis-Dataset-/blob/main/goldman_sachs.csv"> Raw Dataset used : Goldman sachs


## Goldman Sachs Project jupyter file :
- <a href="https://github.com/laganmehra875/Financial-Risk-Analysis-with-Python-Goldman-Sachs-Financial-Analysis-Dataset-/blob/main/python%20project%20copy.ipynb"> Goldman Sachs Python Project </a>


## 🔍 Key Findings

### 1. Data Quality & Structure

The dataset contains 800 transactions across 188 customers with no missing values.

Financial fields were successfully standardized, dates were validated, and categorical variables were normalized.

No duplicate records were found, ensuring high data integrity.

### 2. Transactional Behavior Analysis
   
Transactions are well distributed across Credit, Savings, Loan, and Current accounts.

Monthly analysis revealed fluctuating credit and debit volumes, with debits (withdrawals, payments, transfers) dominating several periods.

Net transaction flow varies significantly across accounts, indicating uneven liquidity behavior.


### 3. Account Performance
 
Top-performing accounts showed strong positive net inflows exceeding ₹120K.

Bottom-performing accounts experienced heavy net outflows exceeding ₹130K.

Several high-balance accounts still exhibited negative net inflows, signaling potential cash-flow stress.


### 4. Dormancy & Activity Levels

Accounts were flagged as dormant when transaction gaps exceeded 60 days.

Based on transaction frequency:

Most customers fell into the Low Activity category.

Very few customers showed sustained high monthly activity.

This highlights a large base of passive or low-engagement customers.

### 5. Customer Segmentation Insights
 
High-net inflow customers are limited but crucial for revenue stability.

High-frequency, low-balance customers were identified—indicating operational usage without balance accumulation.

No significant number of accounts had persistent negative balances, but some showed near-zero average balances.****


### 6. Risk Identification & Volatility

A small number of accounts showed overdraft behavior.

Balance volatility analysis (Coefficient of Variation) identified accounts with unstable financial patterns.

Z-score analysis detected balance anomalies, though transaction amount anomalies were minimal.

No extreme suspicious transaction behavior was statistically confirmed, suggesting overall system stability.

### 7. Hypothesis Testing Results

Statistical tests showed no significant difference in average balances between high-volume and low-volume transaction customers.

This indicates that transaction frequency alone does not predict higher balances, an important insight for customer valuation models.



