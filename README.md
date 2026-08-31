# Retail Sales Consolidation & Performance Analysis

## 📌 Business Scenario

A beverage supplier receives sales reports separately from four major retail partners: **Costco, Target, Walgreens, and Walmart**.

Each retailer maintains its own Excel file, which creates a common reporting problem: management needs to compare overall performance, but the information is scattered across multiple files.

The goal of this project was to **consolidate the four retailer files into a single analysis-ready dataset**, standardize the information, and create a management-level view of sales performance.

The business questions were:

* How much revenue did the company generate overall?
* Which beverage brands generate the most revenue?
* Which retailer contributes the most to sales?
* Which region performs best?
* How does revenue change throughout the year?
* How are sales distributed across retailers and beverage brands?

Rather than analyzing each source independently, I treated the four files as one reporting pipeline — similar to how an analyst would consolidate recurring reports from multiple business partners.

---

## 🛠️ Tools & Techniques

**Microsoft Excel**

* Power Query
* Data transformation and consolidation
* Excel Tables
* PivotTables
* Excel formulas
* Data analysis and reporting
* KPI development
* Data visualization

---

## 🔄 Data Workflow

```text
Costco.xlsx
       │
Target.xlsx
       │
Walgreens.xlsx  ───► Power Query ───► Consolidated Dataset
       │
Walmart.xlsx
                         │
                         ▼
                 Analysis & Reporting
                         │
             ┌───────────┼───────────┐
             ▼           ▼           ▼
         KPIs       PivotTables    Charts
```

The four retailer files were combined into a single dataset while retaining the original source information.

This made it possible to analyze the business as a whole instead of maintaining four disconnected reports.

---

## 📊 Dataset

The consolidated dataset contains **288 records** across:

* **4 retail partners:** Costco, Target, Walgreens, Walmart
* **6 beverage brands:** Coca-Cola, Diet Coke, Sprite, Fanta, Powerade, Dasani Water
* **3 regions:** Northeast, South, West
* **3 states:** New York, Texas, California
* **12 months of sales activity**

## 📈 Analysis Performed

The workbook provides a consolidated view of sales performance through:

### Executive KPIs

* Total Revenue
* Total Orders
* Average Order Value
* Total Units Sold
* Top Beverage Brand
* Top Region
* Top Retailer
* Top State



## 🎯 Business Value

The purpose of this project was not simply to combine four Excel files.

The consolidation creates a **single source for sales reporting** that allows management to compare retailers, products, regions, and time periods without manually opening and analyzing each retailer's file.

This type of workflow could be reused whenever new monthly retailer files arrive, reducing repetitive manual reporting and making cross-retailer analysis much easier.


## 🚀 What This Project Demonstrates

This project demonstrates my ability to:

**Collect → Transform → Consolidate → Analyze → Communicate**

More specifically, it shows practical experience with:

* Combining data from multiple Excel sources
* Building a repeatable Power Query workflow
* Working with structured retail sales data
* Creating business-focused KPIs
* Analyzing sales across multiple dimensions
* Using PivotTables and formulas to answer business questions
* Turning raw operational files into management-ready reporting

---

## 👤 About

Built as a practical data analytics project to strengthen my skills in **Excel, Power Query, data transformation, and business-oriented reporting**.
