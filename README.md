<div align="center">

# 🛒 Blinkit Sales Analysis Dashboard

### An Interactive Retail Sales Analysis Using Power BI

**Transforming grocery sales data into meaningful business insights**

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Domain](https://img.shields.io/badge/Domain-Retail%20Analytics-2E8B57?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</div>

---

## 📌 Project Overview

This project focuses on analyzing Blinkit's grocery sales data to understand product performance, outlet characteristics, customer preferences, and overall business performance.

Using Microsoft Power BI, I developed an interactive dashboard that provides insights into sales distribution across different item types, fat content categories, outlet sizes, outlet locations, and outlet types.

The dashboard combines key performance indicators (KPIs), interactive slicers, and multiple visualizations to help stakeholders explore sales patterns and make data-driven business decisions.

## 📊 Dashboard Preview

![Blinkit Sales Dashboard](images/Dashboard.png)

## 🎯 Business Objectives

- Analyze overall sales performance and key business metrics.
- Identify high-performing product categories.
- Understand customer preferences based on item fat content.
- Compare sales performance across different outlet sizes.
- Analyze sales contribution by outlet location tiers.
- Evaluate outlet performance based on outlet type.
- Understand sales trends across outlet establishment years.
- Provide actionable recommendations to improve business performance.

## 📂 Dataset Overview

The dataset contains grocery sales and outlet-related information.

**Key attributes:**

- Item Fat Content
- Item Type
- Outlet Size
- Outlet Location Type
- Outlet Type
- Outlet Establishment Year
- Item Sales
- Item Rating
- Item Visibility

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development and visualization |
| Power Query | Data cleaning and transformation |
| DAX | KPI calculations and measures |
| Data Modeling | Organizing data for analysis |
| Data Visualization | Presenting business insights |

## 📈 Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Sales | $1.20M |
| Average Sales | $141 |
| Number of Items | 8,523 |
| Average Rating | 3.9 |

## 🔍 Key Business Insights

### 1. Sales Performance by Fat Content

- Regular fat products contribute approximately **$776.32K** in sales.
- Low Fat products contribute approximately **$425.36K**.
- Regular fat products account for around **64.6%** of total sales.
- Low Fat products contribute approximately **35.4%**.

**Insight:** Regular fat products generate a significantly higher share of sales compared to Low Fat products.

### 2. Sales Performance by Item Type

- Fruits & Vegetables and Snack Foods are the leading item categories, each contributing approximately **$0.18M**.
- Household products contribute approximately **$0.14M**.
- Frozen Foods contribute approximately **$0.12M**.
- Dairy contributes approximately **$0.10M**.
- Seafood is among the lowest-performing categories at approximately **$0.01M**.

**Insight:** Fruits & Vegetables and Snack Foods are the strongest product categories, while Seafood contributes the least.

### 3. Sales by Outlet Size

| Outlet Size | Total Sales | Contribution |
|---|---:|---:|
| Medium | $507.90K | 42.3% |
| Small | $444.79K | 37.0% |
| High | $248.99K | 20.7% |

**Insight:** Medium-sized outlets generate the highest sales contribution, followed by Small-sized outlets.

### 4. Sales by Outlet Location

| Outlet Location | Total Sales | Contribution |
|---|---:|---:|
| Tier 3 | $472.13K | 39.3% |
| Tier 2 | $393.15K | 32.7% |
| Tier 1 | $336.40K | 28.0% |

**Insight:** Tier 3 locations generate the highest sales, indicating strong sales performance in these outlet locations.

### 5. Outlet Establishment Trend

- Sales were approximately $78K at the earliest displayed establishment year.
- Sales increased to around $130K in the following year.
- The highest sales contribution reached approximately **$205K around 2018**.
- Sales subsequently stabilized around $129K–$131K in the later displayed years.

**Insight:** The dashboard shows a significant sales peak around 2018, followed by relatively stable sales performance.

### 6. Sales by Outlet Type

| Outlet Type | Total Sales | No. of Items |
|---|---:|---:|
| Supermarket Type 1 | $787.55K | 5,577 |
| Grocery Store | $151.94K | 1,083 |
| Supermarket Type 2 | $131.48K | 928 |
| Supermarket Type 3 | $130.71K | 935 |

**Insight:**

- Supermarket Type 1 contributes the highest sales, approximately **65.5% of total sales**.
- Grocery Stores contribute approximately $151.94K.
- Supermarket Type 2 and Type 3 have comparatively lower sales contributions.

**Business Finding:** Supermarket Type 1 is the strongest outlet format in terms of total sales.

## 💡 Business Recommendations

| Business Area | Recommendation |
|---|---|
| Product Strategy | Focus on high-performing categories such as Fruits & Vegetables and Snack Foods. |
| Inventory Management | Maintain sufficient stock of products with higher sales demand. |
| Outlet Expansion | Study the success of Medium-sized outlets before planning expansion. |
| Location Strategy | Investigate the factors driving higher sales in Tier 3 locations. |
| Product Portfolio | Review low-performing categories such as Seafood for improvement opportunities. |
| Outlet Performance | Analyze the strategies used by Supermarket Type 1 outlets. |
| Sales Monitoring | Regularly track sales trends and outlet performance through Power BI. |

## 🎛️ Dashboard Features

- Interactive KPI Cards
- Sales Analysis by Fat Content
- Item Type Sales Comparison
- Outlet Size Analysis
- Outlet Location Analysis
- Outlet Establishment Year Trend
- Outlet Type Performance Matrix
- Interactive Slicers and Filters
- Dynamic Dashboard Navigation

## 📊 Skills Demonstrated

- Data Cleaning and Transformation
- Exploratory Data Analysis
- Business Intelligence
- Data Visualization
- KPI Development
- Power BI Dashboard Development
- DAX and Data Modeling
- Business Insights and Recommendations

## 🚀 How to Use This Project

1. Download the `Blinkit_Dashboard.pbix` file.
2. Open the file using Microsoft Power BI Desktop.
3. Explore the dashboard and its visualizations.
4. Apply filters using Outlet Location Type, Outlet Size, and Outlet Type.
5. Analyze the changes in KPIs and sales performance.

## 📁 Repository Structure

```text
blinkit-sales-dashboard-power-bi/
│
├── images/
│   └── Dashboard.png
│
├── Blinkit_Dashboard.pbix
│
└── README.md
