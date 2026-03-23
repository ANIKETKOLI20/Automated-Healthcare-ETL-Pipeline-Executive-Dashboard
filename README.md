# 🏥 Automated Healthcare ETL Pipeline & Executive Dashboard

---

## 📌 Project Overview

This project demonstrates an **end-to-end ETL pipeline** built using Excel to process raw healthcare patient data and generate an **executive dashboard**.

The project focuses on improving **data quality, transparency, and insight generation** by implementing structured steps such as cleaning, deduplication, error tracking, and audit logging.

---

## 🚨 Problem Statement

Healthcare datasets often contain:

* Duplicate patient records
* Missing or unclear values ("Not Provided")
* Inconsistent formatting
* Lack of structured reporting

These issues reduce data reliability and make analysis inaccurate.

---

## 🧠 Ask Phase (Google Data Analytics)

### 🔍 Business Task

To improve the quality of healthcare patient data and generate insights that help in understanding patient conditions, treatment patterns, and overall data reliability.

---

### ❓ Key Questions (SMART Thinking)

* Can we identify how much of the dataset is unreliable (duplicate or incorrect records) and reduce it before analysis?

* Which medical conditions and medications appear most frequently, and how can this help in understanding treatment patterns?

* How do health indicators like blood pressure differ across conditions, and can this highlight higher-risk groups?

* Are there any noticeable differences based on gender or age that can help in basic segmentation?

* Can we systematically track data issues (missing values, inconsistencies) to make the cleaning process transparent?

* Can we build a simple dashboard that summarizes key metrics for quick decision-making?

👉 These questions guided the design of the ETL pipeline and dashboard.

---

## 🎯 Objective

* Clean and standardize healthcare data
* Remove duplicate records and measure deduplication rate
* Build a structured ETL workflow
* Track errors and transformations
* Generate insights and KPIs
* Create an executive dashboard

---

## ⚙️ ETL Pipeline Architecture

Raw Data → Data Cleaning → Deduplication → Error Log → Audit Log → Clean Data → Dashboard

---

## 📂 Project Structure

| File / Sheet           | Description                            |
| ---------------------- | -------------------------------------- |
| `01_raw_data`          | Original dataset                       |
| `02_clean_data`        | Cleaned and transformed dataset        |
| `03_error_log`         | Records with errors or inconsistencies |
| `04_audit_log`         | Tracks ETL steps and transformations   |
| `05_data_dictionary`   | Metadata and column definitions        |
| `06_executive_summary` | Final dashboard                        |

---

## 🔍 Key Features

* Data Cleaning & Standardization
* Deduplication (76% duplicate records removed)
* Error Logging System
* Audit Logging for transparency
* KPI Calculation
* Executive Dashboard

---

## 📊 Dashboard Highlights

* Total Patients Processed: **47**
* Deduplication Rate: **76%**

### Insights:

* Common medications: Metformin, Lisinopril, Albuterol
* Key conditions: Diabetes, Hypertension, Heart Disease, Asthma
* Higher BP trends in Hypertension & Heart Disease
* Balanced gender distribution

---

## 🧠 Data Quality Framework

* Cleaning Layer → `02_clean_data`
* Error Tracking → `03_error_log`
* Audit Trail → `04_audit_log`
* Metadata → `05_data_dictionary`

---

## 📄 Scope of Work (SOW)

### **Purpose**

To design a structured ETL pipeline that processes raw healthcare data into a clean, analysis-ready dataset and delivers insights through an executive dashboard.

---

### **Scope / Major Activities**

* Data ingestion from raw dataset
* Data cleaning and standardization
* Deduplication of patient records
* Error logging for invalid entries
* Audit logging for tracking transformations
* Data aggregation and KPI generation
* Dashboard creation

---

### **Out of Scope**

* Real-time data processing
* Integration with hospital systems
* Machine learning models
* Handling sensitive real-world patient data

---

### **Deliverables**

* Clean dataset
* Error log
* Audit log
* Data dictionary
* Executive dashboard
* Insights summary

---

## 📈 Project Outcome

* Converted raw data into **analysis-ready dataset**
* Identified major issue: **76% duplicate records**
* Built a structured ETL workflow
* Delivered actionable insights through dashboard

---

## ⚠️ Limitations

* Small dataset (47 records)
* Excel-based pipeline (limited automation)

---

## 🚀 Future Improvements

* Rebuild ETL pipeline using **Python (Pandas)**
* Store data in **SQL database**
* Create dashboard in **Power BI**
* Automate pipeline execution
* Use larger dataset for real-world simulation

---

## Screenshot

## 👨‍💻 Author

Aniket Koli
Aspiring Data Analyst

---
