## 📌 Navigation
Click any section in the navigation above to jump directly to that part of the project.<br>
[Project Overview](#project-overview) •
[Data Structure](#data-structure) •
[Executive Summary](#executive-summary) •
[Overview of Findings](#overview-of-findings)

[Key Findings & Insights](#key-findings--insights)

# Project Overview </ln>
OmniCore Retail is an international e-commerce company that sells consumer electronic products across multiple countries through its digital platforms. As the company expands globally, management requires a unified and reliable view of sales performance to better understand customer behavior, product trends, and overall business health.

Sales data was originally stored across multiple Excel workbooks, with individual worksheets representing different countries. This fragmentation limited visibility into global performance and made analysis inefficient. This project focuses on cleaning, standardizing, and integrating these datasets into a single source of truth, followed by the development of an interactive Power BI dashboard to support data-driven decision-making.

Insights and deliverables from this project are structured around the following key areas:

- **Data Cleaning & Standardization:** Raw sales data was cleaned using Power Query by reinforcing correct data types, standardizing text fields (such as country names and product attributes), handling null values, and resolving common data quality issues. <br>
- **Data Integration:** Sales data from multiple country worksheets and Excel files were appended and consolidated into a unified FactSales table, ensuring consistency and reliability across regions. <br>
- **Data Quality Assurance:** Duplicate records—including repeated rows and redundant columns—were identified and removed to maintain data accuracy and integrity. <br>
- **Business Metrics & KPIs:** Core performance metrics were calculated, including Total Sales, Net Sales, Total Orders, and Average Order Value (AOV), providing a clear view of commercial performance. <br>
- **Executive Dashboard Delivery:** A clear, single-page Power BI dashboard was developed, enabling stakeholders to monitor global performance, analyze customer behavior, and identify product trends at a glance. <br>

This project transforms fragmented raw data into actionable insights, empowering leadership with a centralized analytics solution for improved strategic decision-making.

# Data Structure 
The data model consists of 4 tables; FactSales, dimCustomer, dimDate, dimProduct

<p align = "center">
  <img src="https://github.com/P-O-I-sql/E-commerce-Sales-Analysis/blob/467242c532783cbf8ca9167dc76a67eeae9bbb71/E-commerce%20sales%20ERD.png" alt = "E-commerce Sales ERD"
  height = "500" width = "700"> <br>
  <em> E-commerce Sales ERD </em>
</p>

# Executive Summary
## Overview of Findings

Overall company sales have exhibited moderate fluctuations from January 2020 to the present, reaching a peak in Q2 2020 before declining to a trough in Q4 2021. Since then, performance has shown recurring seasonal patterns, with sales typically declining between Q3 and Q4 each year. An exception to this trend occurred in 2023, where the decline shifted into Q1 2024.

These seasonal downturns appear to be driven in part by reduced demand in specific product categories, notably books, which consistently experience year-over-year sales declines in Q4. Despite these fluctuations, the business has maintained a substantial sales footprint over the period analyzed.

Key performance indicators for the period include total sales of approximately $91.83M, net sales of $76.65M, and nearly 100,000 total orders, resulting in an average order value (AOV) of $918.26.

You can Download the dashboard **[here](https://raw.githubusercontent.com/P-O-I-sql/E-commerce-Sales-Analysis/main/E-commerce%20Sales%20Analysis.pbix)**.

<p align="center">
  <img src="https://github.com/P-O-I-sql/E-commerce-Sales-Analysis/blob/6892c3337553d014b7b58246820fffdfd46abb6b/E-commerce%20Sales%20Dashboard.png" alt="E-commerce Sales Dashboard" height = "500" width="700"><br>
  <em> E-commerce Sales Analysis dashboard (Power BI) </em>
</p>

## Key Findings & Insights

<p align = "center">
  <img src="https://github.com/P-O-I-sql/E-commerce-Sales-Analysis/blob/083e3d1c41d915cb1caa66d4b9f81fc38a0a678d/E-commerce%20Sales%20trend.png" alt = "E-commerce Sales trend"
  height = "500" width = "700"> <br>
</p>

 **Global Performance:**
- Across all markets, the company generated approximately $91.83M in total sales and $76.65M in net sales, supported by nearly 100,000 total orders.
- Sales performance varies significantly by region, with a small number of countries contributing a disproportionate share of total revenue.
- The United States consistently outperformed all other regions across the entire period analyzed.
- Sales peaked in Q2 2022 and reached their lowest point in Q1 2021.
- From Q1 2020 to Q4 2024, sales exhibited consistent fluctuations with recurring seasonal declines in Q3 and Q4, followed by recovery in Q1 of the subsequent year.

 **Customer Behavior:**
- Customer purchasing behavior appears inconsistent, as reflected in fluctuating year-over-year sales trends.
- Seasonal purchasing patterns play a significant role in customer activity, contributing to periodic spikes and declines in sales.
- These patterns suggest opportunities to improve customer engagement, retention, and purchase frequency during off-peak periods.

 **Product Trends:**
- Revenue contribution is not concentrated in a small set of products; instead, it is evenly distributed across the product portfolio.
- Memory Card 128GB is the highest revenue-contributing product, while Children’s Books contribute the least (~1.89%) and have experienced a steady decline in sales since Q4 2020.
- Product sales trends fluctuate consistently across all items, with sharp declines typically occurring after peak sales periods, reinforcing the presence of seasonality.
- Most products contribute approximately 1.89%–2.12% of total revenue, indicating a balanced and resilient product mix with minimal single-product risk.

 **Recommendations** <br>
Based on the conducted analysis and insights, the following actions are recommended: <br>

- Conduct a deeper review of regional performance, particularly in the United Kingdom and Australia, as a single country accounts for approximately 70% of total sales, while other regions underperform.
- Perform further analysis to identify key drivers behind seasonal demand and inconsistent sales trends.
- Evaluate the effectiveness of Cash on Delivery payment methods, as they contribute less than 5% of total transactions and may be operationally inefficient.
- Develop targeted customer engagement strategies to improve customer retention, customer lifetime value (CLV), and order frequency, especially during low-demand periods.




