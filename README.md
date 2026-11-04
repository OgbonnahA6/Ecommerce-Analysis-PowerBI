# Ecommerce Sales, Customer & Performance Analysis

This interactive Power BI report examines ecommerce performance from **January 2022 through December 2024**. It tracks revenue, profit, order status, products, and customers. The executive dashboard shows **$979M in net revenue**, **$759M in profit**, and a **77.6% profit margin**, exceeding management’s 55% target by **22.6 percentage points**.

## Business objective

Management wanted to understand how the business performed over time and where to investigate changes in revenue or profitability. The project brief specifies two benchmarks. The previous month’s actual result serves as the reference for current-month performance where a formal target is unavailable. Profit margin has a fixed target of 55%. The report also includes year-over-year comparisons.

## Executive results

| KPI | Result shown |
| --- | ---: |
| Total revenue across order statuses | $1.26B |
| Completed revenue / total net revenue | $979M |
| Cost of goods sold | $219.2M |
| Total profit | $759M |
| Profit margin | 77.6% |
| Units | 1.86M |
| Transactions | 70,000 |
| Products | 500 |
| Registered customers | 5,022 |
| Customers with transactions | 4,994 |
| Countries represented | 176 |

Figures are displayed at dashboard precision. The Details view shows net revenue **$36.8M above its displayed reference (+3.9%)** and profit **$29.3M above its displayed reference (+4.0%)**. COGS was also **$7.5M above its displayed reference (+3.6%)**. An increase in cost should be read alongside sales volume, revenue, and margin.

## Key findings

- **Completed orders accounted for 77.5% of total revenue by status.** Pending orders represented **$146M (11.6%)**, and canceled orders represented **$139M (11.0%)**. These are separate statuses and warrant separate analysis.
- **Electronics led category profitability at $232M.** The Products view identifies **Canon EOS R6 ($118M)** as the leading product and **Sony ($132M)** as the leading brand by profitability. At the other end, **Amazon Echo Dot (-$4.6M)** and **Instant Pot Duo (-$3.0M)** were among the largest product losses shown.
- **Customers ages 15–27 generated the most revenue at $407M**, followed by ages 28–37 at **$288M**. The Customers view shows **28 registered customers without transactions (0.56%)**.
- **The United States led country revenue at about $142.9M**, accounting for **14.6%** in the Buyers Location view with no continent selected.

## Dashboard guide

| View | What to explore |
| --- | --- |
| Details | Executive KPI cards for units, net revenue, COGS, and profit, with variance and year-over-year indicators. Switch the trend metric and group it by quarter, year, month, or weekday. Compare margin against the 55% target. |
| Revenue Details | Compare completed, pending, and canceled revenue. Review cumulative net revenue against the prior year and inspect the cumulative variance. |
| Products | Compare leading and underperforming products, categories, and brands by net profit. |
| Product Details | Inspect product-level quantity, COGS, revenue, profit, margin, and transaction count in a sortable table. |
| Customers | Compare registered customers with customers who transacted, review revenue by age group, and use the adjustable Top N control to compare customer rankings across periods by quantity, COGS, revenue, or profit. |
| Buyers Location | Compare country revenue, review the revenue split by gender, and expand the continent and age-group matrix for customer count, transactions, revenue, profit, and margin. |

## Tools and implementation

- **Power Query** prepares the source data for analysis.
- **Power BI data modeling and DAX** support KPIs, benchmark variances, year-over-year comparisons, cumulative trends, and metric switching.
- **Power BI Desktop** provides sidebar navigation, an expandable filter panel, report-page tooltips, and links from summary views to supporting detail.

## Author

Augustine Ogbonnah · [Portfolio](https://ogbonnaha6.github.io/AOPortfolio.github.io/)
