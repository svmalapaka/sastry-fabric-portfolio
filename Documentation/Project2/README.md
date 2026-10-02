# 📘 Portfolio Project 2 — Real-Time Analytics & Medallion Lakehouse

Portfolio Project 2 demonstrates a second end-to-end Microsoft Fabric implementation, expanding on Project 1 with new datasets, transformations, real-time components, and enhanced reporting logic. This project showcases how Fabric’s Lakehouse, Medallion architecture, pipelines, SQL Endpoint, and Power BI integrate to deliver scalable analytics.

---

## 🏗️ Project Summary

This project builds a complete Medallion pipeline using:

- **Bronze → Silver → Gold** data layers  
- **Lakehouse storage** with `/Files` and `/Tables`  
- **Fabric Pipelines** for ingestion, cleaning, and analytics  
- **SQL Endpoint** for semantic modeling and reporting  
- **Power BI** for Gold-layer validation and insights  

Project 2 extends the architecture from Project 1 by introducing additional datasets, transformations, and reporting logic.

---

## 🧱 Architecture Overview

### 🥉 Bronze Layer  
Raw ingestion of source files into the Lakehouse.  
No transformations — schema is preserved exactly as received.

### 🥈 Silver Layer  
Cleaned, standardized, and enriched datasets:  
- Column renaming  
- Data type corrections  
- Null handling  
- Basic transformations  

### 🥇 Gold Layer  
Business-ready analytics:  
- Aggregations  
- KPI calculations  
- Reporting tables  
- SQL Endpoint views for Power BI  

### 🏗️ Lakehouse Structure  
The Lakehouse is organized into:

```
Lakehouse/
│
├── Files/
│   ├── Bronze/
│   ├── Silver/
│   └── Gold/
│
└── Tables/
    ├── BronzeTables
    ├── SilverTables
    └── GoldTables
```

### 🔄 Pipelines  
Three pipelines orchestrate the Medallion flow:

- **Bronze Pipeline** — ingestion  
- **Silver Pipeline** — transformation  
- **Gold Pipeline** — analytics  
- *(Optional)* Unified pipeline running Bronze → Silver → Gold sequentially  

### 📊 Power BI  
The Power BI report includes:

- Gold validation matrix  
- Category-level breakdown  
- SQL Endpoint connectivity  
- KPI summaries  

---

## 📁 Repository Structure

```
Documentation/
│
└── Project2/
    ├── Project_2_Overview.md
    ├── Lakehouse_Project_2.md
    ├── Pipelines_Project_2.md
    └── PowerBI_Project_2.md

Code/
```

Each markdown file provides deep-dive documentation:

- **Lakehouse_Project_2.md** — structure, tables, medallion layers  
- **Pipelines_Project_2.md** — pipeline logic, screenshots, flow diagrams  
- **PowerBI_Project_2.md** — report pages, visuals, SQL Endpoint integration  

---

## 🎯 Purpose of This Overview

This overview serves as:

- A quick introduction for recruiters  
- A navigation guide for GitHub visitors  
- A summary of the project’s architecture  
- A reference point before exploring detailed documentation  

---

## ✔ Summary

Portfolio Project 2 demonstrates how Microsoft Fabric can scale beyond a single dataset or pipeline, integrating multiple layers, transformations, and reporting components into a unified analytics system.

This project builds on the foundation of Project 1 and continues expanding your Fabric portfolio with real-time analytics, advanced transformations, and richer reporting.

