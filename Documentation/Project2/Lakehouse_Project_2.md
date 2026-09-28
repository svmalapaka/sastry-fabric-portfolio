# 🏗️ Lakehouse Structure — Project 2

This document describes the Lakehouse structure for Portfolio Project 2, including folder organization, tables, and medallion layer design.

---

## 📁 Lakehouse Layout

Lakehouse

Files/
- Bronze/
- Silver/
- Gold/

Tables/
- BronzeTables
-  SilverTables
- GoldTables


---

## 🥉 Bronze Layer — Raw Data Ingestion

- Raw CSV ingestion  
- No transformations  
- Stored in `/Files/Bronze/`  
- Dataset: `HR_Employee_Data.csv`  
- Purpose: Load raw HR employee data into the Lakehouse for downstream Silver transformations  

### 📸 Bronze Screenshot
![Bronze HR Employee Data Preview](../../Screenshots/Project2/Bronze/Bronze_HR_Employee_Data_Preview.png)

---



## 🥈 Silver Layer — Data Cleaning & Standardization

- Source: Bronze layer (`HR_Employee_Data.csv`)
- Apply column standardization  
- Convert data types (dates, integers, booleans)  
- Normalize categorical values (Gender, Attrition, Overtime)  
- Remove nulls and inconsistent values  
- Store cleaned data in `/Files/Silver/`  
- Output Table: `Silver_HR_Employee_Data`

### 📸 Silver Screenshot
![Silver HR Employee Data Preview](../../Screenshots/Project2/Silver/Silver_HR_Employee_Data_Preview.png)

---


## 🥇 Gold Layer

- Aggregated business-ready analytics  
- Measures and KPIs  
- Stored in `/Files/Gold/`  

---

## 🔗 SQL Endpoint

The Lakehouse SQL Endpoint is used for Power BI connectivity and Gold layer validation.
