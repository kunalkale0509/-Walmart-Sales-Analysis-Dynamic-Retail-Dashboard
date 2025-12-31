# 🛒 Walmart Sales Analysis – Dynamic Retail Dashboard
Interactive Walmart retail dashboard analyzing sales, profit, orders, and regional performance using dynamic KPIs, slicers, and data modeling across multiple datasets.

---

## 📌 Project Summary**

This project presents an **interactive Walmart Retail Dashboard** built using a real-world global sales dataset. The dashboard enables business users to analyze **sales performance, profitability, order volume, and regional market trends** using dynamic filters and visuals.

The solution integrates **multiple datasets (Orders, Returns, People)** and converts raw transactional data into **actionable business insights.**

---

## 📂 Dataset Overview

**1️⃣ Orders Sheet**

**Rows:** 51,291

**Columns:** 11

**Key Fields:**
Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit, Shipping Cost, Order Priority

📌 Acts as the primary fact table for analysis.



**2️⃣ Returns Sheet**

**Rows:** 1,174

**Columns:** 3

**Key Fields:**
Returned, Order ID, Market

📌 Used to analyze return behavior by market.


**3️⃣ People Sheet**

**Rows:** 14

**Columns:** 2

**Key Fields:**
Person, Region

📌 Maps regional responsibility to business users.


---


## 🔗 Data Modeling

  - **Orders linked with Returns using Order ID**

  - **Orders linked with People using Region**

  - **Created a star-like model to enable cross-filtering and drill-downs**

  - **Ensured clean relationships for accurate KPIs**


---


## 🎯 Dashboard Objectives

- Provide **high-level KPIs** for leadership

- Enable **slice-and-dice analysis** across multiple dimensions

- Identify **top & bottom performing products**

- Analyze **regional, market, and segment performance**

- Visualize **global sales distribution**

- Understand **sales vs profit relationships**


  ---

## 📊 Key KPIs (Top Section)

- **Total Sales:** ₹1.26 Cr

- **Total Quantity Sold:** 178,312

- **Total Profit:** ₹14.67 L

- **Total Orders:** 51,290

- **Profit Margin:** 11.61%

(All KPIs update dynamically based on filters)

---


## 📈 Visualizations Used

- Category-wise Order Distribution (Pie Chart)

- Segment-wise Order Distribution (Donut Chart)

- Top 5 Sub-Categories by Order Count (Bar Chart)

- Bottom 5 Sub-Categories by Order Count (Bar Chart)

- Sales vs Profit Relationship (Scatter Plot)

- Global Sales Distribution (World Map)

- Interactive slicers for:

   - Segment

   - Category

   - Region

   - State

   - Market

   - Order Priority


---

## 🧠 Key Business Insights

- **Office Supplies** contributes the highest number of orders

- **Consumer segment** dominates overall order volume

- Certain sub-categories generate **high sales but low profit**

- Sales and profit show a **positive correlation**, with notable outliers

- Sales are heavily concentrated in **specific regions and markets**


---

## 🛠️ Tools & Technologies

- **Microsoft Excel**

   - Pivot Tables & Pivot Charts

   - Slicers for interactive filtering

   - Calculated Fields & Measures

   - Excel Charts (Bar, Pie, Donut, Scatter, Map)

- **Data Analysis Techniques**

   - Data cleaning and preparation

   - Data aggregation and summarization

   - KPI calculation (Sales, Profit, Quantity, Margin)

   - Trend and comparative analysis

- **Dashboard Design**

   - Interactive layout design

   - Business-focused KPI visualization

   - User-friendly filtering and navigation


---

## 📸 Dashboard Preview

<img width="1552" height="1001" alt="Walmart Dyanamic Dashboard" src="https://github.com/user-attachments/assets/0db16fd5-3194-45ac-bc1d-4e2ca3c6553f" />


---


## ✅ Conclusion

This dashboard demonstrates how retail sales data can be transformed into a decision-support system. By combining KPIs, interactive slicers, and rich visuals, the dashboard enables stakeholders to quickly identify performance trends and take data-driven actions.










