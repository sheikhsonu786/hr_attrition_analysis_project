# HR Employee Attrition Analysis – Internship Project

This project was completed as part of the Data Analyst Internship at **Elevate Labs**.  
The goal was to analyze employee attrition data and derive meaningful insights through visual storytelling and machine learning using Python and Power BI.

---

## 📁 Dataset

Dataset used: `HR_Employee_Attrition.csv`  
Source: Kaggle – contains employee-level data with 35 columns like age, job role, monthly income, education, overtime, work-life balance, etc.

---

## 🎯 Project Objective

To understand the factors affecting employee attrition, build a predictive model, and design a clear and interactive HR Dashboard for business stakeholders.

---

## 🧰 Tools Used

- **Google Colab (Python)** – for data cleaning, EDA, modeling, and SHAP explainability  
- **Libraries**: Pandas, Seaborn, Matplotlib, Scikit-learn, SHAP  
- **Power BI Desktop** – for interactive dashboard design and storytelling  
- **GitHub** – for project version control and submission

---

## 🧪 Steps Involved

### 1. Data Cleaning & Preprocessing (Colab)
- Removed unnecessary columns like `Over18`, `StandardHours`, `EmployeeCount`
- Standardized column names (lowercase and underscores)
- Handled data types and verified null values

### 2. Exploratory Data Analysis (EDA)
- Created visuals for:
  - Attrition by gender, department, overtime
  - Monthly income distributions
  - Attrition vs. years at company
  - Correlation heatmap

### 3. Predictive Modeling
- Trained a **Logistic Regression model** to predict attrition
- Achieved **88% accuracy**
- Used **SHAP values** to interpret model predictions

### 4. Power BI Dashboard Design
Created a **2-page dashboard**:

#### 📄 Page 1: Overview
- KPIs: Total Employees, Attrition Rate, Avg Monthly Income, Avg Tenure  
- Donut chart: Attrition by Gender  
- Bar chart: Attrition by Department  
- Slicers: Department, Gender, Overtime

#### 📄 Page 2: Deep Dive
- Attrition % by Monthly Income  
- Environment Satisfaction vs. Attrition  
- Job Role vs. Attrition  
- Attrition Trend by Tenure

---

## 📊 Key Insights

- **Lower income & low satisfaction** strongly correlate with higher attrition
- Employees in **Lab Technician** and **Sales Rep** roles had the highest attrition
- **Most attrition happens within the first 2–4 years** of joining
- Employees doing **overtime** were more likely to leave

---

## 📝 Deliverables

- ✅ Cleaned Dataset (.csv)
- ✅ Python Notebook (.ipynb)
- ✅ SHAP Visuals
- ✅ Power BI Dashboard (.pdf)
- ✅ 2-Page Project Report

---

## 🙌 Acknowledgement

Thanks to **Elevate Labs** for providing this internship opportunity.  
This project enhanced my skills in **data analysis, visualization, machine learning**, and building **HR dashboards for strategic decision-making**.

---

## 📌 Project By: Sheikh Sonu  
📅 Completed: 4th July 2025  
🔗 [[GitHub Repository Link]](https://github.com/sheikhsonu786)
