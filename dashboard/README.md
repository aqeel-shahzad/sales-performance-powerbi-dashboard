# AdventureWorks Power BI Dashboard

This folder contains the Power BI dashboard file for the **AdventureWorks Sales Performance Dashboard** project.

The dashboard was built using AdventureWorks sales data to demonstrate business intelligence reporting, sales analysis, customer insight, product analysis, regional performance tracking, and DAX-based scenario modelling.

## Dashboard File

```text
AdventureWorks-Report.pbix
```

Download and open the `.pbix` file in **Microsoft Power BI Desktop** to interact with the dashboard.

---

## Dashboard Pages

### 1. Dashboard Overview

![Dashboard Overview](../visuals/dashboard-overview.png)

This page gives managers a high-level view of business performance.

It shows headline KPIs such as **revenue, profit, orders, return rate, monthly revenue, monthly orders, and monthly returns**. These KPIs are important because they allow managers to quickly understand whether the business is growing, profitable, and operating efficiently.

The revenue trend helps managers see performance over time rather than relying only on a single total figure. The orders by category chart shows which product categories are driving volume, while the top products table highlights which products generate strong demand and which ones may have higher return rates.

This page helps managers answer:

* Is overall sales performance improving?
* Are profit and order volume moving in the right direction?
* Which categories are driving customer demand?
* Which products require attention because of higher return rates?

---

### 2. Customer Insights

![Customer Insights](../visuals/customer-insights.png)

This page focuses on customer value and customer behaviour.

It shows **unique customers, revenue per customer, customer groups by income level, customer groups by occupation, top customers, and customer revenue contribution**. These KPIs are useful because revenue growth is not only about selling more products. Managers also need to understand who their customers are, which customer groups are most valuable, and where customer concentration exists.

Revenue per customer helps assess customer quality and spending behaviour. Customer breakdowns by income and occupation help managers understand which groups contribute most to sales. The top customer table helps identify high-value customers who may be important for retention or targeted marketing.

This page helps managers answer:

* How large is the active customer base?
* How much revenue does the average customer generate?
* Which customer groups are most important commercially?
* Are sales concentrated among a small number of customers?
* Which customers could be prioritised for retention or growth activity?

---

### 3. Product Scenario Analysis

![Product Scenario Analysis](../visuals/product-scenario-analysis.png)

This page focuses on product-level performance and pricing decisions.

It shows a selected product, monthly orders vs target, monthly revenue vs target, monthly profit vs target, profit trends, and a **DAX what-if price adjustment feature**. This is important because managers often need to understand how individual products are performing, not just how the overall business is performing.

The target gauges show whether the selected product is meeting commercial expectations. The price adjustment control allows managers to test how a price change could affect adjusted profit. This turns the dashboard from a static reporting tool into a simple scenario-planning tool.

This page helps managers answer:

* Is the selected product meeting order, revenue, and profit targets?
* How does product performance change over time?
* What could happen to profit if the price is adjusted?
* Which products may need pricing review or commercial attention?
* How can managers compare current performance with a possible adjusted scenario?

---

### 4. Regional Performance

![Regional Performance](../visuals/regional-performance.png)

This page shows sales activity across major regions using an interactive map.

Regional reporting is important because overall sales performance can hide geographic differences. A business may look healthy overall while one region is underperforming, or a smaller region may show strong growth potential. The map helps managers quickly compare market presence and identify where commercial focus may be needed.

The region filters allow users to focus on specific markets such as Europe, North America, and Pacific. This supports more targeted decision-making because managers can review performance by geography rather than treating the business as one single market.

This page helps managers answer:

* Which regions show the strongest sales activity?
* Are there geographic markets that need more attention?
* Where is the business most active?
* How does performance differ across regions?
* Which regions could be prioritised for sales or marketing focus?

---

## Features Demonstrated

* Power BI dashboard design
* Data modelling
* Power Query data preparation
* DAX KPI measures
* DAX what-if parameter
* Sales trend analysis
* Customer analysis
* Product performance analysis
* Regional performance mapping
* Business intelligence storytelling
