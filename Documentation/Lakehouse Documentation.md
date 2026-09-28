# Lakehouse Documentation — Sales Lakehouse Project

This document describes the Lakehouse structure, medallion layers, SQL endpoint, and data organization used in Portfolio Project #1.

---

## 🏗️ Lakehouse Structure

The Lakehouse follows a clean, modular medallion architecture:

- **Bronze Layer** — raw ingested CSVs
- **Silver Layer** — cleaned, standardized datasets
- **Gold Layer** — business-ready analytics
- **SQL Endpoint** — query-ready semantic layer for Power BI

---

## 📁 Folder Layout

Lakehouse/
│
├── Files/
│   ├── Bronze/
│   ├── Silver/
│   └── Gold/
│
└── Tables/
├── Bronze Tables
├── Silver Tables
└── Gold Tables

Code

---

## 🧱 Bronze Layer

- Raw CSVs ingested from the `/Files/Bronze` folder  
- No transformations  
- Used as the immutable source of truth  

---

## 🥈 Silver Layer

- Cleaned and standardized  
- Column types aligned  
- Null handling and formatting applied  
- Ready for Gold aggregations  

---

## 🥇 Gold Layer

- Aggregated analytics  
- Category-level sales  
- Revenue totals  
- Validation matrices  
- Used directly by Power BI  

---

## 🧩 SQL Endpoint

The Lakehouse SQL endpoint provides:

- Direct Power BI connectivity  
- Query-ready views  
- Consistent schema for reporting  