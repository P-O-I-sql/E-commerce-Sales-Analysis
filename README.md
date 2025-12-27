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

<p align="center">
  <img src="https://github.com/P-O-I-sql/E-commerce-Sales-Analysis/blob/6892c3337553d014b7b58246820fffdfd46abb6b/E-commerce%20Sales%20Dashboard.png" alt="E-commerce Sales Dashboard" height = "500" width="700"><br>
  <em> E-commerce Sales Analysis dashboard (Power BI) </em>
</p>

Download the dashboard **[here](https://raw.githubusercontent.com/P-O-I-sql/E-commerce-Sales-Analysis/main/E-commerce%20Sales%20Analysis.pbix)**.



