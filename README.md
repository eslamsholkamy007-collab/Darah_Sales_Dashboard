# 🏡 Darah Sales Dashboard

## 📌 Project Overview

**Darah Sales Dashboard** is an interactive Power BI dashboard developed to analyze sales performance for the **Darah Project**, one of Egypt's national initiatives for the **Development of Governorate Capitals**, implemented under the supervision of the **Egyptian Cabinet (Council of Ministers)**.

The dashboard consolidates large-scale real estate sales data into an interactive reporting solution, enabling stakeholders to monitor sales performance, inventory availability, project progress, and phase performance through dynamic visualizations and business intelligence techniques.

---

## 🎯 Business Objectives

* Monitor sales performance across all Darah development projects.
* Track sold and remaining residential units.
* Identify the highest-performing project.
* Analyze sales trends across different time periods.
* Compare sales performance between project phases.
* Provide data-driven insights to support strategic planning and decision-making.
* Improve reporting efficiency through an interactive business intelligence dashboard.


---

## 📊 Key Performance Indicators (KPIs)

* 💰 Total Sales
* 🏆 Best Performing Project
* 🏠 Total Units Sold
* 📦 Remaining Units
* 📈 Sales Trend Over Time
* 🏗️ Best Performing Phase

---

## 📈 Dashboard Features

* Interactive KPI Cards
* Dynamic Date Filtering
* Sales Trend Analysis
* Project Performance Analysis
* Phase Performance Comparison
* Sold vs Remaining Units Analysis
* Interactive Charts & Visualizations
* Drill-Down Analysis
* Responsive Dashboard Design

---

## 🛠️ Tools & Technologies

* Microsoft Power BI
* Power Query
* DAX (Data Analysis Expressions)
* Microsoft Excel
* Data Modeling

---

## 🔄 Data Preparation (ETL)

The dataset underwent a comprehensive data preparation process using **Power Query**, including:

* Data Cleaning
* Handling Missing Values
* Removing Duplicate Records
* Data Type Transformation
* Standardizing Data Structure
* Creating Unique Reference Tables
* Optimizing Data Quality for Reporting

---

## 🗂️ Data Modeling

To improve performance and ensure accurate analysis, a star schema data model was implemented.

The model includes:

* **Fact Table** containing sales transactions.
* **Unique Unit Dimension** created using a distinct Unit Code table.
* **Unique Project Dimension** created for project information.
* **Custom Date Table** built using DAX to support advanced time intelligence analysis.

Relationships were optimized to ensure fast filtering, efficient calculations, and scalable reporting for large datasets.

---

## 📅 Time Intelligence

A dedicated Date Table was created using DAX, including:

* Day
* Month
* Quarter
* Year

This enabled dynamic filtering and trend analysis across different time periods.

---

## 📐 DAX Measures

Several DAX measures were implemented to calculate business metrics, including:

* Total Sales
* Units Sold
* Remaining Units
* Best Project
* Sales by Phase
* Dynamic Time Intelligence Measures
* Performance Calculations

---

## 📊 Business Insights

The dashboard provides valuable business insights such as:

* Identifying the highest-performing real estate project.
* Tracking inventory availability through sold and remaining units.
* Detecting the strongest sales periods.
* Comparing sales performance across project phases.
* Supporting strategic planning through interactive data exploration.

---

## 📁 Project Structure

```text
Darah-Sales-Dashboard/
│
├── Dashboard.pbix
├── README.md
├── Dataset/
├── DAX/
└── Documentation/
```

---

## 🚀 Future Enhancements

* Sales Forecasting
* Customer Segmentation
* Geographic Sales Analysis
* Executive Summary Dashboard
* Mobile Optimized Report

---

## 👨‍💻 Author

**Eslam Ayman**

Administrative Lawyer | Data Analyst

### Technical Skills

* Power BI
* DAX
* Power Query
* SQL
* Excel
* Python
* Data Modeling
* Data Visualization

---

## Disclaimer

This dashboard was developed for data analysis and portfolio demonstration purposes using project-related data. It does not represent an official publication or report of the Egyptian Cabinet or any governmental authority.

---

⭐ If you found this project useful, feel free to star this repository.
