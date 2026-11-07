# 📊 Data Intelligence & Sales Analysis Dashboard

video links:- 1.https://drive.google.com/file/d/1OelPkUMcrF4MSztwl44qzPD-xqfs4fmX/view?usp=drivesdk
              2.https://drive.google.com/file/d/1yrYeCtfcP8iaOi-Csbohsp7S6j6BM07H/view?usp=drivesdk

> **Transforming raw transaction data into meaningful business insights through advanced Excel analysis.**

<p align="center">
  <strong>📈 Sales Analytics • 🧮 Excel Functions • 📊 Pivot Tables • 🎯 Interactive Dashboard</strong>
</p>

---

## 🎯 Project Overview

The **Data Intelligence & Sales Analysis Dashboard** is a spreadsheet-based business analytics project developed to analyze transaction-level sales data and convert it into structured summaries and useful business insights.

The workbook combines raw sales records, formula-based analysis, customer-level summaries, Pivot Table-style reports, statistical analysis, scenario planning, and a visual dashboard.

The project demonstrates how Microsoft Excel can be used for data cleaning and organization, business analysis, reporting, and data-driven decision-making.

## 📌 Project Information

| Detail | Information |
|---|---|
| Project Title | Data Intelligence & Sales Analysis Dashboard |
| Workbook | `final_project.xlsx` |
| Primary Tool | Microsoft Excel / Compatible Spreadsheet Application |
| Project Domain | Data Analysis & Business Intelligence |
| Academic Level | B.Com Student |
| Created By | **Vishvas Solanki** |
| Guided By | **Girish Sir Gondaliya** |

## 🗂️ Dataset Overview

The `Raw_Data` worksheet contains **250 transaction records** and fields covering customers, products, sales, payment methods, regions, and customer segments.

### Dataset Fields

| Column | Description |
|---|---|
| Transaction_ID | Unique transaction identifier |
| Date | Transaction date |
| Customer_ID | Customer identification code |
| Customer_Name | Customer name |
| Product_ID | Product identification code |
| Product_Name | Name of the product |
| Category | Product category |
| Quantity | Units purchased |
| Unit_Price | Price per unit |
| Payment_Method | Payment method used |
| Region | Sales region |
| Customer_Segment | Customer segment |
| Customer_Since | Customer's recorded joining date |
| Total_Amount | Total transaction amount |

### Dataset Snapshot

| Metric | Value |
|---|---:|
| Total Transactions | 250 |
| Unique Customers | 50 |
| Unique Products | 10 |
| Total Quantity Sold | 753 |
| Total Revenue | 229,192.47 |
| Transaction Date Range | 11 Apr 2024 – 11 Apr 2025 |

*Revenue is calculated from the `Total_Amount` field in the provided workbook.*

## 📁 Workbook Structure

The workbook contains four main worksheets:

| Worksheet | Purpose |
|---|---|
| `Raw_Data` | Original transaction-level sales data |
| `Analysis` | Excel functions, customer summaries, matching lists, scenarios, and regression output |
| `Pivot_Tables` | Summary reports for region, category, customer segment, product, and monthly revenue |
| `Dashbooard` | Dashboard worksheet with KPI cards and visual charts |

## 🔍 Key Analysis & Features

### 👥 1. Customer Analysis
- Customer-wise order count.
- Customer-wise quantity and revenue summaries.
- Customer ID and customer name mapping.
- Customer value analysis using aggregation formulas.

### 🌍 2. Regional Revenue Analysis
- Revenue comparison across Central, East, North, South, and West regions.
- Transaction counts by region.
- Average quantity analysis across regions.

### 🛍️ 3. Product & Category Analysis
- Product-wise transaction and quantity summaries.
- Category-wise revenue analysis.
- Comparison of product categories using Pivot Table-style reports.

### 💳 4. Customer Segment & Payment Analysis
- Analysis of Basic, Premium, and Standard customer segments.
- Payment method distribution in the source data.
- Segment-wise transaction and revenue summaries.

### 📅 5. Date & Time Analysis
The Analysis worksheet demonstrates date and time functions such as:
- `TODAY()` – Returns the current date.
- `NOW()` – Returns the current date and time.
- `DATEDIF()` – Calculates the difference between two dates.
- `EOMONTH()` – Returns the last date of a month.

### 🧮 6. Advanced Excel Formula Practice

The workbook demonstrates practical use of these functions and formula concepts:

