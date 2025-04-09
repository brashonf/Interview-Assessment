# 📊 SAP Asset Utilization & Forecasting – Data Science Interview Case Study

## 👋 Overview

This project was completed as part of a data science interview assignment. The task involved analyzing datasets related to asset usage, schedule, and status to uncover operational insights and forecast utilization patterns.

---

## 🔍 Business Problem

**How does asset utilization vary across facilities, and what factors contribute to higher or lower efficiency?**

The objective was to identify overutilized or underutilized assets and determine patterns in lifecycle status, usage cycles, and overall facility performance.

---

## 📁 Data Description

- `Cycles.csv`: 37,514 records of asset cycle activity  
- `StatusCodes.csv`: 1,146 records of asset status over time  
- `Schedule.csv`: 594 records with planned start/end times

Key variables:
- `SerialNo`, `Facility`, `Status Code`, `Usage Hours`, `Date`

---

## 🧹 Data Cleaning & Preprocessing

- Standardized date formats
- Joined datasets using `SerialNo` and `Facility`
- Assumed status persists until the next timestamped record
- Filtered and structured data to analyze per-asset and per-facility behavior

---

## 📈 Key Metrics & Analysis

- **Utilization Analysis**:
  - Cycle count and total usage hours per asset
  - Detection of **overutilized** and **underutilized** assets
  
- **Lifecycle Status Analysis**:
  - Time spent in each status (e.g., Active, Maintenance)
  - Transitions across states by facility and asset

- **Facility Trends**:
  - Aggregate usage by facility
  - Time-series analysis to detect seasonal patterns

---

## 🔎 Key Insights

- Certain assets are **overworked**, indicating a need to redistribute workload.
- **Underutilized assets** represent an opportunity to balance capacity and improve ROI.
- Facilities show varying patterns in usage trends and maintenance cycles.

---

## 📊 Visualizations (from Jupyter notebook)



## ✅ Next Steps

- Implement predictive models to forecast future utilization
- Optimize maintenance scheduling based on status transition timing
- Recommend asset reallocation strategies

---

## 💻 Technologies Used

- Python (pandas, seaborn, matplotlib, statsmodels)
- Jupyter Notebook
- PowerPoint (for initial slide presentation)

---

## 📄 License

This project is licensed under the MIT License.



