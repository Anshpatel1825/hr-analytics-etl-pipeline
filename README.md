# 🚀 HR Analytics End-to-End Data Engineering Pipeline

## 📌 Project Overview
This project is a complete end-to-end data engineering pipeline built using Python, MySQL, Apache Airflow, and Power BI.

The goal of this project is to process raw HR employee data, transform it into meaningful insights, store it in a database, and visualize it using an interactive dashboard.

---

## 🧠 Problem Statement
Organizations often have raw employee data but lack insights such as:
- Why employees leave (attrition)
- Which employees are at high risk
- Impact of salary, experience, and promotion on attrition

This project solves that problem by building a complete data pipeline.

---

## 🏗️ Architecture
- Raw CSV Data
  - ↓
- Python ETL (Cleaning + Feature Engineering)
  - ↓
- Clean Data CSV
  - ↓
- MySQL Database
  - ↓
Apache Airflow (




---

## ⚙️ Tech Stack

- Python (Pandas, NumPy)
- MySQL
- Apache Airflow
- Power BI
- Ubuntu (Linux)

---

## 🔄 ETL Process

### 1. Data Ingestion
- Loaded raw HR dataset (10,000 rows, 26 columns)

### 2. Data Cleaning
- Removed duplicates
- Fixed data types
- Checked missing values

### 3. Feature Engineering
Created new business columns:

- **Income_Category**
  - Low (<5000)
  - Medium (5000–15000)
  - High (>15000)

- **Experience_Level**
  - Junior (<3 years)
  - Mid (3–7 years)
  - Senior (>7 years)

- **Promotion_Status**
  - No Promotion (≥5 years)
  - Recently Promoted (<5 years)

- **Risk_Flag**
  - High Risk employees identified using:
    - Attrition
    - Low satisfaction
    - No promotion
    - Low involvement

### 4. Data Storage
- Saved clean data as CSV
- Loaded data into MySQL database

---

## ⏱️ Automation (Apache Airflow)

- Created DAG to automate ETL process
- Scheduled pipeline to run daily
- Fully automated data pipeline

---

## 📊 Dashboard (Power BI)

Created an interactive HR Analytics Dashboard with:

### 🔹 KPIs
- Total Employees: 10,000
- Total Attrition: 2,000
- Attrition Rate: 20%
- High Risk Employees: 3,000

### 🔹 Visualizations
- Income Category Analysis
- Job Role Attrition
- Department-wise Attrition
- Promotion Impact
- Experience vs Attrition
- Risk Distribution

### 🔹 Filters
- Department
- Gender
- Experience Level
- Income Category

---

## 🔁 Real-Time Flow

- Airflow runs ETL daily
- MySQL updates automatically
- Power BI dashboard refreshes data

👉 Result: **Live and automated analytics system**

---

## 💼 Business Impact

- Identifies high-risk employees
- Helps HR take preventive actions
- Improves employee retention
- Supports data-driven decisions

---

## 📸 Dashboard Preview

(Add your dashboard screenshots here)

---

## 🚀 How to Run

1. Clone repository
2. Create virtual environment
3. Install dependencies
4. Run Python ETL script
5. Setup MySQL database
6. Start Airflow
7. Run DAG
8. Connect Power BI to MySQL

---

## 🧑‍💻 Author

**Ansh Patel**

---

## ⭐ Key Highlights

✔ End-to-End Pipeline  
✔ Real-time Automation  
✔ Business-driven Features  
✔ Production-like Architecture  
✔ Interview Ready Project  

---

## 📢 Final Note

This project demonstrates real-world data engineering workflow from raw data to business insights using modern tools.
Automation)
↓
Power BI Dashboard (Visualization)
