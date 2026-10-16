# Data Exploration and Cleaning Strategy

A Python-based exploratory data analysis (EDA) and data sanitization pipeline designed to diagnose anomalies, handle missing values across MCAR/MAR/MNAR patterns, winsorize skewed outliers using the IQR method, and apply partition-safe feature scaling.

## 📌 Project Overview
- **Track:** Virtual Data Analytics Intern
- **Task:** Week 2 – Data Exploration and Cleaning Strategy
- **Tools:** Python, Pandas, NumPy, Scikit-Learn

## 🎯 Core Business Questions Addressed
1. **Revenue Skew:** Evaluating how missing transaction tokens and unverified refund logs distort Monthly Recurring Revenue (MRR) and Average Order Value (AOV) metrics.
2. **Churn Attribution:** Determining what proportion of apparent customer churn is driven by systematic null records and session timeouts rather than actual customer attrition.
3. **Logistics Bottlenecks:** Auditing delivery delays against standardized ISO-8601 timestamps to isolate real operational bottlenecks.
4. **Distribution Shifts:** Profiling feature variance across customer segments to evaluate dedicated scaling pipelines.

## 📂 Repository Contents
- `customer_transactions_sample.csv`: Sample transactional dataset containing representative anomalies (negative amounts, extreme outliers, casing inconsistencies, and missing values).
- `data_cleaning_pipeline.ipynb`: End-to-end Python pipeline implementing data ingestion, IQR winsorization, imputation, and Z-score standardization.
- `Week_2_Data_Exploration_and_Cleaning_Strategy.docx`: Comprehensive project report outlining data quality frameworks, methodology, validation thresholds, and best practices.

## 🚀 How to Run the Pipeline
1. Clone this repository:
   ```bash
   git clone [https://github.com/mishraunnati07-boop/data-exploration-cleaning-strategy.git](https://github.com/mishraunnati07-boop/data-exploration-cleaning-strategy.git)
