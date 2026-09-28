# 🏗️ Lakehouse Structure — Project 2

This document describes the Lakehouse structure for Portfolio Project 2, including folder organization, tables, and medallion layer design.

---

## 📁 Lakehouse Layout

Lakehouse/ Files/
- Bronze/
- Silver/
- Gold/

└── Tables/
- BronzeTables
-  SilverTables
- GoldTables


---

## 🥉 Bronze Layer

- Raw CSV ingestion  
- No transformations  
- Stored in `/Files/Bronze/`  

---

## 🥈 Silver Layer

- Cleaned and standardized datasets  
- Column renaming  
- Data type corrections  
- Stored in `/Files/Silver/`  

---

## 🥇 Gold Layer

- Aggregated business-ready analytics  
- Measures and KPIs  
- Stored in `/Files/Gold/`  

---

## 🔗 SQL Endpoint

The Lakehouse SQL Endpoint is used for Power BI connectivity and Gold layer validation.
