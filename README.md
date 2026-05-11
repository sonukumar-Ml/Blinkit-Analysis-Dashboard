# 🟡 Blinkit Sales Analysis — Power BI Dashboard

<p align="center">
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  <img src="https://img.shields.io/badge/DAX-FF6F00?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge"/>
</p>

---

## 📌 Introduction

**Blinkit** (formerly Grofers) is India's largest last-minute grocery delivery app, operating across multiple cities with thousands of outlets and product categories. With rapid expansion and a highly diverse product portfolio, understanding **what sells, where it sells, and how customers respond** becomes critical for strategic business decisions.

This project is an **end-to-end Power BI Dashboard** built to analyze Blinkit's grocery sales data — transforming raw transactional records into clear, interactive, and actionable business intelligence.

---

## ❓ Problem Statement

> *To conduct a comprehensive analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution — to identify key insights and opportunities for optimization using various KPIs and visualizations in Power BI.*

---

## 🎯 Business Requirements

### KPI Requirements

| KPI | Description |
|-----|-------------|
| 💰 **Total Sales** | The overall revenue generated from all items sold |
| 📊 **Average Sales** | The average revenue per sale |
| 📦 **Number of Items** | The total count of different items sold |
| ⭐ **Average Rating** | The average customer rating for items sold |

---

### Chart Requirements

| # | Chart | Objective | Chart Type |
|---|-------|-----------|------------|
| 1 | **Total Sales by Fat Content** | Analyze the impact of fat content on total sales & other KPIs | Donut Chart |
| 2 | **Total Sales by Item Type** | Identify performance of different item types | Bar Chart |
| 3 | **Fat Content by Outlet for Total Sales** | Compare sales across outlets segmented by fat content | Stacked Column Chart |
| 4 | **Total Sales by Outlet Establishment** | Evaluate how outlet age influences total sales | Line Chart |
| 5 | **Sales by Outlet Size** | Analyze correlation between outlet size and total sales | Donut / Pie Chart |
| 6 | **Sales by Outlet Location** | Assess geographic distribution of sales across locations | Funnel Map |
| 7 | **All Metrics by Outlet Type** | Comprehensive view of all KPIs broken down by outlet type | Matrix Card |

---

## 🔄 Steps in Project

```
1. Requirement Gathering / Business Requirements
2. Data Walkthrough
3. Data Connection
4. Data Cleaning / Quality Check
5. Data Modeling
6. Data Processing
7. DAX Calculations
8. Dashboard Lay-outing
9. Charts Development and Formatting
10. Dashboard / Report Development
11. Insights Generation
```

---

## 📸 Dashboard

![image alt](https://github.com/sonukumar-Ml/Blinkit-Analysis-Dashboard/blob/main/Blinkit-analysis-dashboard.png?raw=true)


---

## ⚡ KPIs at a Glance

| 💰 Total Sales | 📦 No. of Items | ⭐ Avg Rating | 📊 Avg Sales |
|:-:|:-:|:-:|:-:|
| **$1.20M** | **8,523** | **4.0 / 5** | **$141** |

---

## 📊 Charts & Visualizations

### 1️⃣ Total Sales by Fat Content
<!-- ADD YOUR FAT CONTENT DONUT CHART SCREENSHOT HERE -->


---
### 2️⃣ Total Sales by Item Type
<!-- ADD YOUR ITEM TYPE BAR CHART SCREENSHOT HERE -->


---
### 3️⃣ Fat Content by Outlet — Total Sales
<!-- ADD YOUR STACKED COLUMN CHART SCREENSHOT HERE -->


---
### 4️⃣ Total Sales by Outlet Establishment Year
<!-- ADD YOUR LINE CHART SCREENSHOT HERE -->


---
### 5️⃣ Sales by Outlet Size
<!-- ADD YOUR OUTLET SIZE DONUT CHART SCREENSHOT HERE -->


---
### 6️⃣ Sales by Outlet Location
<!-- ADD YOUR FUNNEL MAP SCREENSHOT HERE -->


---
### 7️⃣ All Metrics by Outlet Type
<!-- ADD YOUR MATRIX CARD SCREENSHOT HERE -->


---

## 💡 DAX Measures

<!-- ADD YOUR DAX SCREENSHOT HERE -->


```dax
Total Sales   = SUM('BlinkIT Grocery Data'[Sales])
Avg Sales     = AVERAGE('BlinkIT Grocery Data'[Sales])
No of Items   = COUNTROWS('BlinkIT Grocery Data')
Avg Rating    = AVERAGE('BlinkIT Grocery Data'[Rating])
```

---

## 🔍 Key Insights

| # | Insight |
|---|---------|
| 🥇 | **Tier 3 outlets** are the highest revenue generators at **$472.13K** |
| 🥈 | **Fruits & Vegetables** and **Snack Foods** lead all categories at **$0.18M each** |
| 🥉 | **64.6%** of sales come from **Regular Fat** products |
| 📅 | Sales peaked in **2018** at **$205K** |
| 🏪 | **Medium-sized** outlets dominate with **42.27%** of total sales |
| 🏬 | **Supermarket Type1** handles the highest volume — **5,577 items** |
| ⭐ | All outlet types maintain consistently high ratings between **3.91 – 3.93** |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard design & visualization |
| **DAX** | Custom KPI measures & calculations |
| **Power Query** | Data cleaning & transformation |
| **Microsoft Excel** | Raw data source |

---




