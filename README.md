# Retail Sales Data Analysis

## Overview
This project focuses on analyzing retail sales data to uncover valuable insights into customer behavior, sales trends, and product performance. The project is structured to demonstrate a complete data analysis workflow, including data cleaning, database storage, querying, analysis, and visualization using Python, SQL, and Power BI.

---

## Project Objectives
1. **Understand Customer Behavior**:
   - How do customer demographics (age, gender) influence purchasing habits?
   - What are the relationships between customer age, spending, and product preferences?

2. **Analyze Sales Trends**:
   - Are there discernible patterns in sales across different time periods (daily, monthly, seasonal)?
   - What drives revenue growth over time?

3. **Product Insights**:
   - Which product categories are the most popular among customers?
   - Identify top-performing products in terms of revenue and sales quantity.
  
---
## Files and Workflow

### **1. `retail_sales_data.csv`**
- Raw dataset containing customer transactions, product details, and purchase information.

---

### **2. `retail_sales_cleaned.csv`**
- Cleaned dataset after handling missing values, removing duplicates, and renaming columns for consistency.

---

### **3. `retail_sales_data_exploration_and_analysis-checkpoint.ipynb`**
- **Python Notebook** for data exploration and cleaning:
  - Checked for missing and duplicate values.
  - Renamed columns for clarity.
  - Cleaned and prepared the dataset for analysis.
- **Key Analysis**:
  - Initial data exploration using `pandas` and `matplotlib`.
  - Insights into data distribution and key metrics.

---

### **4. `sales_analysis.sql`**
- SQL commands to create and populate the database schema.
- Queries for analyzing trends, top products, and customer behavior:
  - Total revenue analysis.
  - Top-performing product categories.
  - Monthly and seasonal sales trends.

---

### **5. `sales_data_analysis.pbix`**
- **Power BI Dashboard** containing interactive visualizations:
  - **Monthly Sales Trends** (Line Chart).
  - **Top Performing Product Categories** (Donut Chart).
  - **Revenue by Product Category** (Clustered Bar Chart).
  - **Spending Analysis by Gender and Age Group** (Clustered Bar Chart).
  - **Transaction Analysis** by quantity and product category (Clustered Column Chart).

---

## Key Insights

### **1. Revenue Trends**
- Monthly sales peaked in **December**, indicating strong seasonal demand.
- Weekends consistently generated higher revenue compared to weekdays.

### **2. Top Products**
- **Electronics** and **Apparel** were the top-performing product categories.
- **Accessories** had lower overall sales but showed steady and consistent growth.

### **3. Customer Behavior**
- Customers aged **25-34** were the highest spenders across all product categories.
- Gender-based preferences revealed significant variation in purchasing habits.

---

## Tools Used

### **Python**
- **Libraries**: `Pandas`, `Matplotlib`, `SQLAlchemy`
- Used for data cleaning, exploratory analysis, and initial visualizations.

### **SQL (PostgreSQL)**
- Structured data storage and analysis.
- Executed queries to derive business insights.

### **Power BI**
- Designed an interactive dashboard for advanced data visualization and storytelling.

---
