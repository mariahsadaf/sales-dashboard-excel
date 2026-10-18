# Sales Dashboard (Excel)

> **Note:** Practice project built on a synthetic dataset.

## Problem
Which product categories, regions and months drive revenue and profit?

## Dataset
`sales_data.csv`: 1,015 raw rows (1,000 after removing duplicates) of 2025 orders with category, product, region, quantity, price, cost and discount.

## Tools
Microsoft Excel (Power-user functions, PivotTables, PivotCharts, slicers)

## What I did
1. Cleaned Region text using TRIM and PROPER
2. Removed 15 duplicate rows
3. Added calculated columns: Revenue, Cost, Profit, Month
4. Built 4 PivotTables and charts, with slicers for Region and Category

## Key findings
- Furniture has the highest revenue (about 4.22M) and profit (about 1.19M).
- Revenue is much higher in October to December.
- Top products by revenue: Office Chair and Study Table.
- West is the strongest region.

## Files
- `Sales_Dashboard.xlsx` – workbook with data, pivots and dashboard
- `sales_data.csv` – original raw data
