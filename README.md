# HR-Analytics👩🏻‍💼

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

###📊 Key Outcomes
- Processed 1.4K+ employee records to identify high-risk attrition segments.
- Reduced reporting time by 80% with automated Power BI updates.
- Enhanced HR decision-making with data-backed attrition and performance trends.

### 🖼️Power BI Dashboard

Below is a screenshot of the Power BI dashboard for Bank Churn Analysis:

<img width="918" height="518" alt="HR_Analytics Dashboard" src="https://github.com/user-attachments/assets/85843217-708a-482d-af93-50fda1253832" />
