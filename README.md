# Global Sales & Logistics Performance Dashboard

## Executive Summary
This project analyzes a comprehensive global sales dataset to uncover insights into regional profitability, operational logistics, and product performance. Using Microsoft Excel, I built an interactive data dashboard that transforms raw transaction logs into clear, actionable business insights to optimize supply chain timelines and maximize revenue.

## Core Business Questions Answered
1. **Top Profitable Country:** `[Djibouti]` achieved the highest total profit, generating `[$2,425,318]`.
2. **Total Revenue:** Across all regions, the business generated a total revenue of `[$135,348,768]`.
3. **Best Selling Item Type:** `[Cosmetics]` moved the highest volume, selling `[83,718]` units.
4. **Sales Channel Split:** 
   * **Online Orders:** `[50]` orders
   * **Offline Orders:** `[50]` orders
5. **Office Supplies Pricing:** The average unit price for items in the "Office Supplies" category is `[$651]`.
6. **Logistics Bottleneck:** Order ID `[585920464]` experienced the longest transit lag, taking `[50]` days to ship after the order date.
7. **High Priority Operational Costs:** Items designated with a High ("H") order priority incurred a total fulfillment cost of `[$31,857,946]`.
8. **Underperforming Region:** The `[North America]` region recorded the lowest total revenue at `[$5,643,357]`.
9. **Sub-Saharan Africa Volume:** A total of `[182,870]` units were successfully distributed within the Sub-Saharan Africa region.
10. **Baby Food Profitability:** The total profit generated specifically from the "Baby Food" item type amounted to `[$3,886,644]`.

## Dashboard Preview
Below is a screenshot of the interactive Excel dashboard built to visualize these key performance indicators (KPIs):

![Global Sales Dashboard](dashboard.png)

## Tech Stack & Excel Features Used
* **Data Cleaning & Engineering:** Utilized Power Query to handle missing fields, change data types, and standardise geographic regions.
* **Advanced Formulas:** Used `DATEDIF` / date subtraction to calculate shipping lags, `AVERAGEIF` for categorical pricing, and `SUMIF`/`SUMIFS` for priority metrics.
* **Aggregation:** Built multiple dynamic Pivot Tables to slice revenue and unit volumes across multi-tiered regions and sales channels.
* **UI/UX Design:** Implemented interactive slicers (Dates and Region switches), clean conditional formatting, and consistent corporate color charts for seamless stakeholder navigation.

