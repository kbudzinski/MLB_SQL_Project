# 💸 MLB Spending vs Performance Analysis

**Author:** Kevin Budzinski  
**Tableau Dashboard:** [MLB Spending Performance](https://public.tableau.com/app/profile/kevin.budzinski/viz/mlbworkbook/MLBSpendingPerformance)

---

## 📊 Overview

This project explores the relationship between MLB team payrolls and on-field performance from 2019 to 2023. Using SQL for analysis and Tableau for visualization, I compared team spending to success metrics like wins, run differential, and fan attendance.

---

## 🗃️ Data Sources

- **Team performance data**: Lahman Baseball Database (imported from CSV)
- **Payroll data**: Compiled manually from public MLB financial reports (2019–2023)

The data was analyzed in SQL and exported to CSV files, which were then used separately in Tableau to build the dashboard.

---

## 🧮 SQL Analysis

All insights were generated using SQL queries, including:

- League and division average payrolls  
- Payroll vs league/division averages  
- Win percentage and wins vs league average  
- Cost per win, cost per run, and wins per dollar  
- Attendance efficiency

### 📂 SQL Files

- `clean_data.sql` – Data import and cleaning  
- `mlb_metrics.sql` – Analytical queries

---

## 📈 Tableau Dashboard

The Tableau dashboard was built using CSVs exported from SQL. It includes:

- Filters by Year, League, and Division  
- Scatter plot of Wins vs Payroll  
- Trend line for average performance  
- KPIs like Cost per Win and Wins per Dollar  
- League and division comparisons

🔗 [**Explore the Dashboard**](https://public.tableau.com/app/profile/kevin.budzinski/viz/mlbworkbook/MLBSpendingPerformance)

---

## 🛠️ Tools Used

- **SQL (MySQL Workbench)** – Data analysis and transformation  
- **Tableau Public** – Visualization using exported CSVs  
- **Excel/Google Sheets** – CSV cleanup and formatting

---

## 📌 Key Takeaways

- High payroll doesn’t guarantee wins  
- Some teams consistently outperform their spending levels  
- Cost-efficiency varies widely across teams and seasons

---

## 📥 How to Recreate

1. Import Lahman team data and payroll data into MySQL  
2. Run queries from `mlb_metrics.sql` to generate insights  
3. Export query results to CSV  
4. Load CSVs into Tableau for visualization (no live DB connection used)

---

## 📧 Contact

Have questions or want to collaborate?

📧 kevinbudzinski54@gmail.com  
🔗 [Tableau Public Profile](https://public.tableau.com/app/profile/kevin.budzinski)

