# Global-Superstore-Sales-Dashboard
An interactive Power BI dashboard for exploring Global Superstore sales, orders, products, regional performance, shipping profitability, and returns. The report brings key business metrics and category- and region-level comparisons into one view to support faster, data-informed decisions.

## Dashboard Highlights

- **KPI cards:** Total Orders, Total Returns, and Return Percentage.
- **Sales by Category:** Compares sales across product categories.
- **Products by Category:** Shows the product portfolio across categories.
- **Orders by Region:** Highlights differences in order volume across regions.
- **Profit by Ship Mode:** Compares profit across shipping methods.
- **Interactive slicers:** Filter report visuals by Product Category and Region.

## Key Metrics

| Metric | Purpose |
|---|---|
| Total Sales | Measures overall sales value. |
| Total Orders | Counts distinct orders. |
| Total Returns | Tracks returned orders. |
| Return Percentage | Shows returns relative to orders. |
| Total Customers | Represents the customer base. |
| Total Product | Counts products represented in the analysis. |
| Total Category | Counts product categories. |
| Total Region | Counts regions represented in the analysis. |
| Profit | Compares profitability across shipping modes. |

## Dashboard Views

### Sales Performance
Sales are compared by product category to show which categories contribute most to overall sales.

### Product Portfolio
Product counts are grouped by category to make the composition of the catalogue easier to understand.

### Regional Performance
Orders are compared across regions, with the Region slicer allowing a focused view of the selected geography.

### Shipping Profitability
Profit is broken down by ship mode to compare the profitability associated with different shipping options.

### Returns Overview
The KPI cards summarise order volume, returned orders, and the return percentage, providing a quick view of return performance alongside the sales analysis.

## Data Model

The Power BI model includes the following tables:

- **Orders** — order-level details, sales, profit, quantity, customer, region, and shipping information.
- **Returns** — information used to analyse returned orders.
- **Product** — product names, categories, and sub-categories.
- **People** — regional people or manager mapping.
- **Date** — calendar attributes for date-based analysis.

## Tools & Technologies

- Microsoft Power BI Desktop
- DAX (Data Analysis Expressions)
- Power BI data modelling and interactive visualisations

## Repository Contents

- `Sales Dashboard(1).pbix` — Power BI dashboard file.
- `README.md` — Project overview and dashboard documentation.

## Project Objective

The dashboard is designed to make core sales and operational metrics easier to explore, compare, and communicate. By combining KPI cards, category and regional charts, shipping-mode profitability, and interactive slicers, it provides a concise view of business performance in a single Power BI report.
