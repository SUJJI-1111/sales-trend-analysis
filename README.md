# 📊 Sales Trend Analysis Using Aggregations

## 📌 Project Overview
This project analyzes **monthly revenue** and **order volume** using SQL queries on a sample sales dataset.  
The goal is to practice grouping, aggregations, and time-based trend analysis with SQL + Python.

---

## 📂 Files in this Repository
- `task-6-sales-trend.ipynb` → Jupyter/Colab notebook with full code  
- `online_sales.db` → Sample SQLite database with orders table (optional upload)  
- `sales_trend_chart.png` → Visualization of monthly revenue and order volume (optional)  
- `README.md` → Project documentation  

---

## 🛠 Tools & Libraries
- SQLite (via Python `sqlite3`)  
- SQL (GROUP BY, SUM, COUNT, ORDER BY)  
- Pandas  
- Matplotlib  

---

## 🔍 Steps Performed
1. Created a sample sales dataset (`orders` table).  
2. Wrote SQL queries to calculate:  
   - **Monthly revenue** → `SUM(amount)`  
   - **Monthly order volume** → `COUNT(DISTINCT order_id)`  
3. Grouped results by year and month.  
4. Ordered results chronologically.  
5. Visualized revenue and volume trends with bar charts.  

---

## 📊 Example Results

| year | month | total_revenue | order_volume |
|------|-------|---------------|--------------|
| 2023 | 1     | 350           | 2            |
| 2023 | 2     | 550           | 2            |
| 2023 | 3     | 1000          | 3            |

---

## 📈 Visualizations
- **Monthly Revenue Trend (Bar Chart)**  
- **Monthly Order Volume Trend (Bar Chart)**  

---

## ✅ Outcome
By completing this task, we learned:
- How to group data by **year and month** in SQL  
- How to use `SUM()` and `COUNT(DISTINCT ...)` for aggregations  
- How to run SQL inside Python using `sqlite3` and Pandas  
- How to create simple bar charts to show trends  

---

## 💡 Learning Takeaways
- SQL date functions (`strftime` in SQLite, `EXTRACT` in PostgreSQL/MySQL)  
- Aggregation and grouping techniques  
- Combining SQL with Python for business analysis  
- Trend analysis using visualization  

