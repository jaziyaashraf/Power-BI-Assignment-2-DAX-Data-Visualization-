# Power-BI-Assignment-2-DAX-Data-Visualization-

# 📊 Sales Analysis Dashboard – Power BI

## 📌 Project Overview

This project focuses on analyzing sales performance using Microsoft Power BI. The dashboard provides insights into sales, targets, profit, quantity sold, customer segments, and geographical sales distribution.

The main objective is to compare actual sales with sales targets and identify business performance trends through interactive visualizations.

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query (Data Cleaning & Transformation)
- DAX (Data Analysis Expressions)
- Data Visualization
- Data Modeling

## 📂 Dataset

This project uses three datasets:

1. **List of Orders** – Contains order details, order dates, customer information, state, and city.
2. **Order Details** – Contains category, sub-category, sales amount, profit, and quantity.
3. **Sales Target** – Contains monthly sales targets for different product categories.

## 🔄 Data Cleaning & Transformation

Data preparation was performed using Power Query:

- Removed unnecessary rows and handled missing values.
- Corrected data types.
- Transformed customer names into proper case.
- Created a Location column by combining City and State.
- Created Profit Margin and Profit Status columns.
- Merged and transformed tables where required.
- Created grouped and summarized tables for analysis.

## 📈 Dashboard Visualizations

The dashboard includes the following nine visualizations:

1. **Clustered Column Chart:** Compares actual sales amount with sales targets across product categories.
2. **Donut Chart:** Displays maximum profit margin across sub-categories.
3. **Line Chart:** Shows monthly sales trends.
4. **Scatter Chart:** Analyzes the relationship between profit and quantity sold across sub-categories.
5. **Cards:** Displays total sales amount and total sales target.
6. **Multi-Row Card:** Displays the minimum sales target for each segment.
7. **Matrix:** Compares actual sales and targets by category and month.
8. **Map:** Displays geographical sales distribution across cities.
9. **Treemap:** Visualizes sales amounts across sub-categories.
10. **Funnel Chart:** Displays distinct order counts across states.

## 📐 DAX Measures

The following DAX measures were created for analysis:

```DAX
Total Sales Amount =
SUM('Order Details'[Amount])
```

```DAX
Total Sales Target =
SUM('Sales target'[Target])
```

```DAX
Minimum Target =
MIN('Sales target'[Target])
```

```DAX
Order Count =
DISTINCTCOUNT('List of Orders'[Order ID])
```

## 🎯 Project Objectives

- Compare actual sales performance against targets.
- Analyze monthly sales trends.
- Identify profitable product sub-categories.
- Understand sales performance across different segments.
- Analyze geographical sales distribution.
- Evaluate order counts across states.
- Support data-driven business decisions.

## 💡 Key Learnings

Through this project, I gained practical experience in:

- Data cleaning and transformation using Power Query.
- Creating relationships between multiple tables.
- Writing DAX measures.
- Building interactive dashboards.
- Working with different Power BI visuals.
- Analyzing business data and generating insights.

## 👩‍💻 Project Created By

**Jaziya**

Data Analytics | Excel | Power BI | SQL

