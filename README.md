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

### 🔹 Executive KPI Layer
- Revenue, Profit, and Margin overview  
- Growth trends using MoM indicators  
- Operational risk indicators (Stockouts, Late Deliveries)  

---

### 🔹 Sales Trend Analysis
- Monthly revenue trend  
- Previous month comparison  
- Performance momentum tracking  

---

### 🔹 Regional Performance
- Revenue by region  
- Identification of top-performing markets  

---

### 🔹 Product Performance
- Revenue by product category  
- Detection of high-dependency categories  

---

### 🔹 Logistics & Delivery Analysis
- Late deliveries by region  
- Identification of logistics bottlenecks  

---

## 🔍 Key Insights
- Revenue increased by **32.6% month-over-month**, indicating strong growth momentum  
- High stockout rates in key regions reveal **revenue leakage due to supply constraints**  
- Revenue is concentrated in a few product categories, indicating **portfolio dependency risk**  
- South and West regions show elevated late deliveries, suggesting **logistics inefficiencies**  

---

## 💡 Recommendations
- Optimize inventory allocation in high-demand regions  
- Improve supply chain processes to reduce stockouts  
- Address logistics bottlenecks in high-delay regions  
- Diversify product portfolio to reduce dependency risk  

---

## 📸 Dashboard Preview

<img width="472" height="267" alt="sales-logistics-revenue-risk-dashboard" src="https://github.com/user-attachments/assets/33a27447-3fb4-4ad4-a824-ae872c00bbf4" />

---

## 📁 Repository Structure

sales-logistics-revenue-risk-dashboard-powerbi/
├── README.md

├── powerbi/
│ └── sales-logistics-revenue-risk-dashboard.pbix

├── screenshots/
│ └── dashboard-overview.png

└── data/
└── sample-data.xlsx
