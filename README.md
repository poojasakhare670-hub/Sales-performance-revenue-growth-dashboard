# Sales Performance & Revenue Growth Dashboard

An interactive **Microsoft Power BI** project for exploring sales performance, revenue, profitability, target achievement, and business trends.

## Project Overview

This dashboard brings key sales metrics and comparisons into one report. It helps users review performance across regions, product categories, sales channels, customer types, and sales executives, then investigate details using filters and a dedicated **Sales Details** page.

## Key KPIs

- **Total Revenue** — revenue generated in the selected filter context
- **Total Profit** — profit generated in the selected filter context
- **Total Units Sold** — sales volume
- **Overall Achievement %** — actual sales compared with target sales
- **Revenue Growth %** — revenue movement compared with the previous period

KPI values change with the report's selected filters, so the displayed figures depend on the current selection.

## Dashboard Features

- Revenue and profit comparisons by region
- Revenue and units sold by product category
- Monthly revenue trend
- Actual sales versus target sales by region
- Online versus offline sales-channel comparison
- New versus existing customer revenue distribution
- Revenue ranking by sales executive
- Regional summary table
- Interactive slicers for year, month, quarter, region, product category, sales channel, sales executive, and date range
- A **Sales Details** report page for transaction-level inspection

## Tools & Technologies

- Microsoft Power BI Desktop
- Power Query for data preparation
- DAX measures for KPI calculations
- Excel dataset as the source data
- GitHub for project versioning and portfolio presentation

## Repository Contents

| File | Description |
|---|---|
| `Sales Performance & Revenue Growth Dashboard.pbix` | Power BI report file |
| `Sales_Performance_Dataset.xlsx` | Source sales dataset |
| `Sales_Performance_Revenue_Growth_Dashboard.docx` | Project documentation and analysis |

## How to Explore the Project

1. Download the `.pbix` file and open it in **Power BI Desktop**.
2. If Power BI requests a data-source location, reconnect it to the included Excel dataset.
3. Use the slicers to filter the report by time period, region, category, channel, or sales executive.
4. Open the **Sales Details** page to inspect the underlying sales records.

## Business Questions This Dashboard Supports

- Which regions contribute the most revenue and profit?
- How are actual sales performing against targets?
- Which product categories contribute to revenue and unit sales?
- How do online and offline channels compare?
- How does revenue vary between new and existing customers?
- How do sales executives compare by revenue?
- How does sales performance change over time?

## Limitations & Future Improvements

The report reflects the fields and quality of the supplied dataset. Potential extensions include sales forecasting, deeper customer-level profitability analysis, automated refresh after deployment to Power BI Service, and exception alerts for under-target performance.

## Author's Project Summary

This project demonstrates practical use of Power BI for KPI reporting, interactive data visualization, sales analysis, and drill-through exploration.

---
**Project:** Sales Performance & Revenue Growth Dashboard  
**Repository:** `sales-performance-revenue-growth-dashboard`
