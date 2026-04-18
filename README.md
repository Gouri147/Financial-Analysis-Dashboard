# Financial Analysis Dashboard (Power BI)

##  Overview

This project showcases an interactive **Financial Dashboard** built in Power BI to monitor key financial KPIs, profitability, cash flow, and operational efficiency. The dashboard enables dynamic filtering across time, region, and product/service, helping stakeholders make data-driven decisions.

---

##  Objective

To design a monthly-level dashboard that provides insights into:

* Financial performance (Revenue & Profitability)
* Budget vs Actual comparison
* Cash flow movement
* Product and regional performance
* Receivables aging and liquidity risk

---

##  Dataset

The dataset includes the following fields:

* Month, Region, Product/Service
* Revenue, COGS, Gross Profit, Opex, EBITDA
* Cash Inflows, Cash Outflows
* Receivables Aging (Days)
* Revenue Budget

---

##  Tools & Technologies

* **Power BI Desktop** – Dashboard development
* **Power Query** – Data transformation & cleaning
* **DAX** – KPI and measure creation

---

##  Dashboard Visuals

The dashboard consists of 8 key visuals grouped by business function:

###  Financial Performance

* 📈 **Revenue & Profit Trend** – Tracks Revenue and EBITDA over time
* 📊 **Budget vs Actual** – Compares actual revenue against targets

###  Profitability Analysis

*  **Region-wise Profitability** – EBITDA % comparison across regions
*  **Profitability by Product** – Margin contribution by product/service

###  Operational Insights

*  **Product/Service Performance** – Revenue contribution by product/service
*  **Receivables Aging** – Distribution of receivables across aging buckets

###  Cash Flow Analysis

*  **Cash Flow Waterfall** – Visualizes inflows, outflows, and net cash

###  Geographic Analysis

*  **Region Map** – Geographic distribution of business activity

---

##  Key Features

* KPI Cards:

  * Total Revenue (~2M)
  * Gross Margin % (~46%)
  * EBITDA % (~26%)
  * Net Cash (~39K)

* Interactive Filters:

  * Quarter
  * Region
  * Product/Service
  * Date range

* Drill-down capability and cross-filtering across visuals

---

##  Key Insights

* The business generated **~2M in revenue**, with an **EBITDA margin of ~26%**, indicating moderate profitability.
* **North region** leads in profitability, while South shows relatively lower margins.
* **Product C and Service X** are strong contributors to both revenue and profitability.
* Budget vs Actual comparison highlights **underperformance in certain periods**, indicating gaps in planning or execution.
* Cash flow remains positive (~39K), but variations suggest the need for improved cash management.
* A large portion of receivables falls in the **31–60 days bucket**, signaling delayed collections and potential liquidity concerns.

---

##  Data Modeling & Calculations

* Created a **Date Table** for time-based filtering (Year, Quarter, Month)
* Recalculated key metrics:

  * Gross Profit = Revenue – COGS
  * EBITDA = Gross Profit – Opex
* Key Measures:

  * Total Revenue
  * Gross Margin %
  * EBITDA %
  * Net Cash Flow
  * Budget Variance %
* Created **Receivables Aging Buckets** for analysis


---

##  How to Use

1. Open the `.pbix` file in Power BI Desktop
2. Use slicers (Quarter, Region, Product, Date)
3. Interact with visuals for deeper insights
4. Hover for additional details

---

##  Assumptions

* Missing values treated as zero
* Financial metrics recalculated for accuracy
* Aging buckets created using standard ranges
* Dataset assumed to be complete and accurate

---

##  Conclusion

This dashboard provides a consolidated view of financial performance, helping stakeholders monitor profitability, track cash flow, and identify operational inefficiencies. It supports informed decision-making and highlights key areas for improvement.

---

## 👤 Author

**Gouri Sharma**
Aspiring Data Analyst

* 🔗 LinkedIn: *https://www.linkedin.com/in/gouri-sharma-702117293/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3B4A3O3Ds%2BQxuHX8e2nwbAag%3D%3D*
* 📧 Email: *34shgouri@gmail.com*
* 💻 GitHub: *Gouri147*
