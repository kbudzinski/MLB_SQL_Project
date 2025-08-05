# MLB_SQL_Project
💸 MLB Spending vs Performance Analysis
Author: Kevin Budzinski
Tableau Dashboard: MLB Spending Performance

📊 Overview
This project explores the relationship between MLB team payrolls and on-field performance from 2019 to 2023. Using SQL for analysis and Tableau for visualization, I compared team spending to success metrics like wins, run differential, and fan attendance.

🗃️ Data Sources
Team performance data: Lahman Baseball Database (imported from CSV)

Payroll data: Compiled manually from public MLB financial reports (2019–2023)

The data was analyzed in SQL and then exported to CSV files, which were used separately in Tableau to build the dashboard.

🧮 SQL Analysis
All insights were generated using SQL queries, including:

League and division average payrolls

Payroll vs league/division averages

Win percentage and wins vs league average

Cost per win, cost per run, and wins per dollar

Attendance efficiency

📂 SQL Files:

clean_data.sql: Data import and cleaning

mlb_metrics.sql: Analytical queries

📈 Tableau Dashboard
The Tableau dashboard was built using CSVs exported from the SQL queries. It features:

Filters by Year, League, and Division

Scatter plot of Wins vs Payroll

Trend line for average performance

KPIs like Cost per Win and Wins per Dollar

League and division comparisons

🔗 Explore Dashboard

🛠️ Tools Used
SQL (MySQL Workbench) – Data analysis and transformation

Tableau Public – Visualization using exported CSVs

Excel/Google Sheets – Basic formatting and prep of CSVs

📌 Key Takeaways
High payroll doesn’t guarantee wins.

Some teams consistently outperform their spending level.

Cost-efficiency varies widely across teams and seasons.

📥 How to Recreate
Import Lahman team data and compiled payrolls into MySQL.

Run queries from mlb_metrics.sql to generate insights.

Export relevant query results to CSV.

Import CSVs into Tableau and build visuals manually (no live DB connection used).

📧 Contact
Have questions or want to collaborate?

📧 kevinbudzinski54@gmail.com
🔗 Tableau Public

Let me know if you’d like me to generate this as a downloadable file or tweak anything else!
