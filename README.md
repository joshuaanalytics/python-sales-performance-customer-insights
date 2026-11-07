# Retail Sales Performance & Customer Insights

**Python Programming Data Analyst Capstone — Option A**

## Project Overview

This project analyzes a synthetic Philippine retail/e-commerce dataset to understand store performance, customer purchasing behavior, product performance, regional sales, and returns.

The analysis uses Python and Pandas for data cleaning, preparation, integration, and calculation. Matplotlib is used to create charts and a consolidated dashboard.

## Business Question

**How is the store performing, and what drives revenue?**

## Executive Summary

- This project examined sales performance and customer insights using a synthetic Philippine retail/e-commerce dataset.
- Seven related datasets were reviewed, cleaned, and prepared using Python and Pandas.
- The analysis produced an integrated sales fact table based on completed and shipped orders.
- Total merchandise revenue was ₱5,293,430.12 across 11,601 eligible orders.
- Average order value was ₱456.29.
- Repeat customers represented 74.8% of purchasing customers.
- Toys recorded the highest category revenue at ₱738,320.75.
- Central Luzon generated the highest regional revenue at approximately ₱926,983.
- The findings highlight opportunities to review product profitability, support customer retention, monitor regional performance, and investigate returns.

## Key Findings

- Merchandise revenue was **₱5,293,430.12** across **11,601 eligible orders**.
- Average order value was **₱456.29**.
- The repeat customer rate was **74.8%** (3,378 repeat customers out of 4,519 purchasing customers).
- Toys generated the highest category revenue at **₱738,320.75**.
- Central Luzon recorded the highest regional revenue at approximately **₱926,983**.
- The return-record rate was **8.2%**, based on eligible orders with at least one associated return record.
- Annual revenue decreased by approximately **1.8%** from 2024 to 2025.

## Project Files

### Notebook
- [YourNotebook.ipynb](YourNotebook.ipynb)

### Cleaned Data
- [Cleaned Customers](data/cleaned_customers.csv)
- [Cleaned Products](data/cleaned_products.csv)

### Executive Summary
- [Executive Summary.txt](Executive%20Summary.txt)

### Charts and Dashboard
- [Monthly Revenue](charts/01_monthly_revenue.png)
- [Top 10 Products](charts/02_top_10_products.png)
- [Revenue by Region](charts/03_revenue_by_region.png)
- [Customer Spend Distribution](charts/04_customer_spend_distribution.png)
- [Monthly Returns](charts/05_monthly_returns.png)
- [Dashboard — 1920 × 1080](charts/dashboard_1920x1080.png)

### One-Page Insights Summary
- [One-Page Insights Summary](One-Page%20Insights%20Summary.md)

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Methodology

The project involved loading seven related CSV datasets, checking and cleaning records, standardizing categories, handling missing and invalid values, validating relationships between datasets, and preparing an integrated sales fact table.

Sales analysis focused on completed and shipped orders. Merchandise revenue is measured after discounts and before refunds, excluding shipping charges.

## Data Note

The datasets used in this capstone are synthetic training data. Findings describe the supplied dataset and should not be interpreted as actual business performance.

## Recommendations

Review product profitability alongside revenue, strengthen customer retention efforts, investigate regional sales patterns, monitor monthly performance, and examine return reasons for opportunities to improve the customer experience.
