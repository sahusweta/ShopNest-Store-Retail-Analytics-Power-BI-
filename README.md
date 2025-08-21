# ShopNest-Store-Retail-Analytics-Power-BI-
# ShopNest Store Retail Analytics – Power BI

## 📅 Date
June 2025

## 📌 Objective
To analyze multi-source retail sales data and deliver actionable business insights using Power BI dashboards.

## 📊 Key Features
- Built an interactive dashboard displaying sales, profit trends, and performance metrics.
- Used Power Query to clean and transform the raw data.
- Implemented DAX measures and drill-through reports for deep analysis.
- Enabled fast decision-making with clear visuals.

## 🛠️ Tools & Technologies
- Power BI
- Power Query
- DAX (Data Analysis Expressions)

## 📈 Dashboard Preview
*(Insert screenshot here if available)*

## ✅ Outcomes
- Delivered clear, data-driven insights for business stakeholders.
- Improved understanding of data modeling and visual storytelling.
- Developed strong skills in Power BI and dashboard design.

## 🔗 File
- `ShopNest_Analytics.pbix` – [Include the .pbix file if available]

---

### 🔹 Project 3: Airline Database Management (SQL) – `README.md`

```markdown
# Airline Database Management – SQL

## 📅 Date
April 2025

## 📌 Objective
To design and query an airline database for generating operational and revenue reports efficiently.

## 🗂️ Key Features
- Created and queried tables for flight schedules, bookings, and revenue.
- Wrote SQL queries using joins, subqueries, and aggregate functions.
- Optimized query performance and improved report accuracy.

## 🛠️ Technologies Used
- SQL
- Relational Databases (MySQL / PostgreSQL / SQL Server)

## 📋 Example Queries
```sql
-- Total revenue by route
SELECT route, SUM(revenue) AS total_revenue
FROM bookings
GROUP BY route;

-- On-time flights report
SELECT flight_id, departure_time, arrival_time
FROM schedules
WHERE status = 'On-Time';
