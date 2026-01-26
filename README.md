# Inventory and Supply Chain Management Analysis 📦📊

This project presents a **Power BI–based analysis of inventory and supply chain performance**, focusing on operational efficiency, inventory health, and warehouse utilization through interactive dashboards.

---

## 📌 Project Objectives
- Measure inventory efficiency using key performance indicators
- Analyze warehouse utilization and capacity usage
- Track inventory movement and holding performance
- Support data-driven decision-making in supply chain operations

---

## 🛠 Tools & Technologies
- **Power BI Desktop**
- **CSV Dataset**
- **DAX Measures**
- **Interactive Visualizations**

---

## 📊 Key KPIs
- Warehouse Utilization (%)
- Days Sales of Inventory (DSI)
- Inventory Turnover Ratio
- Transportation Cost by Region and Category
- Inventory Level by Category and Region
- Lead Time by Product Category
- Backorders by Order Status
- Units Sold Trend (Year-wise)

---

## 🧮 DAX Measures Used

| S. No | Measure Name | DAX Formula |
|-----|-------------|------------|
| 1 | **Warehouse Utilization (%)** | `DIVIDE(SUM('Inventory and SupplyChain Dataset'[Inventory Level]), SUM('Inventory and SupplyChain Dataset'[Warehouse Capacity])) * 100` |
| 2 | **Days Sales of Inventory (DSI)** | `DIVIDE(SUM('Inventory and SupplyChain Dataset'[Inventory Level]), SUM('Inventory and SupplyChain Dataset'[Cost of Goods Sold])) * 365` |
| 3 | **Inventory Turnover Ratio** | `DIVIDE(SUM('Inventory and SupplyChain Dataset'[Cost of Goods Sold]), SUM('Inventory and SupplyChain Dataset'[Average Inventory]))` |

---

## 📈 Dashboard Insights
- Warehouse utilization is below optimal capacity, indicating scope for space optimization.
- Inventory turnover varies across categories, highlighting efficiency differences.
- DSI reflects inventory holding patterns and potential overstocking areas.
- Regional analysis shows uneven inventory distribution and cost impact.

---

## 📂 Dataset Overview
The dataset includes:
- Inventory levels
- Warehouse capacity
- Cost of goods sold (COGS)
- Average inventory
- Product categories
- Regions
- Order status and lead time

---

## 🚀 How to Use
1. Download the Power BI `.pbix` file
2. Open it using **Power BI Desktop**
3. Use slicers to filter by **Region** and **Category**
4. Analyze KPIs and trends through interactive visuals

---

## 🎯 Applications
- Inventory Optimization
- Supply Chain Performance Analysis
- Warehouse Capacity Planning
- Operations & Logistics Analytics
- Academic and Mini Project Reference

---

## ⭐ Support
If you find this project useful, consider giving the repository a **star ⭐**.
