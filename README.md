# 📊 Superstore Sales Dashboard

An interactive **Power BI dashboard** designed to analyze Superstore sales performance, profitability, products, customers, and regional trends.

## 🎯 Project Objective

The objective of this project is to transform Superstore sales data into meaningful business insights using Power BI.

The dashboard helps analyze:

- Overall sales and profit performance
- Monthly sales trends
- Category and regional performance
- Profitable and loss-making products
- Impact of discounts on profit
- Customer and segment performance

## 🛠️ Tools & Technologies

- Power BI
- Power Query
- DAX
- Data Visualization
- CSV Dataset

## 📌 Key KPIs

| KPI | Value |
|---|---:|
| Total Sales | 2.30M |
| Total Profit | 286.40K |
| Total Orders | 5K |
| Profit Margin | 12.47% |

---

# 📈 Dashboard Pages

## 1. Executive Overview

Provides a high-level overview of business performance including sales, profit, orders, profit margin, monthly sales trends, category performance, and regional sales.

![Executive Overview](screenshots/Executive%20Overview.png)

### Key Insights

- Technology generated the highest sales among the three categories.
- Technology also generated the highest overall profit.
- The West region recorded the highest sales.
- Monthly sales show noticeable fluctuations with stronger sales periods toward the end of the dataset.

---

## 2. Product Analysis

Analyzes product and sub-category profitability and investigates the relationship between discount and profit.

![Product Analysis](screenshots/Product%20Analysis.png)

### Key Insights

- Copiers generated the highest profit among the displayed sub-categories.
- The Canon imageCLASS product was the most profitable product in the Top 10 analysis.
- Some Cubify CubeX 3D Printer products were among the largest loss-making products.
- Higher discount levels are generally associated with weaker profitability.

---

## 3. Customer Analysis

Analyzes customer sales, profitability, customer segments, and the relationship between customer sales and profit.

![Customer Analysis](screenshots/Customer%20Analysis.png)

### Key Insights

- Consumer is the largest segment by total sales.
- Home Office has the highest profit margin at 14.03%.
- Sean Miller is the highest-selling customer in the Top 10 customer analysis.
- Tamara Chand generated the highest customer profit.
- The Sales vs Profit scatter plot shows a generally positive relationship between sales and profit, with some loss-making outliers.

---

## ✨ Dashboard Features

- Interactive page navigation
- Year slicer for customer analysis
- KPI cards
- Top 10 analysis
- Sales trend analysis
- Profitability analysis
- Discount vs Profit analysis
- Customer Sales vs Profit analysis
- Interactive Power BI filtering

## 📁 Repository Structure

```text
Superstore-Sales-Dashboard/
│
├── README.md
├── Superstore.csv
├── Superstore_Sales_Dashboard.pbix
│
└── screenshots/
    ├── Executive Overview.png
    ├── Product Analysis.png
    ├── Customer Analysis.png
    └── README.md
