# SQL_AtliQ_hardware_finance_supplychain_analytics
This SQL project is part of the Data Analyst Bootcamp at CodeBasics.

## Introduction
AtliQ hardware is a leading hardware company that specializes in Computer devices such as desktops, laptops, printers,
monitors, keyboards and mouse having a global reach of customers. The project involves performing financial and supply chain analytics on Atliq Hardware data, namely sales, market, product, customer, and supply chain data and performing the tasks that will help to make informed business decisions.

## Overview
The focus on use of Excel files has led to unresponsiveness and performance inefficiency. To overcome the problem, AtliQ Hardware hired data analysts. I will utilize MySQL as their database management system to extract meaningful insights from the data and reduce the dependency on Excel
files. 

## Financials concepts used 
- Pre-invoice deduction: yearly discount agreements made at the beginning of each financial year
- Post-invoice deduction: promotional offers + placement fees + performance rebate
- Cost of goods sold : manufacturing cost + freight cost + other cost

## Supply chain concepts used
- Forecast value: The predicted value of demand for products.
- Net error: The difference between forecast value and actual value.
- Absolute Net error: the positive value of net error even if the net error is negative
- Absolute Net error percent: Total absolute net error divided by total forecast value
- Forecast accuracy percent: 100 – absolute net error percent

## Business related tasks that this project addresses 
- Generating report for Croma India product-wise sales report for the Fiscal year - 2021.
- Generating report for Croma India gross monthly total sales report.
- Generating report for Croma India's gross yearly total sales report for each fiscal year.
- Generating report for Top 5 markets by net sales in fiscal year 2021.
- Generating report for Top 5 customers by net sales in fiscal year 2021.
- Generating report for Top 5 products by net sales in fiscal year 2021.
- Generating report for Top 10 customers by net sales percent.
- Generating report for Net sales percent by region.
- Generating report for Top 2 markets in each region in fiscal year 2021.
- Generating report for forecast accuracy for all customers in the fiscal year 2021.

## Skills learnt
- Data definition and data manipulation operations
- Implementing Data Integrity in Entity-Relationship Diagrams with the significance of Primary and Foreign Keys and cardinalities
- Handling various data types: numeric, string, date/time, JSON, and Spatial
- Various finance-related concepts.
- Various supply chain-related concepts.
- Using stored procedures and user-defined functions as many times many of the tasks are repetitive and queries are big and complex. Such time-stored procedures and user-defined functions can come in handy.
- Performance optimization by reducing the overall query execution time and easing the management of queries by implementing methods such as performing joins, creating a helper table, adding a new column, using CTEs, or using views.
- Using common table expressions, helper tables, and views.
- Windows functions (OVER along with PARTITION BY CLAUSE, ROW_NUMBER, RANK, DENSE_RANK).
- Using indexes

