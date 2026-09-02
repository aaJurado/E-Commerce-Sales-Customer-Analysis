# E-Commerce Sales & Customer Analysis

An end-to-end e-commerce analytics project using Python, Pandas, Matplotlib, and RFM customer segmentation.

## Project Overview

This project analyzes more than 500,000 online retail transactions to evaluate sales performance, customer behavior, product performance, geographic trends, and returns.

The analysis focuses on identifying business insights that could support inventory planning, customer retention, international growth, and revenue optimization.

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- VS Code

## Dataset

The project uses the Online Retail dataset from the UCI Machine Learning Repository.

The dataset contains transaction-level information including:

- Invoice number
- Product code
- Product description
- Quantity
- Invoice date
- Unit price
- Customer ID
- Country

## Data Cleaning

The raw dataset contained:

- 541,909 rows
- 5,268 duplicate rows
- 1,454 missing product descriptions
- 135,080 missing customer IDs
- 10,624 negative-quantity transactions
- 2,517 zero or negative-price transactions

Completed sales, returns, and customer-level data were separated so each could be analyzed appropriately.

## Key Performance Indicators

- **Total Revenue:** £10,642,110.80
- **Total Orders:** 19,960
- **Units Sold:** 5,572,420
- **Unique Products:** 3,922
- **Average Order Value:** £533.17

## Key Findings

- November 2011 was the highest-revenue month, generating approximately **£1.50 million**.
- Revenue increased strongly from September through November, indicating significant seasonal demand.
- **REGENCY CAKESTAND 3 TIER** was the highest-revenue merchandise product.
- **PAPER CRAFT, LITTLE BIRDIE** was the highest-volume product with approximately 80,995 units sold.
- The United Kingdom accounted for the majority of total revenue.
- The Netherlands, EIRE, Germany, and France were the strongest international markets.
- Customer 14646 was the highest-value customer, generating approximately £280,206 in revenue.
- RFM analysis identified 867 Champions, 805 Loyal Customers, and 999 customers needing attention.
- Returns and cancellations represented an estimated value of approximately £893,980.

## RFM Customer Segmentation

Customers were segmented using:

- **Recency** — how recently a customer purchased
- **Frequency** — how many orders a customer placed
- **Monetary Value** — how much revenue a customer generated

The resulting segments were:

- Champions
- Loyal Customers
- Potential Loyalists
- Needs Attention
- At Risk

## Business Recommendations

- Increase inventory support for high-performing products.
- Prepare for stronger demand during September through November.
- Expand marketing efforts in strong international markets.
- Develop retention campaigns for Champions and Loyal Customers.
- Create re-engagement campaigns for At Risk and Needs Attention customers.
- Investigate the causes of returns and cancellations to reduce revenue loss.

## Project Files

- `ecommerce_analysis.ipynb` — complete Python analysis and visualizations
- `data_source.md` — dataset source information

## Author

Axel Jurado
