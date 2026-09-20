# E-Commerce Sales Intelligence Dashboard

A Power BI internship project focused on analyzing e-commerce sales,
profitability, product performance, customers, regions, and returns.

## Project Overview

This dashboard was built in Microsoft Power BI to transform order-level
data into interactive business insights. The report contains four
analysis pages:

1.  **Executive Dashboard** --- high-level sales, profit, order,
    quantity, average order value, and profit-margin KPIs.
2.  **Product Performance Dashboard** --- product/category/sub-category
    sales and profit analysis.
3.  **Customer & Regional Analysis Dashboard** --- customer,
    salesperson, segment, state, and regional performance.
4.  **Returns & Business Insights Dashboard** --- returned orders by
    category, region, product, and month, with a written
    business-insights section.

## Tools & Technologies

-   Microsoft Power BI
-   Power Query / data transformation
-   DAX measures
-   Data visualization
-   Interactive filtering and drill-down analysis

## Report Structure

### 1. Executive Dashboard

Key KPIs: - Total Sales - Total Profit - Total Orders - Total Quantity -
Average Order Value - Profit Margin %

Visual analysis includes: - Sales trend by year/month - Profit trend by
month - Sales by region - Sales by product - Sales share by category -
Filters for region, segment, category, and order date

### 2. Product Performance Dashboard

Key KPIs: - Total Products - Total Categories - Total Sub-Categories -
Average Sales per Product

Visual analysis includes: - Sales by category - Sales by sub-category -
Profit by sub-category - Sales by product - Profit by product -
Product-level detail table

### 3. Customer & Regional Analysis Dashboard

Visual analysis includes: - Sales by customer - Sales by region - Sales
by state using a map - Sales by segment - Sales by person/sales
representative - Customer-level sales and profit table

Interactive filters: - Region - Segment - Category - Order date

### 4. Returns & Business Insights Dashboard

Visual analysis includes: - Returned orders by category - Returned
orders by region - Returned orders by product - Returned orders over
time - Interactive filters for category, region, segment, and order date

The dashboard's documented observations include: - The Consumer segment
generated the highest share of total sales. - Technology was the
highest-revenue category. - The West region recorded the highest number
of returned orders. - A small number of products contributed
disproportionately to total returns. - Monitoring return patterns can
support loss reduction and customer-experience improvements.

## Data Model

The Power BI file contains three model tables:

-   **Orders** --- primary transactional/order analysis table.
-   **People** --- person/sales-representative information used in
    customer/people analysis.
-   **Returns** --- return-related data used by the return analysis.

The report uses measures and fields from the Orders table for the main
KPIs and visualizations.

## Skills Demonstrated

-   Data cleaning and preparation
-   Exploratory data analysis
-   KPI design
-   DAX measure usage
-   Interactive dashboard development
-   Business-oriented data visualization
-   Trend and regional analysis
-   Product and customer performance analysis
-   Return-pattern analysis
-   Communicating data-driven business insights

## Repository Structure

``` text
E-Commerce-Sales-Intelligence-Dashboard/
│
├── E-Commerce-Sales-Intelligence-Dashboard.pbix
├── README.md
├── UPLOAD_GUIDE.md
│
├── docs/
│   ├── dashboard-pages.md
│   ├── data-model.md
│   └── insights.md
│
└── screenshots/
    └── README.md
```

## How to Open

1.  Install **Microsoft Power BI Desktop**.
2.  Download the `.pbix` file from this repository.
3.  Open the file in Power BI Desktop.
4.  Use the page tabs and slicers to explore the report.

> Note: GitHub cannot render a Power BI `.pbix` file as an interactive
> dashboard. Screenshots are therefore recommended for the repository's
> visual preview.

## Internship Portfolio Note

This repository presents the Power BI dashboard as an internship
portfolio project and documents the analytical work, dashboard
structure, and business insights demonstrated in the report.

## Screenshots

Dashboard screenshots can be added to the `screenshots/` folder and
embedded here later. See `screenshots/README.md` for the recommended
naming convention.

## License

No open-source license is currently specified. The repository is
intended as a portfolio/project showcase.
