# Task 6: Sales Trend Analysis Using SQL

## Tools Used
- MySQL Workbench
- SQL (Structured Query Language)
- Dataset: `online_sales_sample.csv`

---

##  Steps Followed
1. Created a new database: `sales_insights`
2. Imported the CSV file into a table: `online_sales_sample`
3. Used SQL queries with:
   - `EXTRACT()` to get month and year
   - `SUM()` for revenue
   - `COUNT(DISTINCT)` for order volume
   - `GROUP BY`, `ORDER BY`, `LIMIT` for aggregation and sorting
4. Generated and saved result outputs

---

##  Key Findings
- Monthly sales trends show variations in revenue and order volume
- Identified the **top 3 highest revenue months**
- Demonstrated the use of SQL for business trend analysis

---

## Files Included
- `task6.sql` – SQL script with all queries
- `online_sales_sample.csv` – Dataset used for analysis
- `monthly_revenue_order_volume.png` – Result of monthly trend query
- `top_3_months_by_revenue.png` – Result of top 3 revenue months query
