# Data-Analyst-Intern-ApexPlanet
# Task 1 - Foundational Setup & Exploratory Data Analysis (EDA)

## Objective
To set up the environment, clean the dataset, and perform Exploratory Data Analysis (EDA).

## Dataset
Sample Superstore Dataset

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning
- Checked missing values
- Removed duplicates
- Converted date columns to datetime format
- Handled outliers using IQR method
- Saved cleaned dataset

## Visualizations Created
1. Distribution of Sales (Histogram)
2. Total Sales by Category (Bar Chart)
3. Total Profit by Category (Bar Chart)
4. Correlation Matrix (Heatmap)
5. Total Sales Trend (Line Chart)

## Key Insights

1. Office Supplies generated the highest total sales among all categories.
2. Furniture recorded a negative profit despite having high sales.
3. Most sales transactions are of lower value, indicating a right-skewed distribution.
4. Discount and Profit have a strong negative correlation (-0.46).
5. Sales fluctuate significantly over time with several peaks and dips.

# Task 2 - SQL for Data Extraction

## 📌 Objective

The objective of this task is to learn and apply SQL concepts for data extraction and analysis using the Superstore dataset. This task covers basic SQL operations, advanced SQL concepts, and integration of Python with SQLite.

---

## 🛠️ Tools & Technologies Used

* Python
* SQLite (`sqlite3`)
* Pandas
* Jupyter Notebook

---

## 🔹 SQL Concepts Covered

### Basic SQL

* SELECT
* WHERE
* ORDER BY
* LIMIT
* GROUP BY
* HAVING
* JOINs

### Advanced SQL

* Subqueries
* Common Table Expressions (CTEs)
* Window Functions

  * ROW_NUMBER()
  * RANK()
  * LAG()
  * LEAD()
* Views

---

## 🔹 Python + SQLite Integration

* Connected Python to SQLite using `sqlite3`
* Executed SQL queries using `pandas.read_sql()`
* Created reusable database utility functions in `db_utils.py`

---

## 📊 Business Questions Solved

1. Top 5 products by sales
2. Monthly sales trend
3. Customer segment by total sales
4. Total profit by category
5. Top 10 customers by sales
6. Products with negative profit
7. Average discount by category
8. Number of orders by region
9. State-wise sales analysis
10. Average sales across all orders

---

## 🎯 Key Learnings

* Gained hands-on experience with SQL fundamentals and advanced SQL concepts.
* Learned to extract and analyze data using SQLite.
* Integrated Python with SQL for efficient data analysis.
* Developed reusable scripts for database operations.
* Solved business-oriented problems using SQL queries.

---

## 🚀 Outcome

Successfully completed **Task 2: SQL for Data Extraction** as part of the **Data Analytics Internship at ApexPlanet**, demonstrating proficiency in SQL querying, database management, and Python-SQL integration.
