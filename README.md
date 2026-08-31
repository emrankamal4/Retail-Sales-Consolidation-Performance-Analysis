# Retail Sales Consolidation & Analysis

## 📌 Business Scenario

A beverage supplier receives sales reports separately from four major retail partners: **Costco, Target, Walgreens, and Walmart**.

Each retailer provides its own Excel report, making it difficult to get a single view of overall sales performance. Instead of manually combining these files, the goal was to create a repeatable process that consolidates the data and prepares it for analysis.

The main business questions were:

* How much revenue is being generated overall?
* Which beverage brands perform best?
* Which retailers contribute the most revenue?
* Which regions and states perform best?
* How does revenue change throughout the year?

---

## 🎯 Project Objective

Build a consolidated retail sales dataset from four separate Excel files using **Power Query**, then use the combined data to produce business-focused analysis and reporting.

The project focuses on creating a workflow that could easily be reused when new retailer reports are received.

---

## 🛠️ Tools & Techniques

* **Microsoft Excel**
* **Power Query**
* Excel Tables
* Data Cleaning & Transformation
* Data Consolidation
* PivotTables
* Excel Formulas
* Data Visualization

---

## 🔄 Data Workflow

```text
Costco.xlsx
Target.xlsx
Walgreens.xlsx  ───► Power Query ───► Consolidated Dataset
Walmart.xlsx
                              │
                              ▼
                        Data Analysis
                              │
                  ┌───────────┼───────────┐
                  ▼           ▼           ▼
                KPIs      PivotTables    Charts
```

The four retailer files were imported and combined through Power Query while preserving the retailer information needed for comparison and analysis.

---

## 📊 Dataset

The final consolidated dataset contains **288 records** across:

* **4 Retailers:** Costco, Target, Walgreens, Walmart
* **6 Beverage Brands:** Coca-Cola, Diet Coke, Sprite, Fanta, Powerade, Dasani Water
* **3 Regions:** Northeast, South, West
* **3 States:** New York, Texas, California
* **12 Months of Sales Data**


## 📈 Analysis Performed

The consolidated dataset was used to analyze sales performance across several dimensions:

### Revenue Analysis

* Total revenue
* Monthly revenue trends
* Revenue by beverage brand
* Revenue by retailer
* Revenue by region/state

### Sales Performance

* Total units sold
* Total orders
* Average order value
* Brand performance comparison
* Retailer performance comparison

The analysis was designed around practical business questions rather than creating separate reports for every available field.


## 🎯 Business Value

The main value of this project is not simply the final charts.

The project demonstrates how multiple independent retailer reports can be turned into a **single analysis-ready dataset** using Power Query.

Instead of manually opening, copying, and combining four Excel files, the process creates a more efficient and repeatable reporting workflow.

This approach could be reused whenever updated retailer files are received, making future reporting faster and more consistent.


## 🚀 What This Project Demonstrates

This project demonstrates practical experience with:

* Combining multiple Excel data sources using Power Query
* Cleaning and transforming raw business data
* Building a consolidated dataset for analysis
* Creating KPIs and summary metrics
* Analyzing sales across retailers, products, regions, and time
* Turning operational spreadsheets into useful business reporting

### Core Workflow

**Multiple Excel Sources → Power Query → Consolidated Data → Analysis → Business Reporting**
