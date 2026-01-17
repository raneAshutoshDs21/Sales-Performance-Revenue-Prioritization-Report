# 📊 Sales Performance & Revenue Prioritization Dashboard (Power BI)

## 📌 Project Overview
This project presents an **end-to-end Power BI sales analytics dashboard** designed to analyze retail sales performance and identify **high-impact revenue drivers** using **time intelligence, Top-N analysis, and Pareto (80/20) principles**.

The dashboard focuses on **decision-making**, not just reporting, by answering:
- How are sales performing over time?
- Which sub-categories contribute the most to revenue?
- Where should the business prioritize its efforts?

---

## 🗂️ Dataset
- **Records:** ~5,900 sales transactions  
- **Domain:** Retail / Sales  
- **Key Fields:**  
  - Order Date  
  - Sales  
  - Profit  
  - Quantity  
  - Region  
  - Category / Sub-Category  

> Note: The dataset represents approximately **1.5M in total revenue**.

---

## 🧱 Data Model
- Implemented a **star schema**
- Created a **custom Calendar (Date) table**
- Established a **one-to-many relationship**:

This enabled accurate **time-based analysis** such as YoY, YTD, and rolling metrics.

---

## 🧮 Key DAX Concepts Used
- Explicit measures (no implicit aggregations)
- Time Intelligence:
- Year-over-Year (YoY)
- Year-to-Date (YTD)
- Rolling 6 Months
- Ranking & Filtering:
- `RANKX`
- Dynamic Top-N logic
- Contribution & Prioritization:
- Sales Contribution %
- Cumulative Contribution %
- Pareto (80/20) Analysis
- Context management using:
- `CALCULATE`
- `FILTER`
- `ALL`
- Variables (`VAR`)

---

## 📈 Dashboard Features

### 🔹 Executive KPIs
- Total Sales  
- Total Profit  
- YoY Growth % (with conditional formatting)  
- Sales YTD  
- Rolling 6-Month Sales  

### 🔹 Sales Trend Analysis
- Monthly Sales vs Previous Year comparison
- Interactive slicers for:
- Year
- Region

### 🔹 Top-N Analysis
- Dynamic **Top 5 Sub-Categories by Sales**
- Automatically recalculates based on slicers

### 🔹 Contribution Analysis
- Donut chart showing **sales contribution %** of top sub-categories

### 🔹 Pareto (80/20) Analysis
- Combo chart (Bar + Line) visualizing:
- Total Sales by Sub-Category
- Cumulative Contribution %
- Highlights how a small number of sub-categories drive the majority of revenue

---

## 🎯 Key Insights
- A limited number of sub-categories contribute **~70–80% of total revenue**
- Sales growth trends vary significantly by **region and time period**
- Pareto analysis helps identify **high-priority product segments** for strategic focus

---

## 🛠️ Tools & Technologies
- **Power BI**
- **DAX**
- Data Modeling (Star Schema)
- Time Intelligence Functions

---

## 📌 Why This Project Matters
Unlike basic dashboards, this project emphasizes:
- Explicit DAX over drag-and-drop logic
- Business prioritization over raw metrics
- Scalable, reusable analytical patterns

It reflects **real-world BI practices** used in data analyst roles.

---

## 🚀 Future Enhancements
- Add customer-level segmentation (VIP / High Value)
- Extend analysis to profitability-based Pareto
- Create a drill-through page for sub-category deep dives

---

## 👤 Author
**Ash**  
Aspiring Data Analyst | Power BI | SQL | Analytics  

> Feel free to explore, fork, or provide feedback.

