# 📊 Sales & Profit Performance Dashboard (Power BI)

An executive-level **Sales & Profit Performance Dashboard** built using **Power BI**, designed to analyze revenue, profitability, customer behavior, and time-based performance across multiple business dimensions.

This project demonstrates **data modeling best practices**, **time-intelligent DAX**, and **business-focused analytics** using real-world sales data.

---

## 🔍 Project Overview

The dashboard analyzes sales data across **2019–2020** to answer key business questions:

- How is overall sales and profitability performing?
- Which product categories and customer segments drive profit?
- Who are the most important customers by order frequency?
- How do sales and profit trends behave over time?
- How does performance change month-over-month and year-to-date?

---

## 📌 Key Metrics & KPIs

- **Total Sales:** ₹1.57M+
- **Total Profit:** ₹175K+
- **Total Orders:** 3,000+
- **Total Quantity Sold:** 22K+
- **Average Order Value (AOV)**
- **Profit Margin %**
- **Sales MTD / YTD / Previous Month**
- **Sales Month-over-Month (MoM %)**

All KPIs dynamically respond to slicers and filters.

---

## 🧱 Data Modeling

The project follows a **Star Schema** data model for optimal performance and clarity.

### Tables Used
- **Fact Table**
  - `fact_sales`
- **Dimension Tables**
  - `dim_customer`
  - `dim_product`
  - `dim_ship_mode`
  - `dim_payment_mode`
  - `calendar`

### Calendar Table Highlights
- Custom calendar table with **730+ dates**
- Supports **MTD, YTD, PM, MoM** calculations
- Uses a **Year–Month Sort Key** for correct chronological ordering across years

<img width="1470" height="732" alt="image" src="https://github.com/user-attachments/assets/9617bcd7-f86d-4585-b542-b4e5be0f1c98" />

---

## 📊 Dashboard Visuals

### KPI Section
- Executive KPI cards with **conditional formatting**
- Positive/negative performance highlighted dynamically

### Analytical Visuals
- **Total Sales & Total Profit by Category**
- **Total Sales & Total Profit by Customer Segment**
- **Top Customers by Order Frequency**
- **Sales vs Profit Trend Over Time (Line Chart)**

<img width="1560" height="729" alt="image" src="https://github.com/user-attachments/assets/2b722f26-d7b4-4b33-ae61-4246310986db" />



---

## 🧮 DAX & Time Intelligence

Key DAX concepts implemented:

- Base measures for Sales, Profit, Quantity, Orders
- Time intelligence measures:
  - MTD
  - YTD
  - Previous Month
  - Month-over-Month %
- Conditional formatting logic for KPI indicators
- Chronological sorting using **Year Month Sort** column

---

## 🎛️ Interactivity & Filters

Slicers included:
- **Year**
- **Customer Segment**
- **Ship Mode**

These enable users to analyze performance from **strategic and operational perspectives** without cluttering the dashboard.

---

## 💡 Key Insights (Sample)

- Office Supplies generate the highest sales volume, while Technology delivers stronger profitability.
- Consumer segment drives revenue, whereas Corporate maintains healthier margins.
- A small group of customers contributes disproportionately to order volume.
- Sales show an upward trend, while profit exhibits higher volatility, indicating margin pressure in certain periods.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **DAX**
- **Power Query**
- **Data Modeling (Star Schema)**

---

## 🚀 How to Use

1. Download the `.pbix` file from the repository
2. Open it in **Power BI Desktop**
3. Interact with slicers to explore performance by time, segment, and shipping mode

---

## 📎 Project Status

✅ Completed  
📌 Portfolio-ready  
📈 Suitable for **Data Analyst / BI Analyst** roles

---

## 📬 Contact

If you’d like to discuss this project or provide feedback, feel free to connect with me on LinkedIn.

---

 

 
