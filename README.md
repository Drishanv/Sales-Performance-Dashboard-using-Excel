# 📊 Sales Performance Dashboard

## 📌 Overview
This project presents a **Sales Performance Dashboard** created in Microsoft Excel as part of Neozeno data analytics program 
The goal is to clean, analyze, visualize, and present key business insights from a sales dataset.

The dashboard highlights:
- Regional sales performance  
- Category-wise contribution  
- Monthly sales trends  
- Core KPI metrics  

---

## 🎯 Requirements Covered

### ✔ Data Cleaning  
- Removed duplicate entries  
- Handled missing numerical values using **AVERAGE**  
- Corrected missing Postal Codes based on other location information  
- Ensured dates were converted to valid date formats (Order Date, Ship Date)  
- Standardized category/region/state names  
- Added computed fields such as:
  - **Sales level** (High/Low using IF)  
  - **Year** and **Month** (using DATE/TEXT functions)

### ✔ Data Analysis Using Excel Formulas  
The following formulas were used:

#### **1. IF Function – Sales Level**
### **2. SUMIF – Total Sales by Region**
### **3. COUNTIF – High/Low Sales Count**
### **4. VLOOKUP – Fetch Category**
### **5. AVERAGE, MAX, MIN – Summary Statistics**
### **6. TEXT/DATE Functions – Year & Month**

These formulas fulfill the requirement to use at least **five Excel analysis functions**.

---

## 📊 Visualizations Included

### 🔸 **1. Region-wise Total Sales (Column Chart)**  
Shows how each region (Central, East, South, West) contributes to total revenue.  
Used for comparing regional performance and identifying strong/weak regions.

---

### 🔸 **2. MOM (Month-over-Month) Average Sales Trend – Line Chart**  
Displays the average order value per month across the year.  
Helps identify seasonal patterns.

---

### 🔸 **3. Category-wise Total Sales – Pie Chart**  
Breakdown of sales by major product categories:
- Furniture  
- Office Supplies  
- Technology  

Shows percentage contribution of each category to overall sales.

---

### 🔸 **4. (Optional) Sales by State – Map Chart**  
If supported by Excel, a **Filled Map** visualizes total sales by U.S. state.

---

## 🧮 Pivot Tables Created

### ✔ Region-wise Sales Pivot  
- Rows: Region  
- Values: Sum of Sales  

### ✔ Category-wise Sales Pivot  
- Rows: Category  
- Values: Sum of Sales  

### ✔ Month-over-Month Average Sales Pivot  
- Rows: Month (Jan–Dec)  
- Values: Average of Sales  

### ✔ High/Low Sales Summary Pivot  
- Rows: Sales Level  
- Values: Count of Orders  

These pivot tables support KPI generation and charts.

---

## 🏆 KPI Metrics Displayed on Dashboard

| KPI                     | Example Value |
|-------------------------|---------------|
| **Total Sales**         | 2,261,537     |
| **Average Order Value** | 230           |
| **High Sales Count**    | 462           |
| **Top Region**          | West          |
| **Bottom Region**       | South         |

> Values may vary depending on dataset version.

---

## 📈 Final Dashboard Highlights

The completed **Sales Performance Dashboard** includes:

- A professional dashboard title  
- KPI cards  
- Region-wise sales column chart  
- MOM average sales line chart  
- Category-wise sales pie chart  
- Optional geographic map  
- Clean formatting and consistent theme  

### The dashboard helps users:
- Identify top/bottom-performing regions  
- Understand category contributions  
- Observe monthly sales trends  
- Compare high vs low-value orders  

---

## 📝 Conclusion

This project demonstrates essential **Excel data analytics skills**, including:

- Data cleaning  
- Analytical formulas (IF, SUMIF, COUNTIF, VLOOKUP, AVERAGE, MIN, MAX)  
- Date and text functions  
- Pivot Tables  
- Chart creation  
- Dashboard design  
- PDF reporting  

The **Sales Performance Dashboard** provides a comprehensive view of business performance across **regions**, **categories**, and **time**, making it valuable for academic and business use.
