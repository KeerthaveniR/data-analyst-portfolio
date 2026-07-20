Medical Data History Analysis

Overview
SQL-based analysis of hospital records using MySQL, applying joins, aggregations, GROUP BY, NULL handling, and date functions to solve real-world data analysis problems.

Dataset
- 4,500+ hospital records
- 4 relational tables: `patients`, `admissions`, `doctors`, `province_names`

What I Did
- Queried patient, admission, and province data to extract insights on patient demographics, admission patterns, and allergy trends
- Applied joins, aggregations, GROUP BY, NULL handling, and date functions across the dataset

Key Findings
- 45% missing allergy data — identified significant gaps in the `allergies` column within the `patients` table, supporting data quality checks and reporting
- 481 same-day admissions flagged — surfaced records requiring operational review

Files in this folder
- medical_data_history — queries used (Word file)
- medical_data_history — analysis report (PDF file)
- medical_data_history — SQL file

Tools
MySQL, SQL
