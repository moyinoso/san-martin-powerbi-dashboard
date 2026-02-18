# 📊 San Martín Store Sales Analytics Dashboard (Power BI)

## 📌 Project Overview

This project is a multi-page Power BI dashboard built to analyze sales performance for San Martín Store.

The objective was to transform raw transactional data into actionable business insights by answering:

- What drives revenue and profit?
- Which products and categories perform best?
- Which stores and sales agents generate the most value?
- How does performance vary across regions and time?

The dashboard is designed for decision-makers to quickly identify trends, inefficiencies, and growth opportunities.

---

## 🛠 Tools Used

- Power BI Desktop  
- DAX  
- Excel (data cleaning)  

---

## 📂 Data Model

The project uses a **star schema**:

### Fact Table
- Sales Transactions (Order ID, Date, Product, Store, Quantity, Sales, Profit)

### Dimension Tables
- Date  
- Product  
- Category  
- Store  
- Region  
- Sales Agent  

This structure improves performance, enables accurate filtering, and simplifies DAX calculations.

---

## 📈 Key Measures (DAX)

Core KPIs include:

- Total Sales  
- Total Profit  
- Total Orders  
- Total Quantity  
- Profit Margin  
- Average Order Value (AOV)  

All visuals are driven by dynamic DAX measures and respond to slicers.

---

## 📑 Dashboard Pages

### 1️⃣ Executive Overview
- Total Sales, Profit, Orders, Quantity, Margin, AOV
- Daily Sales vs Profit trend
- Sales by Product Category
- Profit by Region

Key Insight:
Revenue leaders are not always profit leaders.

---

### 2️⃣ Sales & Product Performance
- Sales and Profit by Category
- Top 10 Products by Sales
- Bottom 10 Products by Sales

Ranking logic was used to identify best and worst performers, helping detect dead stock and pricing issues.

---

### 3️⃣ Stores & Sales Agents
- Top Stores by Sales
- Stores by Profit Margin
- Profit by Sales Agent
- Geographic distribution of sales

This page highlights operational efficiency and performance gaps across locations and agents.

---

## 🎯 Key Business Insights

- Overall profit margin is approximately 28%
- Profit is concentrated in specific regions
- Category sales leaders differ from profit leaders
- Store-level margin differences reveal pricing and cost issues
- Agent performance is measurable and actionable

---

## 🔧 Future Improvements

- Drill-through pages (Region → Store → Product)
- Decomposition Tree for profit drivers
- Sales forecasting
- Data quality checks
- Customer segmentation

---

## 📸 Dashboard Preview

Screenshots of the dashboard are included in the repository.

---

## 👤 Author

Built by Oso Moyinoluwa Oluwatosin

Aspiring Data Analyst focused on turning data into business decisions.

---

## 📬 Contact

Feel free to connect with me on LinkedIn 
🔗 LinkedIn: https://www.linkedin.com/in/m-oso 
