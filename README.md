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
##### 📊 Visual & Exploratory Insights :
- <a href="https://github.com/laganmehra875/Financial-Risk-Analysis-with-Python-Goldman-Sachs-Financial-Analysis-Dataset-/blob/main/line%20plot.png"> Monthly Credits vs Debits</a>


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


## 📊 Visual & Exploratory Insights

Account balance distribution is right-skewed, with most balances concentrated in mid-range values.
- <a href="https://github.com/laganmehra875/Financial-Risk-Analysis-with-Python-Goldman-Sachs-Financial-Analysis-Dataset-/blob/main/bell%20shaped.png"> Balance Distribution </s>

Scatter plots show weak correlation between transaction volume and average balance.
- <a href="https://github.com/laganmehra875/Financial-Risk-Analysis-with-Python-Goldman-Sachs-Financial-Analysis-Dataset-/blob/main/scatter.png"> Average Balance vs. Total Transaction Volume </a>

Boxplots revealed transaction outliers but within acceptable risk thresholds.
- <a href=""> Transaction Amount Outliers </a> 



## 💡 Recommendations

#### 1. Target High-Net Inflow Customers
   Offer premium services and retention programs to customers contributing consistent positive inflows.

#### 2. Re-engage Dormant Accounts
   Launch engagement campaigns for inactive customers to increase transaction activity.

#### 3. Monitor High-Frequency Low-Balance Users :
   These accounts may benefit from overdraft protection, micro-savings plans, or fee optimization.

#### 4. Enhance Risk Monitoring 
   Continuously track balance volatility and overdraft signals to proactively manage risk.

#### 5. Improve Customer Valuation Models    
   Combine transaction behavior with balance stability instead of relying solely on transaction volume.

#### 6. Automate Anomaly Detection   
   Integrate Z-score or IQR-based alerts into real-time monitoring systems.


## ✅ Conclusion

This project successfully demonstrates how Python-based financial analytics can transform transactional data into meaningful business insights. Through structured data cleaning, exploratory analysis, customer profiling, and risk assessment, the analysis highlights both financial stability patterns and potential risk areas.

The findings confirm that transaction behavior is multifaceted and must be analyzed alongside balance trends and volatility to accurately assess customer value and financial risk
