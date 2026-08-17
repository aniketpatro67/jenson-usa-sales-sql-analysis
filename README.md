# jenson-usa-sales-sql-analysis
SQL retail analysis project solving complex business questions on inventory, sales, customer behavior, and staff performance using CTEs and window functions.

# Jenson USA Sales & Inventory Analysis (SQL Project)

## 📌 Project Overview
**Jenson USA** is one of America's leading retailers specializing in bicycles, cycling components, accessories, and outdoor gear. This project analyzes transactional, customer, inventory, and staff data using SQL to solve 12 critical business problems and derive actionable operational insights.

---

## 🛠️ Tech Stack & Skills
* **Language / Database:** SQL (MySQL / PostgreSQL / T-SQL compatible)
* **Key SQL Concepts:**
  * **Window Functions:** `RANK() OVER()`, `ROW_NUMBER() OVER()`, `PARTITION BY`
  * **Common Table Expressions (CTEs):** Multi-level `WITH` clauses
  * **Subqueries:** Correlated subqueries and filtering using `EXISTS` / `NOT EXISTS`
  * **Complex Joins:** `INNER JOIN`, `LEFT JOIN`, `USING`
  * **Aggregations & Grouping:** `SUM()`, `AVG()`, `COUNT()`, `GROUP BY`, `HAVING`

---

## 🔍 Key Business Problems Solved
1. **Store Sales Performance:** Aggregated total product volume sold per retail store.
2. **Product Trajectory:** Calculated running/cumulative product sales volumes over time.
3. **Category Champions:** Ranked and extracted top revenue-generating items per category using `RANK()`.
4. **VIP Customer Identification:** Pinpointed highest-lifetime-spend customers for targeted retention.
5. **Pricing Boundaries:** Analyzed category price ceilings using correlated subqueries.
6. **Customer Loyalty:** Evaluated order frequencies per customer across different store locations.
7. **Staff Sales Inactivity:** Identified non-selling personnel using `NOT EXISTS` clauses.
8. **Top Movers:** Extracted top 3 highest-volume products.
9. **Price Distribution:** Computed statistical median product prices using analytical row indexing.
10. **Deadstock / Zero-Order Products:** Flagged unpurchased catalog items for inventory clearance.
11. **Staff Productivity Benchmarks:** Benchmarked employee performance against company averages.
12. **Cross-Category Buyers:** Filtered omnichannel customers purchasing across all store categories using `HAVING COUNT(DISTINCT)`.

---

## 📈 Strategic Business Insights
* **Inventory Optimization:** Identified unpurchased items to guide inventory clearance and catalog adjustments.
* **Customer Retention:** Located high-value and cross-category customers to build personalized loyalty programs.
* **Pricing Strategy:** Outlined pricing distribution and category ceilings to optimize promotional discounting.
* **Staff Performance:** Benchmarked store sales vs. staff activity to improve operational scheduling and training.

---

## 📁 Repository Contents
* `Jenson_USA_Milestone_Project.pdf` — Slide presentation detailing project methodology and findings.
