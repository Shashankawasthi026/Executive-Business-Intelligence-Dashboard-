# Executive-Business-Intelligence-Dashboard-
Power BI Business Intelligence Dashboard with Data Modeling, DAX Measures, KPI Tracking, Time Intelligence Analysis, and Executive Reporting using the Global Superstore Dataset.

## 📌 Project Overview

This project focuses on Data Modeling, DAX Calculations, and Executive-Level Business Intelligence Reporting using Microsoft Power BI. The dashboard was developed using the Global Superstore Dataset to transform raw sales data into meaningful business insights and support data-driven decision-making.

The project demonstrates the complete BI workflow, including data preparation, relationship modeling, KPI creation, dashboard design, and business insight generation.

---

## 🎯 Objectives

- Perform data modeling using fact and dimension tables.
- Create DAX measures for KPI tracking and performance analysis.
- Build an interactive executive-level dashboard.
- Analyze sales, profit, customer segments, and product categories.
- Generate actionable business insights for strategic decision-making.

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Business Intelligence
- Data Visualization

---

## 📂 Dataset

**Global Superstore Dataset**

The dataset contains:
- Order Information
- Customer Details
- Product Information
- Sales & Profit Data
- Regional Performance
- Customer Segmentation

---

## 🏗️ Data Model

### Fact Table
- Orders

### Dimension Tables
- Customers
- Calendar

### Relationships
- Customer ID → Orders
- Date → Orders

---

## 📈 Key Performance Indicators (KPIs)

| KPI | Value |
|------|--------|
| Total Sales | $3M+ |
| Total Orders | 5K+ |
| Total Profit | $311K+ |
| Profit Margin | 11% |

---

## 📊 Dashboard Features

### Executive KPI Cards
- Total Sales
- Total Profit
- Total Orders
- Profit Margin

### Interactive Visualizations
- Sales by Region
- Profit by Category
- Sales by Segment
- Category Analysis

### Filters & Slicers
- Region
- Category
- Segment

---

## 🧮 DAX Measures

```DAX
Total Sales =
SUM(Orders[Sales])

Total Profit =
SUM(Orders[Profit])

Total Orders =
DISTINCTCOUNT(Orders[Order ID])

Profit Margin =
DIVIDE([Total Profit],[Total Sales])

Category Contribution % =
DIVIDE(
    [Total Sales],
    CALCULATE(
        [Total Sales],
        ALL(Orders[Category])
    )
)
```

---

## 🔍 Business Insights

### Revenue Performance
The organization generated over **$3 million in sales**, demonstrating strong market demand and customer engagement.

### Profitability Analysis
The business achieved approximately **$311K in profit** with an overall **11% profit margin**.

### Customer Segment Analysis
The **Consumer Segment** contributed the highest share of total sales and remains the most valuable customer segment.

### Product Category Performance
The **Technology Category** emerged as the strongest-performing category in terms of revenue and profitability.

### Strategic Recommendations
- Expand high-performing technology products.
- Improve customer retention strategies.
- Focus on profitable market segments.
- Strengthen sales performance in key regions.
- Optimize business operations to improve profit margins.

---

## 📷 Dashboard Preview

> Dashboard screenshot
<img width="1305" height="738" alt="image" src="https://github.com/user-attachments/assets/5eab842d-5c5c-4e08-8504-f8b4d644e785" />
> Model View
<img width="1497" height="724" alt="image" src="https://github.com/user-attachments/assets/1839388d-67ac-475e-8a38-775c91824c70" />

---

## 📁 Repository Structure

```text
Data-Analytics-BI-Dashboard/
│
├── Dashboard_Screenshot.png
├── Data_Model.png
├── Task4.pbix
├── Business_Insight_Report.pdf
└── README.md
```

---

## 🚀 Project Outcome

This project successfully demonstrates the application of Business Intelligence concepts, data modeling techniques, DAX calculations, and dashboard development to convert raw data into actionable insights that support executive-level decision-making.

---

## 👨‍💻 Author

**Shashank Awasthi**

B.Tech CSE (Data Science & Artificial Intelligence)

- GitHub: https://github.com/Shashankawasthi026
- LinkedIn: linkedin.com/in/shashank-awasthi-b74b23317

---
⭐ If you found this project helpful, consider giving it a star!
