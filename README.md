# Adventureworks-bike-shop

### Adventureworks-bike-shop-Analysis

## TABLE OF CONTENT
- [Project Overview](#project-overview)
- [Aim of Analysis](#aim-of-analysis)
- [Tools](#tools)
- [Data Preparation](#data-preparation)
- [Insights and Findings](#insights-and-findings)
- [Recommendations](#recommendations)    
- [Conclusion](#conclusion)
- [Data Source](#data-source)

### Project Overview 

This project presents a full sales analytics solution for **AdventureWorks Bike Shop**.
The analysis covers:
* total revenue performance (2020 – 2022)
* product category performance
* customer behaviour patterns
* profitability + return rate monitoring
* deep dive (per top customers + per product)
  
### Aim of Analysis 

* To understand which products & customer segments drive revenue.
* To quantify return behaviour and its impact.
* To identify opportunities for margin uplift via price adjustment / product focus.
* To help management decide which category to scale or reduce.

### Tools
* Power BI : Report visualisation & analytics 
* Power Query : ETL, transformations             
* DAX : Measures & business logic        
* Model View : Relationship modelling          

### Data Preparation 
* Data Quality check - No missing values, no duplicates          
* Data Types - Formatted in Power Query                  
* Standardisation - Column names normalised                  
* Enrichment - Calculated columns & DAX measures created

### Insights and Findings
  ## Exec Dashboard 
  🧭Key Metrics 
  
* **Revenue** : $24.9M
* **Profit** : $10.5M
* **Revenue Per Customers** : $1.4K
* **Orders** : 25.2K
* **Unique Customers** :17.4K
* **Return rate** : 2.2%

**Category Observations**

* **Accessories**: most ordered (17.0k orders)
* **Bikes**: 13.9k
* **Clothing**: lowest (7.0k)
* **Most Ordered Product Type** → Tires & Tubes
* **Most Returned Product Type** → Shorts
  
<img width="1440" height="826" alt="Screenshot 2025-11-09 193205" src="https://github.com/user-attachments/assets/13c56e66-2a6f-4fb1-b075-e1c0855f8626" />

  ## 🧭Customer Dashboard
* Professionals order the most (**7.9K orders**)
* Skilled follows (**6.0K orders**)
* Management lowest (**4.4K orders**)

**Top Customer by Revenue**:

* **Mr Maurice Shan**
* Orders: 6
* Revenue: **$12.4K**
  <img width="1463" height="848" alt="Screenshot 2025-11-09 193922" src="https://github.com/user-attachments/assets/14b960ca-6c78-49d1-9bbd-1163e5f56011" />

  
  ## 🧭Product Dashboard

* Monthly profit trend shows consistent improvement from mid-2021 → 2022
* Price Adjustment parameter supports sensitivity testing
* Returns tab shows spikes mainly in Q1 2022

  <img width="1447" height="845" alt="Screenshot 2025-11-09 193733" src="https://github.com/user-attachments/assets/7e319179-967b-48bc-80d6-f34b28cd981d" />



### Recommendations 

1. Prioritize **Tires & Tubes** category (top driver of orders).
2. Review **Shorts** product line → reduce returns → investigate quality, sizing, or customer expectation gap.
3. Target **Professional occupation** segment more aggressively (highest spenders) through upsell bundles.
4. Use price sensitivity slider to test margin lift opportunities at category level before full rollout.

---

### Conclusion 

AdventureWorks’s revenue performance is improving, but margin improvements still exist: especially within high-return product segments.
Professionals + Tires/Tubes combinations represent the strongest ROI path moving forward.

---

### Data Source

Microsoft sample: **AdventureWorks Dataset** (2020–2022)

