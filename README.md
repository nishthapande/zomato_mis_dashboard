---

## 🗄️ Database Schema

6 relational tables imported into MySQL:

| Table | Description |
|-------|-------------|
| orders | 1.5L order records with date, amount, user, restaurant |
| restaurant | Restaurant details — name, city, cuisine, rating |
| users | 1L user profiles — age, gender, occupation |
| menu | Menu items with cuisine and price |
| food | Food item master with veg/non-veg flag |
| orders_type | Order type classification |

---

## 🛢️ SQL Analysis

All queries written in MySQL Workbench with JOIN operations across tables.

| # | Query | Insight |
|---|-------|---------|
| 1 | Revenue by City | Tirupati is #1 city (₹4.25 Cr) |
| 2 | Top 10 Restaurants | Janta Snacks leads with ₹15.1L |
| 3 | Monthly Revenue Trend | Peak in Nov 2017, decline post 2019 |
| 4 | Revenue by Occupation | Students drive 80,032 orders |
| 5 | Revenue by Cuisine | North Indian & Chinese is #1 |
| 6 | Avg Order Value by Gender | Female AOV slightly higher |

---

## 📊 Google Sheets Dashboard

5-tab workbook built in Google Sheets:

| Tab | Contents |
|-----|----------|
| RawData | Full orders dataset |
| SQL_outputs | All 6 query results with labels |
| PIVOT_analysis | Pivot table + VLOOKUP + INDEX MATCH |
| KPI_summary | Dynamic KPIs + bar and line charts |
| MIS_summary | Formatted weekly MIS report |

**Functions used:** VLOOKUP, INDEX MATCH, SUM, COUNTA,
Pivot Tables, Advanced Filters, Conditional Formatting

---

## 📋 Key Insights

- **Tirupati** generates highest revenue (₹4.25 Cr) despite only 243 orders
- **Electronic City, Bangalore** has highest order volume (1,039 orders)
- **Students** are the dominant segment driving 80,032 orders
- **North Indian & Chinese** cuisine is the top revenue category
- Revenue **peaked in Nov 2017** and shows a declining trend post 2019

---

## 📸 Dashboard Screenshots

| SQL Outputs | KPI Summary | MIS Report |
|-------------|-------------|------------|
| ![sql](screenshots/screenshot_sql_outputs.png) | ![kpi](screenshots/screenshot_kpi_summary.png) | ![mis](screenshots/screenshot_mis_summary.png) |

---

## 🛠️ Tools Used

- **MySQL Workbench** — database setup, joins, aggregations
- **Google Sheets** — pivot tables, VLOOKUP, INDEX MATCH, charts
- **Excel** — MIS report formatting
- **Python + SQLAlchemy** — bulk CSV import into MySQL
- **GitHub** — version control with phase-wise commits

---

## 👩‍💻 Author

**Nishtha Pande**
B.Tech Mechanical Engineering, NSUT Delhi (2024–2028)
📧 nishtha17.04.06@gmail.com
[GitHub](https://github.com/nishthapande)
