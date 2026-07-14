# 👨‍💼 HR Analytics Dashboard | Power BI

> **An interactive HR Analytics Dashboard built using Microsoft Power BI to monitor employee attrition, workforce demographics, job roles, salary distribution, education background, and key HR metrics through dynamic and interactive visualizations.**

---

## 📑 Table of Contents

- Project Overview
- Business Problem
- Business Objectives
- Dashboard KPIs
- Dashboard Features
- Dashboard Visualizations
- Interactive Filters
- Data Cleaning & Transformation
- Data Modeling
- DAX Measures
- Key Business Insights
- Tools & Technologies
- Project Structure
- Future Enhancements
- Dashboard Preview
- Author

---

# 📖 Project Overview

Human Resource departments generate a significant amount of employee-related data. However, transforming this raw data into meaningful insights is often challenging.

This **HR Analytics Dashboard** was developed using **Microsoft Power BI** to provide HR managers and business leaders with a centralized platform for monitoring employee attrition, workforce demographics, salary distribution, education background, job roles, and employee experience.

The dashboard enables organizations to make informed decisions regarding employee retention, workforce planning, and talent management through interactive data visualization.

---

# 🎯 Business Problem

Organizations often struggle to answer critical HR questions such as:

- Why are employees leaving?
- Which department has the highest attrition?
- Which salary group experiences the highest turnover?
- Which age group is most likely to leave?
- Which job roles require immediate attention?
- How do education backgrounds influence attrition?

Without proper visualization, identifying these trends becomes difficult.

---

# 🎯 Business Objectives

- Monitor employee attrition
- Analyze workforce demographics
- Understand salary distribution
- Compare education backgrounds
- Analyze department performance
- Evaluate job role attrition
- Identify employee retention opportunities
- Support HR decision-making using data

---

# 📊 Dashboard KPIs

| KPI | Value |
|------|------:|
| Total Employees | 1470 |
| Total Attrition | 237 |
| Attrition Rate | 16.12% |
| Average Age | 33.61 Years |
| Average Monthly Income | 6.50K |
| Average Years at Company | 7.01 Years |

---

# 🚀 Dashboard Features

✅ Executive KPI Cards

✅ Department Filter

✅ Employee Demographics

✅ Salary Analysis

✅ Job Role Analysis

✅ Education Analysis

✅ Attrition Trends

✅ Interactive Slicers

✅ Dynamic Charts

✅ Matrix Reports

---

# 📈 Dashboard Visualizations

## 1️⃣ KPI Cards

Displays the overall HR performance through:

- Total Employees
- Total Attrition
- Attrition Rate
- Average Age
- Average Monthly Income
- Average Years at Company

---

## 2️⃣ Attrition by Education Field

Visualizes employee attrition across education backgrounds.

Education Fields:

- Life Sciences
- Medical
- Marketing
- Technical Degree
- Human Resources
- Other

Purpose:

- Understand educational background of employees leaving the company.
- Improve recruitment strategy.

---

## 3️⃣ Attrition by Age Group

Displays attrition across different employee age groups.

Age Groups:

- 18–25
- 26–35
- 36–45
- 46–55
- 55+

Purpose:

- Identify high-risk age groups.
- Improve retention strategy.

---

## 4️⃣ Attrition by Job Role

Compares employee attrition across various job roles.

Example Roles:

- Laboratory Technician
- Sales Executive
- Research Scientist
- Healthcare Representative
- Manager
- Research Director

Purpose:

- Identify departments requiring immediate HR attention.

---

## 5️⃣ Attrition by Years at Company

Displays attrition trends based on employee tenure.

Purpose:

- Understand employee lifecycle.
- Identify critical resignation periods.

---

## 6️⃣ Attrition by Salary Slab

Analyzes employee attrition across salary ranges.

Salary Groups:

- Up to 5K
- 5K–10K
- 10K–15K
- 15K+

Purpose:

- Understand the impact of salary on employee turnover.

---

## 7️⃣ Gender-wise Attrition

Displays employee attrition based on gender.

