# 👩🏻‍💼HR Analytics Dashboard – Employee Attrition Analysis

_Data-driven analysis of employee attrition to uncover workforce risk areas, improve retention strategies, and support HR decision-making using Python and Power BI._

---
## 📌 Table of Contents
- [Overview](#overview)  
- [Business Problem](#business-problem)  
- [Dataset](#dataset)  
- [Tools & Technologies](#tools--technologies)  
- [Project Structure](#project-structure)  
- [Data Cleaning & Preparation](#data-cleaning--preparation)  
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)  
- [Research Questions & Key Findings](#research-questions--key-findings)  
- [Dashboard](#dashboard)  
- [Final Recommendations](#final-recommendations)  

---

## Overview

This project focuses on analyzing employee attrition using HR data to identify at-risk employee groups, uncover retention drivers, and provide actionable insights for human resource strategy.  

Using Python for data processing and Power BI for visualization, this project converts raw HR data into strategic insights that support workforce planning, employee engagement, and operational improvements.

The final output includes:
- A cleaned and transformed dataset  
- Exploratory analysis using Python  
- Interactive Power BI dashboard  
- Business-ready insights and recommendations  

---

## Business Problem

Employee attrition increases hiring costs, disrupts productivity, and weakens organizational stability.  
The company is experiencing an overall attrition rate of approximately **16%**, but attrition is not evenly distributed.

Key issues include:
- Certain job roles losing employees at a significantly higher rate
- Early-tenure employees leaving within their first two years
- Overtime strongly correlating with attrition
- Higher salaries not guaranteeing better retention
- Younger employees resigning faster than senior age groups

The business needs a **data-driven approach** to understand:
- Who is leaving  
- Why they are leaving  
- Where retention actions should be focused  

---

## Dataset

### Source
Internal HR dataset provided as:
- `HR_Analytics.csv` (raw data)
- `cleaned_dataset.csv` (processed version for analysis)

### Size
- **1,470 employee records**

### Key Columns
- `Age`, `AgeGroup` — employee age and categories  
- `Attrition`, `Attrition_Flag` — attrition status  
- `Department`, `JobRole` — organizational roles  
- `MonthlyIncome` — income level  
- `YearsAtCompany` — tenure  
- `OverTime` — employee workload indicator  
- `PerformanceLevel` — job performance  
- `TenureCategory`, `IncomeCategory` — derived fields

---

## Tools & Technologies

- **Python**
  - Pandas (data manipulation)
  - NumPy (calculations)
- **Power BI**
  - DAX
  - Interactive BI visuals
- **Excel**
  - Primary inspection and validation
 
---

## Project Structure

```
HR Analytics Dashboard/
│
├── notebooks/                  # Jupyter notebooks
│   ├── Python_HR_Analytics.ipynb
│
├── data/                     # CSV Files
│   ├── HR_Analytics.csv
│   └── cleaned_dataset.csv
│
├── Power BI Dashboard/                  # Power BI dashboard file
│   └── HR_Analytics.pbix
│
├── Reports/                   
│   └── HR Analytics Reports.pdf
├── README.md

```

---

## Data Cleaning & Preparation

Steps applied to transform the raw dataset into analyzable form:

- Removed duplicate records  
- Standardized categorical values (e.g., Overtime, JobRole)  
- Corrected column formats  
- Addressed missing or invalid values  
- Created new features:
  - Age group classification  
  - Tenure buckets  
  - Income categories  
  - Binary attrition flag  
- Verified column consistency across both datasets  

---

## Exploratory Data Analysis (EDA)

Key observations from exploratory analysis:

- Attrition is concentrated early in employee tenure  
- Young employees show the highest exit rate  
- Salary correlates only weakly with attrition  
- Overtime has a strong relationship with employee exits  
- Sales department employees earn more but leave more  
- Performance rating is not a reliable retention indicator  

---

## Research Questions & Key Findings

### 1. What is the attrition rate?
- **16.12% overall attrition**

### 2. Which roles have the highest attrition?
- Sales Representatives (~40%)
- Laboratory Technicians  
- HR roles  

### 3. Does age affect attrition?
- Highest attrition in **18–25** age group

### 4. Does experience matter?
- Employees with **<2 years** tenure leave the most

### 5. Does overtime influence attrition?
- Yes: Overtime employees leave at **3× higher** rate

### 6. Does higher income prevent attrition?
- No — Sales department earns more and leaves more

### 7. Do poor performers quit more?
- No — Good and Excellent performers show similar exit rates

---

## Dashboard

The Power BI dashboard provides a complete visual summary of attrition behavior with:

- KPI cards:
  - Total employees
  - Attrition rate
  - Avg Year at company
  - Monthly income
- Attrition by:
  - Department
  - Job role
  - Performance level
  - Year at company
- Workload analysis:
  - Overtime vs attrition
- Demographics:
  - Age group analysis
  - Gender distribution

Dashboard file:  
📁 <img width="918" height="518" alt="HR_Analytics Dashboard" src="https://github.com/komalb30/HR-Analytics/blob/main/dashboard/HR_Analytics.png" />


## Final Recommendations
### Focus Areas
- Fix early-stage attrition through stronger onboarding programs
- Reduce overtime and rebalance workloads
- Redesign Sales incentives and expectations
- Introduce targeted retention programs for high-risk roles
- Implement predictive attrition modeling
- Track attrition monthly and by tenure group

