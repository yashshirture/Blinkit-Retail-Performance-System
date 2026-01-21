# 🛒 Blinkit Retail Performance System (Power BI)

## 📊 Dashboard Preview

![BlinkIt Dashboard](./dashboard.png)

## 🧩 Problem  
Retail sales data contained inconsistent product categories, missing values, and mismatched store records.  
Directly visualizing this data would produce misleading KPIs, broken trends, and untrustworthy performance metrics.

## 🎯 Objective  
Design a reliable Power BI model that converts messy retail data into accurate, decision-ready performance insights while preventing silent calculation errors.

## 🚨 Data Issues Identified  
- Inconsistent product and category names  
- Missing sales and quantity values  
- Duplicate store-product records  
- Date format mismatches  
- Totals drifting across tables  

## 🛠️ Approach  
1. Cleaned and standardized raw retail data  
2. Built a structured data model with proper table relationships  
3. Created validation measures to detect:  
   - Missing critical values  
   - Duplicate records  
   - KPI drift across dimensions  
4. Designed DAX measures for revenue, orders, and growth  
5. Built dashboards for store, category, and time-based performance  

## 🛡️ Validation & Control Logic  
- Relationship sanity checks (cardinality & filter direction)  
- Measure reconciliation across slicers  
- Null and duplicate flags on critical fields  
- Total-control visuals to surface silent breakage  

Any anomaly is surfaced before reporting.

## 📊 Output  
- Clean, modeled retail dataset  
- Reliable KPIs for sales, orders, and growth  
- Interactive dashboard for business review  

## 💡 Why This Matters  
Retail dashboards are trusted by default—and that’s risky.  
This system is built to:

- Assume upstream data can break  
- Prevent KPI drift  
- Surface hidden inconsistencies  
- Protect business decisions  

The goal is not beautiful visuals.  
The goal is **truthful performance metrics**.

## 🧰 Tools Used  
- **Power BI** – Data Modeling, Relationships, DAX Measures, KPI Dashboards  


