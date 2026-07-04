# Customer Trends Data Analysis using Python, MySQL & Power BI

## Project Overview

This project analyzes customer shopping behavior using Python, MySQL, and Power BI. The dataset was cleaned and transformed in Python, analyzed using SQL queries in MySQL, and visualized through an interactive Power BI dashboard to generate meaningful business insights.

---

## Business Problem

The objective of this project is to understand customer purchasing behavior and identify trends that can help improve marketing strategies, customer engagement, and business decision-making.

---

## Tools & Technologies Used

* Python
* Pandas
* SQLAlchemy
* Jupyter Notebook
* MySQL
* Microsoft Power BI

---

## Project Workflow

* Data Cleaning and Preprocessing using Python
* Feature Engineering
* Importing Data into MySQL
* SQL Business Analysis
* Interactive Dashboard Creation in Power BI
* Business Insights and Recommendations

---

## Data Preprocessing

The following preprocessing steps were performed:

* Handled missing values
* Converted column names to snake_case
* Created `age_group` using `qcut()`
* Converted purchase frequency into numerical values
* Removed redundant columns
* Checked data quality using `info()` and `describe()`

---

## SQL Analysis

The following analyses were performed using MySQL:

* Revenue by Gender
* Revenue by Product Category
* High Spending Customers
* Customer Segmentation
* Product Ranking using Window Functions
* Average Purchase Amount Analysis

---

## Power BI Dashboard

The dashboard includes:

* Total Customers
* Average Purchase Amount
* Average Review Rating
* Revenue by Category
* Revenue by Age Group
* Subscription Status
* Interactive slicers for Gender, Category, and Subscription Status
  <img width="700" height="408" alt="Screenshot 2026-07-04 184037" src="https://github.com/user-attachments/assets/8cde510d-b58c-4b52-bb70-e59e558549b9" />


---

## Key Insights

* Young Adult customers contribute significantly to revenue.
* Express Shipping customers have a higher average purchase amount.
* Many loyal customers are not subscribed.
* Some product categories generate higher revenue than others.

---

## Repository Contents

```text
Customer-Trends-Data-Analysis/
│── Customer_Trends_Analysis.ipynb
│── customer_analysis_queries.sql
│── Customer_Behaviour_Dashboard.pbix
│── shopping_trends.csv
│── README.md
```

