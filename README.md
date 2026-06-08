# Adidas Regional Sales Performance Dashboard

An interactive analytics dashboard tracking Adidas sales revenue, profit margins, and distribution metrics across key Middle Eastern markets. Built to provide data-backed insights into retail performance, product categories, and consumer demographics.

## Dashboard Overview

<img width="1553" height="683" alt="AdidasSales Dashbord" src="https://github.com/user-attachments/assets/df3dfbb3-d528-4980-b737-e7ec75b52adb" />

The dashboard provides a comprehensive 360-degree view of retail operations across five regional markets (Egypt, Iraq, KSA, Lebanon, and Oman). It consolidates transactional data into actionable visual components, allowing stakeholders to filter performance by year, region, product category, store type, and gender demographics.

### Key Visualizations & Insights

* **Sales & Profitability Metrics**: Tracks performance across major categories (**Footwear**, **Apparel**, and **Accessories**). Footwear represents the dominant revenue driver, commanding 62% of both total sales and total profit.
* **Retail Channel Analysis**: Breaks down the performance of various fulfillment channels (**Online**, **Retail**, **Outlet**, and **Wholesale**). Online sales represent the largest single channel, generating over $141,000 in revenue.
* **Geographic Breakdown**: Visualizes regional market shares and absolute profit metrics. **Egypt** leads regional revenue at 30%, followed closely by **Iraq** at 28%.
* **Product Performance**: Pinpoints the top four revenue-generating products, led by the *Predator Freak* (generating $34,372 in sales and $9,218 in profit) and the *Ultraboost Light*.
* **Demographic Segmentation**: Segments units sold per product category across **Female**, **Male**, and **Other** gender classifications, highlighting a strong male-driven market for footwear.
* **Temporal Trends**: Plots historical performance over months and years (2023–2025), showing a downward contraction from a 2023 high of $113,789 in sales down to $81,409 in 2025.

---

## Interactive Filters (Slicers)

The dashboard enables dynamic cross-filtering using the following dimensions:
* **Region**: Egypt, Iraq, KSA, Lebanon, Oman
* **Category**: Accessories, Apparel, Footwear
* **Store Type**: Online, Outlet, Retail, Wholesale
* **Gender**: Female, Male, Other
* **Order Date**: Multi-year timeline slider spanning 2023, 2024, and 2025.

---

## Data Structure & Key Metrics

The underlying analysis relies on the following calculated metrics:
* `Sum of Sales`: Total gross revenue generated.
* `Sum of Profit`: Net profit achieved after deducting costs.
* `Units Sold`: Quantity of items distributed per category/demographic.
