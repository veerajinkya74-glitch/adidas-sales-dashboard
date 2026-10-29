# Adidas US Sales Performance Dashboard

## 📊 Project Overview

The **Adidas US Sales Performance Dashboard** is a Power BI data analytics project that explores Adidas sales performance across the United States. It helps users understand sales trends, profitability, product performance, and regional sales patterns through interactive visualizations.

The goal of this project is to transform raw sales data into meaningful business insights that can support better decision-making.

## 🎯 Project Objectives

- Analyze total sales and operating profit.
- Track units sold and average selling price.
- Understand monthly sales trends.
- Compare sales performance across products and regions.
- Identify business opportunities and provide data-driven recommendations.

## 🛠️ Tools & Technologies

- **Microsoft Power BI** — Dashboard development and visualization
- **Power Query** — Data cleaning and transformation
- **DAX** — Measures and KPI calculations
- **Adidas US Sales Dataset** — Sales data analysis

## 📈 Dashboard Pages

### 1. Executive Overview
Provides a high-level summary of business performance using KPI cards, monthly sales trends, product comparisons, and regional sales analysis.

### 2. Sales Analysis
Provides a detailed view of sales performance to help explore patterns and compare business results.

### 3. Insights & Recommendations
Highlights key business findings, including top-performing products, regional performance, peak sales periods, and inventory recommendations.

## 📌 Key Performance Indicators (KPIs)

- **Total Sales Amount**
- **Total Profit Amount**
- **Total Units Sold**
- **Average Selling Price**
- **Operating Margin %**

## 🧮 DAX Measures

Examples of measures used in this project:

```DAX
Total Sales Amount =
SUM('Adidas_Sales'[Total Sales])

Total Profit Amount =
SUM('Adidas_Sales'[Operating Profit])

Total Units Sold =
SUM('Adidas_Sales'[Units Sold])

Average Selling Price =
AVERAGE('Adidas_Sales'[Price per Unit])

Operating Margin % =
DIVIDE(
    [Total Profit Amount],
    [Total Sales Amount],
    0
)

Total Transactions =
COUNTROWS('Adidas_Sales')
```

## 💡 Business Insights

The dashboard is designed to help identify:

- Products contributing strongly to sales.
- Regions with strong sales performance.
- Seasonal patterns in monthly sales.
- Opportunities to improve inventory planning.
- Relationships between sales, profit, and operating margin.

*Specific findings should be validated against the dataset and dashboard visuals.*

## 📂 Repository Contents

- `README.md` — Project documentation
- Power BI report file (`.pbix`), if included
- Dataset or a link to the dataset, if permitted
- Dashboard screenshots, if included

## 🚀 How to Use

1. Clone or download this repository.
2. Open the Power BI report (`.pbix`) in Microsoft Power BI Desktop, if the report file is included.
3. Refresh the dataset if required and available.
4. Explore the dashboard pages and interactive visuals.

## 🎓 Skills Demonstrated

- Data cleaning and transformation
- Data modeling and DAX calculations
- KPI development
- Data visualization and dashboard design
- Exploratory data analysis
- Business insights and recommendations

## 👨‍💻 Author

**Ajinkya Deepak Veer**

MCA Student | Data Science & Analytics

This project demonstrates practical skills in data analytics, Power BI, and business intelligence.

---

⭐ If you find this project useful, feel free to explore the repository and share feedback.
