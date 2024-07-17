# Online Retail Sales Dashboard

## Overview
This project consists of an interactive dashboard for e-commerce sales analysis, using the "Online Retail" dataset available on the UCI Machine Learning Repository.

## Tools Used
- Power BI
- Power Query Editor

## Metrics and KPIs
- Total revenue
- Number of sales
- Average ticket
- Number of unique customers
- Best-selling product categories
- Sales by country
- Sales over time

## Calculations
- Revenue = [Quantity] * [UnitPrice]
- DAX Average Ticket = DIVIDE(SUM('Online Retail'[Revenue]), COUNT('Online Retail'[InvoiceNo]))

## Visualizations
- Line chart for total revenue per month
- Line chart for number of sales per month
- Line chart for number of customers per month
- Bar chart for top 10 best-selling products

## How to Run
1. Download the `OnlineRetailDataset.pbix` file and the `Online Retail.xlsx` dataset.
2. Open the file in Power BI Desktop.
3. Explore the visualizations and interact with the date filters.

## Screenshots
![Dashboard Overview](/screenshot.png)
