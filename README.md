# Zipto Dark Store Performance Dashboard (Noida Cluster)

## 📌 Overview
This repository contains the **Zipto_Dark_Store_Dashboard.xlsx**, a performance dashboard designed to analyze the operational efficiency and profitability of Zipto’s dark stores in the Noida cluster.  
The dashboard provides insights into **store economics, delivery performance, and unit economics**.

---

## 🚀 Key Features
- **Filters**: Store, Vehicle Type, Employment Type  
- **KPIs**:
  - Total Orders: 7,794  
  - Delivered Orders: 7,357  
  - Failed / Returned: 284 (3.6%)  
  - On-Time %: 44.4% (Target: 65% within 10 min)  
  - Avg Delivery Time: 11.2 min  
  - Avg Delivery Cost per Order: ₹30.5  
  - Avg Distance: 3.01 km  
  - Total Contribution: ₹519,310  
  - Store P&L: ₹519,310  

---

## 📊 Dashboard Sections

### 1. Store Economics & Delivery Performance
- **Store P&L by Store (₹)** – Profitability comparison across stores  
- **On-Time % by Store** – Benchmark vs actual performance  
- **Avg Delivery Time by Store (min)** – Delivery speed analysis  

### 2. Delivery Cost, Fulfilment Status & Unit Economics
- **Avg Delivery Cost by Store** – Cost efficiency comparison  
- **Trip Status Distribution (orders)** – Delivered, Returned, Cancelled breakdown  
- **Contribution vs Delivery Cost by Store (₹)** – Profitability vs cost trade-off  

---

## 📈 Business Definition
Contribution is calculated as:  
- **Delivered Order** → Net Amount − COGS − Delivery Cost  
- **Returned Order** → − (COGS + Delivery Cost)  
- **Cancelled Order** → 0  

Store P&L = Σ(Contribution) − (Monthly Rent × Months in Data)

---

## 🎯 Usage
- Open `Zipto_Dark_Store_Dashboard.xlsx` in Excel or Power BI.  
- Use filters to drill down by store, vehicle type, or employment type.  
- Review KPIs and charts to identify top-performing and underperforming stores.  
- Apply insights to optimize delivery operations and improve profitability.

---

## 🏆 Insights
- Identify **top 2 stores to fix** based on contribution and P&L.  
- Pinpoint **root causes** (delivery delays, high costs, product returns).  
- Quantify **₹ impact per month** for corrective actions.  
- Provide actionable recommendations for the COO.

---

## 👥 Contributors
- [Monika](https://github.com/mengawademonika-hash)  
- [Rohilt](https://github.com/thiro2003)  
- [Triveni](https://github.com/trivenichavhan731-cmd)  

---

## 📂 Files
- `Zipto_Dark_Store_Dashboard.xlsx` – Main dashboard file  
- Supporting datasets (CSV/Excel) for store performance, delivery logs, and product data  

---

## 📜 License
This project is for **educational and analytical purposes**.  
Not intended for commercial redistribution.
