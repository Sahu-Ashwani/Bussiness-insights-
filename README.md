# Business Insights 360 - Power BI Dashboard

## 🚀 **Live Dashboard**
📊 [**View Interactive Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiZTI0ZWRhODQtMTdhNi00M2RiLWEzNTMtMzE5MjYzNGFiMGYxIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9&pageName=425a33c740d36a29d8c5)

## 🌟 **Project Overview**

**Business Insights 360** is a comprehensive **data analytics solution** developed for **AtliQ Hardware**, a global consumer electronics company.  
This **Power BI dashboard** delivers **actionable insights** across multiple business functions, enabling **data-driven decision-making** at all organizational levels.

### 📈 **Key Functional Areas**

┌────────────────────────────────────────┐<br>
│ 💰 Finance │ 💼 Sales │ 📢 Marketing │<br>
│ 🚚 Supply Chain │ 👔 Executive Dashboard │<br>
└────────────────────────────────────────┘<br>

---

## 🎯 **Business Problem**

AtliQ Hardware was experiencing **major operational and strategic challenges** in the Latin American market due to its heavy reliance on **Excel-based data management**. This resulted in fragmented insights, slow decisions, and missed opportunities.

### 🚨 **Critical Challenges**

| **Challenge**                 | **Impact**                                                   |
|------------------------------|--------------------------------------------------------------|
| 📉 **Limited Data Visualization** | Poor data comprehension and weak insight generation          |
| 📊 **Scalability Issues**         | Inability to handle rapidly growing data volumes             |
| ⏰ **Decision Latency**           | Difficulty in making timely, informed business decisions      |
| 💸 **Financial Losses**           | Significant losses across key markets                         |

### ✅ **Solution**

This project delivers a robust **end-to-end analytics solution** addressing the above challenges and driving long-term business growth through:

- 🔍 **Real-time data visualization**  
- 📊 **Interactive dashboards** for every department  
- 🎯 **Automated KPI tracking & performance monitoring**  
- 📈 **Predictive analytics capabilities**  
- 🌐 **Scalable, cloud-backed data infrastructure**

---

## 📁 **Dataset Information**

### **📌 Data Sources**

The project uses two primary databases:

### **🗄️ gdb041 (Core Business Data)**

- **dim_customer**   75 customers across 27 markets;   2 platforms: *Brick & Mortar, E-commerce*;   3 channels: *Retailer, Direct, Distributors*  

- **dim_market**  27 markets; 7 sub-zones; 4 regions: **APAC, EU, LATAM, NA**

- **dim_product**  14 product categories; 3 divisions: **P&A, PC, N&S**

- **fact_forecast_monthly**  Customer demand forecasts for **inventory optimization**

- **fact_sales_monthly**  Actual sales transaction data


### **🗄️ gdb056 (Financial Data)**

- **freight_cost** — Logistics & transportation cost by market  
- **gross_price** — Product pricing information  
- **manufacturing_cost** — Production costs by product & year  
- **pre_invoice_deductions** — Pre-invoice discount percentages  
- **post_invoice_deductions** — Post-invoice adjustments & deductions  

### 🧱 **Data Model**

The project implements a **Snowflake Schema**, ensuring:  
- Optimized query performance  
- High data integrity  
- Efficient handling of large datasets  

---

## 🎨 **Dashboard Views**


### 🏠 **Home Page**
**Central navigation hub** featuring:
- Quick access to **all department views**  
- **Last data refresh** timestamp  
- **Data currency** indicator *(sales data loaded till mmm/yy)*  
- **Note:** All financial values are displayed in **Millions ($)**  


### 💰 **Finance View**
**Objective:** Comprehensive financial performance analysis  

**Key Features:**  
- KPI cards for **Net Sales**, **Gross Margin %**, **Net Profit %** with **YoY comparisons**  
- Full **Profit & Loss statement**  
- **Top/Bottom customers** by Net Sales  
- **Top/Bottom products** by Net Sales  


### 📈 **Sales View**
**Objective:** Detailed customer and product sales performance  

**Key Features:**  
- Customer performance metrics: **Net Sales**, **Gross Margin**, **GM%**  
- Product performance deep-dive  
- **Performance matrix** (scatter plot) showing customer distribution by **GM% vs Net Sales**  
- Donut charts for key metrics: **Net Sales**, **Deductions**, **COGS**, **Gross Margin**  


### 🎯 **Marketing View**
**Objective:** Market penetration & profitability analysis  

**Key Features:**  
- Product performance across multiple **profitability metrics**  
- Performance breakdown by **Region → Market → Customer**  
- Dual-filter **performance matrix** (GM% or NP% vs Net Sales)  
- **Unit economics** including customer-level COGS and Gross Margin  
- **Waterfall chart** illustrating Net Profit after operational costs  

### 🚚 **Supply Chain View**
**Objective:** Forecast accuracy & inventory management  

**Key Features:**  
- KPI cards for **Forecast Accuracy**, **Net Error**, **Absolute Error**  
- Monthly trend analysis *(current vs previous year)*  
- Key supply chain metrics by product  
- **Performance benchmarking** vs last year  


### 👔 **Executive View**
**Objective:** High-level business summary for leadership  

**Key Features:**  
- Critical KPIs: **Forecast Accuracy, Net Sales, GM%, NP%**  
- Revenue distribution by **Division** and **Channel** (donut charts)  
- Key insights categorized by **sub-zone**  
- Yearly trends for **Net Sales**, **GM%**, **NP%**, **PC Market Share**  

---
## 👨‍💻 Author

**Ashwani Kumar Sahu**  
B.Tech + M.Tech (Transportation Engineering), IIT Bhubaneswar  
**Focus Areas:** Product Analytics • Data Science • Experiment Design

---


