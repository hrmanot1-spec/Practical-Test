# Retail Sales Performance Dashboard

## Project Overview

This project is an Excel-based sales analysis dashboard created to
summarize retail performance and present key business metrics visually.
It includes sample retail transaction data, formula-driven analysis, and
charts.

## Objectives

-   Summarize total revenue, total profit, number of orders, units sold,
    and profit margin.
-   Compare revenue across product categories and regions.
-   Review monthly revenue trends.
-   Provide a simple category dropdown to view revenue for a selected
    category.

## Workbook Structure

The Excel workbook contains these worksheets:

1.  **Dashboard** --- KPI cards, a category dropdown, and visual charts.
2.  **Raw Data** --- 300 illustrative retail transactions.
3.  **Analysis** --- Formula-driven monthly, category, regional, and KPI
    summaries.

> If you deleted the optional **Project Guide** worksheet, the workbook
> will contain these three sheets.

## Dashboard Visualizations

-   **Column chart:** Revenue by product category.
-   **Line chart:** Monthly revenue trend.
-   **Pie chart:** Revenue share by region.

## Key Performance Indicators

-   Total Revenue
-   Total Profit
-   Total Orders
-   Units Sold
-   Profit Margin

## Excel Formulas Used

The workbook demonstrates the following formulas: - `SUM` --- calculates
totals. - `SUMIF` --- summarizes revenue by category or region. -
`SUMIFS` --- calculates monthly revenue and profit using date
criteria. - `COUNTA` --- counts order IDs. - `IFERROR` --- handles
calculation errors in the profit-margin calculation. - `EDATE` ---
identifies the end of each month for monthly summaries.

## How to Use

1.  Open `Harsh_ExcelDashboard.xlsx` in Microsoft Excel.
2.  Start on the **Dashboard** worksheet.
3.  Use the category dropdown in cell **C9** to select a category or
    **All Categories**.
4.  Review the KPI cards and charts.
5.  Open **Raw Data** to inspect the transaction-level data.
6.  Open **Analysis** to view the calculations and formulas.

## Dataset Note

The included 300-row retail dataset is simulated sample data for
demonstrating Excel dashboard features. It is **not** an original Kaggle
or UCI download. If the assignment requires a dataset sourced from
Kaggle or the UCI Machine Learning Repository, replace the sample data
with an approved dataset and update the formulas and chart ranges as
needed.

One possible source is the [UCI Online Retail
dataset](https://archive.ics.uci.edu/dataset/352/online+retail).

## Suggested File Name

`Harsh_ExcelDashboard.xlsx`

## Tools

-   Microsoft Excel
-   Excel formulas
-   Excel charts and data validation