Purpose:

- Workforce diversity analysis.
- Gender-specific HR insights.

---

## 8️⃣ Job Role Matrix

Provides a detailed comparison of employees across job roles and performance metrics.

Purpose:

- Department-level reporting
- Workforce planning
- Detailed HR reporting

---

# 🎛 Interactive Filters

Users can dynamically analyze data using:

- Department
- Human Resources
- Research & Development
- Sales

These slicers automatically update all dashboard visuals.

---

# 🧹 Data Cleaning & Transformation

The dataset was cleaned and transformed using **Power Query**.

### Cleaning Steps

- Removed duplicate records
- Corrected inconsistent values
- Standardized department names
- Changed data types
- Removed unnecessary columns
- Handled missing values
- Optimized data model

---

# 🔗 Data Modeling

The dashboard uses a star-schema model with relationships built between employee dimensions and HR fact tables to improve query performance and reporting efficiency.

---

# 📐 DAX Measures

```DAX
Total Employees =
COUNT(Employee[EmpID])

Total Attrition =
CALCULATE(
COUNT(Employee[Attrition]),
Employee[Attrition]="Yes"
)

Attrition Rate =
DIVIDE(
[Total Attrition],
[Total Employees]
)

Average Age =
AVERAGE(Employee[Age])

Average Monthly Income =
AVERAGE(Employee[MonthlyIncome])

Average Years at Company =
AVERAGE(Employee[YearsAtCompany])
```

---

# 💡 Key Business Insights

### Employee Attrition

- Total employees: **1470**
- Employees left: **237**
- Overall attrition rate: **16.12%**

---

### Workforce Demographics

- Average employee age is **33.61 years**.
- Majority of employees belong to the **26–35 years** age group.

---

### Salary Analysis

- Employees earning **Up to 5K** show the highest attrition.
- Higher salary groups demonstrate better retention.

---

### Education Analysis

- Employees from **Life Sciences** contribute the highest attrition.
- Medical background employees represent the second-largest group.

---

### Job Role Analysis

Highest employee attrition observed among:

- Laboratory Technician
- Sales Executive
- Research Scientist

These roles may require improved retention strategies.

---

### Employee Experience

Attrition tends to be higher during the early years of employment, indicating a need for stronger onboarding and engagement programs.

---

# 🛠 Tools & Technologies

| Tool | Purpose |
|------|---------|
| Microsoft Power BI | Dashboard Development |
| Power Query | Data Cleaning |
| DAX | KPI Calculations |
| Excel / CSV | Data Source |
| Data Modeling | Relationships |

---

# 📂 Project Structure

```
HR-Analytics-Dashboard
│
├── Dashboard.pbix
├── HR_Data.xlsx
├── Dashboard.png
├── README.md
└── Assets
```

---

# 🚀 Future Enhancements

- Employee Performance Dashboard
- Recruitment Analytics
- Leave Management Dashboard
- Diversity & Inclusion Dashboard
- Predictive Attrition Analysis
- AI Visuals
- Drill-through Reports
- Mobile Layout
- HR Scorecard

---

# 📷 Dashboard Preview

> Place your dashboard screenshot inside the repository and rename it as **Dashboard.png**
>
> <img width="1300" height="732" alt="image" src="https://github.com/user-attachments/assets/b0ca7758-abd1-4061-9e93-36d7b3a2ceae" />


---

# ⭐ Project Highlights

- Interactive HR Dashboard
- Professional UI Design
- Data Cleaning using Power Query
- Dynamic DAX Measures
- Employee Attrition Analysis
- Workforce Demographics
- Salary Distribution
- Department-wise Analysis
- Interactive Slicers
- Business Insights

---

# 👨‍💻 Author

## Abhishek Sharma

**Aspiring Data Analyst**

### Technical Skills

- Microsoft Power BI
- SQL
- Python
- Excel
- Power Query
- DAX
- Data Cleaning
- Data Visualization
- Business Intelligence

---

## ⭐ If you found this project useful, consider giving it a Star on GitHub.
