# 👩🏻‍💼HR Analytics Dashboard – Employee Attrition Analysis

_Data-driven analysis of employee attrition to uncover workforce risk areas, improve retention strategies, and support HR decision-making using Python and Power BI._\
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
- [How to Run This Project](#how-to-run-this-project)  
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

























### 📊 Project Overview
This project is an end-to-end **HR Analytics Dashboard** built using **Python (Pandas, NumPy)** and **Power BI**.  
It provides deep insights into **employee attrition, performance, and workforce trends**, empowering HR teams to make data-driven decisions and reduce turnover.

### 🚀 Objectives
- Analyze employee attrition patterns and their key drivers.  
- Create an interactive Power BI dashboard for HR stakeholders.  
- Automate data cleaning and transformation using Python.  
- Identify improvement areas in employee engagement and retention.

### 🧰 Tech Stack
| Tool | Purpose |
|------|----------|
| **Python (Pandas, NumPy)** | Data cleaning & feature engineering |
| **Jupyter Notebook** | Data analysis workflow |
| **Power BI** | Visualization & dashboarding |
| **Excel / CSV** | Raw data source |

### 🧹 Data Preparation (Python)
1. **Loaded** the raw dataset (`1470 rows × 35 columns`) using Pandas.  
2. **Cleaned** redundant fields (`EmployeeCount`, `Over18`, `StandardHours`, `EmployeeNumber`).  
3. **Standardized** column names into `snake_case`.  
4. **Engineered features:**
   - `age_group`
   - `tenure_category`
   - `income_category`
   - `performance_level`
   - `attrition_flag` (binary target variable)  
5. **Exported** the cleaned data as `HR_Analytics_Cleaned_for_PowerBI.csv` for Power BI import.

### 📊 Key Outcomes
- Processed 1.4K+ employee records to identify high-risk attrition segments.
- Reduced reporting time by 80% with automated Power BI updates.
- Enhanced HR decision-making with data-backed attrition and performance trends.

### 🖼️Power BI Dashboard

Below is a screenshot of the Power BI dashboard for HR Analytics:

<img width="918" height="518" alt="HR_Analytics Dashboard" src="https://github.com/komalb30/HR-Analytics/blob/main/dashboard/HR_Analytics.png" />

