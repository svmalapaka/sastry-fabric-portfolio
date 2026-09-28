# 🔄 Pipelines Documentation — Project 2

This document describes the ingestion and transformation pipelines used in Portfolio Project 2.

---

## 📥 Bronze Pipeline

**Purpose:**  
Ingest raw CSV files into the Bronze layer.

**Steps:**  
- Load source files  
- Validate schema  
- Write to `/Files/Bronze/`  

---

## 🔧 Silver Pipeline

**Purpose:**  
Transform Bronze data into clean, standardized Silver datasets.

**Steps:**  
- Column cleanup  
- Data type corrections  
- Null handling  
- Write to `/Files/Silver/`  

---

## 📊 Gold Pipeline

**Purpose:**  
Generate business-ready analytics.

**Steps:**  
- Aggregations  
- KPI calculations  
- Write to `/Files/Gold/`  

---

## 🔁 Unified Pipeline (Optional)

A combined pipeline that runs Bronze → Silver → Gold in sequence.

