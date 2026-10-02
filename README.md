# brewmetrics-bi
A version-controlled Business Intelligence solution for BrewMetrics Coffee Co.

# BrewMetrics BI

## Project Overview

BrewMetrics BI is a Power BI business intelligence solution
developed for BrewMetrics Coffee Co. The project analyzes
transaction-level sales data across cities, store formats,
categories and products.

## Technologies

- Power BI Desktop
- GitHub
- GitHub Copilot
- Visual Studio Code
- DAX
- Power Query

## Data Model

The solution uses a star schema.

### Fact_Sales

Contains transaction-level sales information including
date, city, store format, category, item, quantity,
unit price and sales amount.

### Dim_Date

Contains date-related attributes used for time analysis.

### Dim_City

Contains city and store-format information.

### Dim_Product

Contains product and category information.

## DAX Measures

- Total Sales
- MoM Growth %
- Running Total Sales
- City Sales Rank
- Average Transaction Value

## Dashboard

The dashboard provides:
- Sales trend analysis
- Cold Brew seasonal analysis
- City-level sales comparison
- Product-level analysis
- Interactive city filtering
- Date drill-down

## Key Insights

1. Cold Brew sales show the seasonal pattern represented
   in the dataset, particularly across April and May.

2. Bengaluru shows stronger sales performance compared
   with the other cities in the dataset.

3. The dashboard allows users to explore sales performance
   by date, city, store format and product.

## Version Control

The project was developed incrementally using GitHub.
Separate commits were used for the star schema, individual
DAX measures and the completed dashboard.
