# Fetch_Rewards_2025

Analysis Performed
-- Data Quality Checks file
Missing Data: Significant null values in BRAND, MANUFACTURER, and BARCODE.
Inconsistent Dates: Cases where PURCHASE_DATE > SCAN_DATE.
Transaction-Product Mismatch: 20K+ transactions reference barcodes not found in the Product dataset.
Barcode Anomalies: 4K+ barcodes have fewer than 10 digits (potentially invalid).

-- SQL Queries (Business Questions)
Top 5 brands by receipts scanned (for users 21+ years old).
Top 5 brands by total sales (for users with accounts 6+ months old).
Identifying power users based on scanning frequency, longevity, and total spending.
Year-over-year and month-over-month user growth analysis.

-- Business Findings & Insights
Users with accounts older than 6 months contribute the highest total sales, indicating strong retention and spending behavior.
There is no strong correlation between receipt scanning frequency and total spending, suggesting that high-frequency users are not always the highest spenders.
Significant seasonality in Fetch’s user growth, with spikes during promotions.


dataquality_issues_takehome.ipynb - Showcases the data quality issues in the all the datasets 
second:SQL_queries - Solves business questions given
third_email - Email communication with stakeholders regarding data quality checks and outstanding questions
