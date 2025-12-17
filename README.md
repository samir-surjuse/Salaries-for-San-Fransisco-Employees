# 🏙 San Francisco Employee Salary Analysis | Data Analytics Project

## 📌 Project Overview
This project analyzes government employee salary data from San Francisco using Python and Tableau.
The goal is to understand:

- How total salaries and benefits grow over years
- Which job titles receive highest benefits
- How overtime impacts total compensation
- Which employees consume maximum payroll budget
- Whether salary distribution shows inequality or outliers

This project demonstrates real-world data analysis, dashboard building, and business insights.

---

## 🧹 Data Cleaning (Python)
Key steps performed:

- Loaded `Total.csv` using Pandas
- Replaced missing values in salary fields with `0`
- Converted numeric fields to proper datatypes
- Verified distributions using `.describe()`
- Removed data inconsistencies (NaNs, negative values)
- Prepared columns for aggregation: After cleaning, the data became ready for Exploratory Data Analysis.

---

## 🔍 Exploratory Data Analysis (Python)

### ✔ Statistical Summary
Used:
- `df.describe()`
- `df.groupby()`
- `df.value_counts()`

### ✔ Questions Answered
- Which job titles earn more?
- Which roles depend heavily on overtime?
- Do benefits significantly increase salaries?
- Who are the highest-earning employees?
- Is yearly spending rising?

### ✔ EDA Metrics Calculated
- Yearly average salary benefits
- Job title-wise mean salaries
- Overtime pay concentration
- Employee-wise total benefits
- Salary distribution histogram

---

## 📊 Visualization (Tableau Dashboard)
Created visual dashboards including:

- 📈 **Avg Total Pay Benefits by Year**
- 🟩 **Top Job Titles by Avg Benefits**
- 🟦 **Overtime Pay Contribution by Job Title**
- 🟨 **Employee-wise Benefits Area Chart**
- 📉 **Total Benefit Distribution Chart**
- 🍩 **OT Breakdown Pie/Donut Chart**

These charts help leadership make budget decisions.

---

## 🔥 Key Insights

### 🟢 1. Salary Growth Trend
- Avg Total Pay Benefits increased consistently until **2016–2017**, then stabilized.

### 🔥 2. Overtime Dependency
Major roles drawing overtime:
- Transit Operators (largest OT pool)
- Firefighters
- Police Ranks

Overtime acts like a **second salary source**.

### 💰 3. High Paying Job Titles
Highest Avg Total Benefits:
- Sergeant
- Attorney
- Firefighter
- Deputy Sheriff

These job titles consistently top earnings.

### 🧑‍💼 4. Employee Budget Concentration
Few employees claimed **200K+** total benefits, indicating payroll concentration.

### 📉 5. Pay Distribution
Salary distribution is **right-skewed**, meaning:
- Very few high earners
- Majority mid-range salary

Indicates inequality in compensation.

---

## 🛠 Tools & Technologies
Programming:
- **Python (Pandas, NumPy, Matplotlib)**  

Analytics:
- **Exploratory Data Analysis (EDA)**  

Visualization:
- **Tableau Desktop / Tableau Public**  

Version Control:
- **Git & GitHub**

Dataset:
- `Total.csv` (employee salary & benefit records)

---

## 🖥 Dashboard Preview


Example:

---

## ✔ How to Run This Project
1. Clone the repo  
2. Open `notebooks/salary_analysis.ipynb`
3. Run all Python cells to reproduce metrics
4. Open Tableau to view dashboard
5. Review insights in the report

---

## 🧑‍💻 Author
Data Analyst Portfolio Project  
Includes Python, Tableau, Business Insights and Dashboarding

---

## ⭐ Final Note
This project highlights:
- Data cleaning
- Analytical thinking
- Visual storytelling
- Dashboard design
- Actionable business insights

Perfect for Data Analyst / Business Analyst resume projects.