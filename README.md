# ConnectaTel Customer Usage Analysis
Telecom customer behavior analysis using Python. Includes data quality assessment, feature engineering, segmentation, statistical analysis, visualizations, and stakeholder-oriented insights.


## 📌 Project Overview

This project analyzes customer behavior for ConnectaTel, a telecommunications company operating in Latin America.

The objective is to understand how customers use mobile services (calls and text messages), identify usage patterns, detect outliers, segment customers, and generate actionable business insights to improve commercial strategies and customer experience.

---

## 📂 Datasets Used

The analysis is based on three datasets:

### plans.csv
Contains information about the available mobile plans:
- Plan name
- Monthly price
- Included minutes
- Included data
- Extra usage costs

### users_latam.csv
Contains customer information:
- User ID
- Age
- City
- Registration date
- Plan type
- Churn information

### usage.csv
Contains customer activity records:
- Calls
- Text messages
- Duration of calls
- Message length
- Activity dates

---

## 🔎 Analysis Process

The project was completed following these steps:

### 1. Data Exploration
- Loaded datasets
- Reviewed structure, dimensions, and data types

### 2. Data Quality Assessment
- Missing values analysis
- Sentinel value detection
- Invalid date detection

### 3. Data Cleaning
- Replaced sentinel values
- Corrected invalid dates
- Validated missing values according to business logic

### 4. User Behavior Aggregation
- Calculated:
  - Total messages
  - Total calls
  - Total call minutes
- Built a user-level analytical dataset

### 5. Exploratory Data Analysis
- Statistical summaries
- Histograms
- Distribution analysis

### 6. Outlier Detection
- Boxplots
- IQR method
- Business validation of extreme values

### 7. Customer Segmentation
- Segmentation by usage level
- Segmentation by age group

### 8. Executive Insights
- Business conclusions
- Recommendations for ConnectaTel stakeholders

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔁 Reproducibility Guide

To reproduce the analysis:

1. Download or clone this repository.
2. Obtain the original datasets used in the project.
3. Place the datasets in the paths referenced by the notebook.
4. Install the required Python libraries.
5. Execute all notebook cells sequentially.
6. Review the statistical analysis, visualizations, customer segmentation, and business recommendations.
   
---

## 👤 Author

Natalia García Pérez

Finance Reporting Analyst | Data Analytics | Business Intelligence

GitHub: https://github.com/nataliagp-finance-analyst
