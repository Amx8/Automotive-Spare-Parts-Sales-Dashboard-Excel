# Automotive Spare Parts Sales Dashboard

## Project Overview

This project is an Excel-based sales analysis dashboard for an automotive spare parts business.  
The main goal of the project is to analyze sales performance, identify top-performing products, brands, branches, and salespersons, and provide clear business insights through an interactive dashboard and executive report.

The project follows a complete data analysis workflow starting from cleaned sales data, calculated metrics, KPI tracking, data quality validation, dashboard design, and final business recommendations.

## Business Problem

Automotive spare parts businesses need to understand which products, brands, and branches generate the highest revenue, how sales performance changes over time, and whether the sales data is reliable enough for decision-making.

This dashboard helps answer key business questions such as:

- Which brand generates the highest revenue?
- Which branch performs best?
- What are the top-selling products?
- Who are the top-performing salespersons?
- What is the total revenue, order count, and quantity sold?
- Are there any data quality issues that need review?

## Dataset

The dataset contains sales transactions for automotive spare parts, including invoice details, product names, brands, countries, salespersons, branches, customers, quantities, prices, discounts, and net sales values.

Key fields include:

- Invoice Number
- Date
- Product
- Brand
- Country
- Salesperson
- Branch
- Customer
- Quantity
- Price
- Total Sales
- Discount
- Net Sales

## Data Preparation

Several calculated fields were created to improve the analysis and validate the data:

- `calc_total` = Quantity × Price
- `corrected_net_sales` = Total Sales - Discount
- `discount_pct` = Discount / Total Sales
- `year`
- `month`
- `quarter`
- `quality_flag`
- `net_variance`

The `quality_flag` column was used to identify records that need review by comparing the original values with the calculated values.

## Dashboard Features

The dashboard includes:

- KPI cards for total net sales, gross sales, orders, quantity sold, discount rate, and review records
- Sales trend analysis over time
- Sales by brand
- Sales by branch
- Sales by product
- Salesperson performance analysis
- Customer analysis
- Data quality status using a donut chart
- Interactive filters for better exploration

## Key Metrics

- Total Net Sales: 5.86M
- Gross Sales: 6.35M
- Total Discount: 489K
- Discount Rate: 7.71%
- Total Orders: 5,000
- Units Sold: 27,572
- Records Needing Review: 2

## Key Insights

- Audi was the top-performing brand by revenue.
- Luxur branch generated the highest sales.
- Front Fog was the highest-performing product.
- Most records were valid, with only 2 records requiring review.
- Sales performance can be improved by monitoring top products, branch performance, and discount impact.

## Tools Used

- Microsoft Excel
- Pivot Tables
- Pivot Charts
- Excel Formulas
- Data Cleaning
- Data Validation
- KPI Analysis
- Dashboard Design
- Executive Reporting

## Project Files

```text
Automotive-Spare-Parts-Sales-Dashboard-Excel/
│
├── Spare-Parts-Sales-Dashboard-Excel.xlsx
├── Excel Dashboard.png
├── Report.png
└── README.md