| Function / Concept | Purpose |
|---|---|
| `COUNTIF()` | Counts records that meet a condition |
| `SUMIF()` | Adds values that meet a condition |
| `IF()` | Returns results based on a logical test |
| `FILTER()` | Returns records matching selected criteria |
| `UPPER()` | Converts text to uppercase |
| `LEFT()` | Extracts characters from the beginning of text |
| `MID()` | Extracts characters from a specified position |
| `FIND()` | Finds the position of a character or text |
| `TODAY()` | Returns the current date |
| `NOW()` | Returns the current date and time |
| `DATEDIF()` | Calculates the difference between dates |
| `EOMONTH()` | Calculates a month-end date |
| `GROUPBY` concept | Demonstrates grouped customer-value analysis |

### 🔗 7. Compare Two Lists – Matching Names
- Compares names from List A and List B.
- Uses `COUNTIF()` with `IF()` to identify matching names.
- Displays matching results and a no-match outcome.

### 🔤 8. Abbreviations Using Text Functions
- Creates initials from customer names.
- Combines `LEFT()`, `MID()`, `FIND()`, and `UPPER()`.

### 🎛️ 9. What-If Analysis
The workbook includes scenario-based revenue calculations:

| Scenario | Price Multiplier |
|---|---:|
| Conservative | 0.90 |
| Base | 1.00 |
| Growth | 1.10 |
| Aggressive | 1.20 |

The scenario calculations compare estimated revenue against the base scenario to demonstrate the impact of different price multipliers.

### 📉 10. Linear Regression & Statistical Output
- Includes a regression analysis section titled **Linear Regression – Monthly Revenue**.
- Displays regression statistics such as Multiple R, R Square, Adjusted R Square, Standard Error, and Observations.
- Includes ANOVA and coefficient output.

## 📊 Pivot Table Reports

The `Pivot_Tables` worksheet contains summary reports for:

1. Revenue by Region
2. Revenue by Category
3. Customer Segment
4. Monthly Revenue
5. Product Performance

These summaries make it easier to compare sales performance across different business dimensions.

## 📈 Dashboard

The `Dashbooard` worksheet presents a visual summary of the project with KPI indicators and charts.

### Dashboard KPIs
- **Total Revenue**
- **Total Transactions**
- **Total Quantity Sold**
- **Total Customers**
- **Average Order Value**

The dashboard is designed to provide a quick overview of key sales metrics without requiring users to inspect every transaction.

## 🛠️ Tools & Skills Demonstrated

- Microsoft Excel / compatible spreadsheet tools
- Data organization and structured worksheets
- Excel formulas and logical functions
- Date and time functions
- Text manipulation functions
- Conditional matching
- Dynamic filtering
- Customer-level aggregation
- Pivot Table-style reporting
- What-If scenario analysis
- Regression and statistical output
- KPI reporting and dashboard visualization
- Business data interpretation

## 🚀 How to Use This Project

1. Open `final_project.xlsx` in Microsoft Excel or a compatible spreadsheet application.
2. Visit `Raw_Data` to explore the original transaction records.
3. Open `Analysis` to review the formulas, customer summaries, matching lists, scenarios, and regression output.
4. Visit `Pivot_Tables` to compare regional, category, segment, monthly, and product summaries.
5. Open `Dashbooard` to view the KPI cards and charts.
6. Change supported input cells in the Analysis worksheet to explore formula-based and scenario-based results.

**Compatibility note:** Some functions and features, particularly dynamic-array functions such as `FILTER()` and `GROUPBY`, may require a recent version of Microsoft Excel. Formula recalculation and dashboard behavior can vary across spreadsheet applications.

## 💡 Project Objectives

This project aims to demonstrate how spreadsheet tools can answer practical business questions:

- Which regions contribute to revenue?
- Which product categories generate sales?
- How do customer segments compare?
- How many transactions and units are recorded?
- Which names appear in both lists?
- How can customer names be converted into abbreviations?
- How do alternative scenario multipliers affect estimated revenue?
- What statistical information is available from the regression output?

## 👨‍💻 Author & Academic Guidance

**Made By:** Vishvas Solanki  
**Academic Status:** B.Com Student  
**Guided By:** Girish Sir Gondaliya

---

<p align="center">
  <strong>📊 Data • Analysis • Insights • Decisions</strong><br>
  <em>Academic project demonstrating practical Excel-based data analysis and business intelligence.</em>
</p>
