# 📊 Sales, Logistics & Revenue Risk Dashboard (Power BI)

## 🚀 Overview
This project delivers an end-to-end Business Intelligence solution using Power BI to analyze **sales performance, operational efficiency, and revenue risk drivers**.  

The dashboard integrates sales, inventory, and logistics data to provide actionable insights for decision-makers and highlight opportunities to improve revenue and operational performance.

---

## 🎯 Business Problem
Organizations often lack a unified view of:
- Revenue performance  
- Inventory inefficiencies (stockouts)  
- Delivery performance issues  

This results in:
- Lost sales opportunities  
- Inefficient inventory allocation  
- Poor operational decision-making  

---

## 🧱 Data Model
A **star schema data model** was implemented to ensure scalability and performance.

- **Fact Table:** `Sales`  
- **Dimension Tables:**  
  - `Product`  
  - `Customer`  
  - `Warehouse`  
  - `Calendar`  

### 🔧 Key Design Considerations
- One-to-many relationships between fact and dimensions  
- Centralized date table for time intelligence  
- Optimized aggregation for KPI calculations  

---

## ⚙️ Technical Implementation
- Built using **Power BI Desktop** with Power Query for data transformation  
- Developed **DAX measures** for KPI calculations:
  - Revenue, Profit, Margin  
  - Stockout Rate & Lost Sales  
  - Late Delivery Rate  
  - Custom **Month-over-Month (MoM) Growth** logic  
- Implemented **time intelligence functions** (e.g., `PREVIOUSMONTH`)  
- Applied **conditional formatting** and KPI indicators (▲ ▼) for trend visibility  
- Designed interactive filtering using slicers (Month, Region, Category)  

---

## 📊 Key Metrics
- Total Revenue  
- Total Profit  
- Gross Margin %  
- Stockout Rate  
- Lost Sales  
- Month-over-Month (MoM) Growth %  
- Late Delivery Rate  

---


## 📈 Dashboard Features

### 🔹 Executive KPIs
Quick snapshot of business performance:
- Revenue, Profit, Margin
- Growth trends (MoM ▲)
- Operational risks (Stockouts, Late Deliveries)

---

### 🔹 Sales Trend Analysis
- Monthly revenue trend
- Previous month comparison
- Growth momentum tracking

---

### 🔹 Regional Performance
- Revenue contribution by region
- Identification of top-performing markets

---

### 🔹 Product Performance
- Revenue by product category
- Identification of high-dependency categories

---

### 🔹 Logistics & Delivery Analysis
- Late deliveries by region
- Operational bottleneck identification

---

## 🔍 Key Insights

- Revenue increased by **32.6% month-over-month**, indicating strong growth momentum  
- High stockout rates in key regions reveal **revenue leakage due to supply constraints**  
- Revenue is heavily concentrated in a few categories, indicating **portfolio dependency risk**  
- South and West regions show elevated late deliveries, suggesting **logistics inefficiencies**

---

## 💡 Recommendations

- Improve inventory allocation in high-demand regions  
- Optimize supply chain processes to reduce stockouts  
- Address logistics bottlenecks in high-delay regions  
- Diversify product portfolio to reduce dependency risk  

---

## 🛠️ Tools Used
- Power BI  
- DAX  
- Power Query  
- Excel  

---

## 📸 Dashboard

<img width="470" height="266" alt="PBI Dashboard" src="https://github.com/user-attachments/assets/18a054f2-8f48-4bdd-800e-26cac262b0ca" />


---

## 📚 Key Learnings
- Importance of data modeling (star schema)
- Handling time intelligence with limited data (MoM analysis)
- Translating data into actionable business insights
- Designing executive-level dashboards

---

## 🔗 Author
**Richard A Oketade**  
Data Analyst | BI | Marketing & Operations Analytics
