# 📊 Sales Performance Tracking Dashboard

## 📌 Project Overview

The **Sales Performance Tracking Dashboard** is a Business Intelligence project developed using **Microsoft Power BI** to analyze and monitor sales performance through interactive data visualizations.

The dashboard provides insights into **total sales, units sold, operating margin, sales trends, regional performance, product performance, retailer performance, sales methods, and monthly/quarterly sales patterns**.

The main objective of this project is to transform sales data into meaningful business insights that can support **data-driven decision-making and sales performance analysis**.

---

## 🎯 Objectives

- Track overall sales performance.
- Analyze monthly and yearly sales trends.
- Identify high-performing and low-performing regions.
- Analyze product-wise sales performance.
- Compare sales performance across retailers.
- Analyze different sales methods.
- Monitor total units sold and operating margin.
- Create interactive Power BI visualizations.
- Provide meaningful insights for business decision-making.

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX (Data Analysis Expressions)**
- **Microsoft Excel**
- **SQL / Database Sources**
- **Data Visualization**
- **Data Modeling**

---

## 📂 Project Workflow

Sales Data
    ↓
Data Collection
    ↓
Data Cleaning & Transformation
    ↓
Power Query
    ↓
Data Modeling
    ↓
DAX Calculations
    ↓
Interactive Visualizations
    ↓
Power BI Dashboard
    ↓
Business Insights


---

## 🧹 Data Preparation

The data preparation process includes:

- Removing duplicate records
- Handling missing values
- Standardizing data formats
- Converting data types
- Cleaning product and region names
- Combining data from different sources
- Creating relationships between tables
- Preparing the data for Power BI analysis

Power Query is used for data cleaning and transformation before creating the dashboard.

---

## 🗂️ Data Model

The project uses a structured data model consisting of sales transaction data and supporting dimension tables.

### Fact Table

The sales transaction table contains important fields such as:

- Sales ID
- Date
- Product ID
- Retailer ID
- Sales Method ID
- State ID
- City ID
- Sales Amount
- Units Sold
- Operating Margin

### Dimension Tables

The project includes supporting dimensions such as:

- Date
- Product
- Retailer
- Sales Method
- City
- State / Region

A **Star Schema** approach is used to organize the data and support efficient reporting.

---

## 📊 Dashboard Features

### 1. Sales Overview

The dashboard provides an overall view of sales performance through key metrics such as:

- Total Sales
- Total Units Sold
- Operating Margin
- Total Profit

### 2. Sales by Region

Regional analysis helps identify:

- High-performing regions
- Low-performing regions
- Regional sales contribution
- Geographic sales patterns

### 3. Product Analysis

The dashboard helps analyze:

- Product-wise sales
- Product categories
- Best-performing products
- Sales contribution by product

### 4. Retailer Analysis

Sales performance can be analyzed across different retailers to identify major contributors to overall sales.

### 5. Sales Method Analysis

The dashboard provides analysis of sales methods such as:

- Online
- Outlet
- In-store

### 6. Time-Based Analysis

Sales performance can be analyzed by:

- Year
- Quarter
- Month
- Date

This helps identify sales trends and seasonal patterns.

---

## 🧮 DAX Calculations

DAX measures are used to calculate important business metrics.

Example:

```DAX
Total Sales =
SUM('Data Sales Adidas'[Total Sales])
```

```DAX
Unit Sold =
SUM('Data Sales Adidas'[Unit Sold])
```

```DAX
Operating Margin =
AVERAGE('Data Sales Adidas'[Operating Margin])
```

DAX functions such as `SUM()`, `AVERAGE()`, `CALCULATE()`, `RANKX()`, `FILTER()`, and `DIVIDE()` can be used to create dynamic calculations and performance metrics.

---

## 📈 Visualizations

The dashboard uses different Power BI visualizations including:

- KPI Cards
- Line Charts
- Bar Charts
- Tables
- Maps
- Treemaps
- Area Charts
- Interactive Filters
- Slicers

These visualizations make it easier to understand sales performance and identify important trends.

---

## 💡 Key Insights

The dashboard helps users:

- Understand overall sales performance.
- Identify high-performing regions.
- Identify top-performing products.
- Compare retailer performance.
- Analyze sales methods.
- Monitor units sold.
- Analyze profit and operating margin.
- Identify monthly and quarterly sales patterns.
- Support data-driven business decisions.

---

## 🚀 Project Outcome

The final Power BI dashboard provides an interactive and user-friendly environment for analyzing sales performance.

It transforms raw sales data into meaningful visual insights and helps users understand **revenue trends, regional performance, product performance, retailer contribution, sales methods, and key performance indicators**.

---

## 🔮 Future Enhancements

Future improvements can include:

- AI-based sales forecasting
- Machine learning-based prediction
- Real-time data streaming
- Automated sales alerts
- Mobile-optimized dashboard
- Advanced customer analysis
- AI-driven sales recommendations
- Automated reporting

---

## 👩‍💻 Developed By

**Gowsalya C**

**Project:** Sales Performance Tracking

**Degree:** B.Sc. Computer Science with Cognitive Systems

---

## ⭐ Skills Demonstrated

`Power BI` `Power Query` `DAX` `Data Visualization` `Data Analysis` `Data Modeling` `Excel` `SQL` `Business Intelligence`
