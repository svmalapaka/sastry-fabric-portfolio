# 📘 Portfolio Project 2 — Overview

This document provides a high-level overview of Portfolio Project #2, including the architecture, components, workflows, and documentation structure. It serves as the entry point for anyone reviewing this project.

---

## 🏗️ Project Summary

Portfolio Project 2 demonstrates a second end-to-end Microsoft Fabric implementation using the Medallion Architecture. This project expands on Project 1 by introducing new datasets, transformations, and reporting logic.

Key components include:

- Bronze → Silver → Gold data layers  
- Lakehouse storage  
- Pipelines for ingestion and transformation  
- SQL Endpoint for reporting  
- Power BI report for validation and insights  

---

## 🧱 Architecture Overview

### **Medallion Layers**
- **Bronze:** Raw ingestion  
- **Silver:** Cleaned and standardized datasets  
- **Gold:** Business-ready analytics  

### **Lakehouse**
- Organized into `/Files` and `/Tables`  
- Supports SQL Endpoint for Power BI  

### **Pipelines**
- Bronze ingestion pipeline  
- Silver transformation pipeline  
- Gold analytics pipeline  

### **Power BI**
- Gold validation report  
- Category-level breakdown  
- SQL Endpoint connectivity  

---

## 📁 Repository Structure


Documentation/
│
└── Project2/
├── Project_2_Overview.md
├── Lakehouse_Project_2.md
├── Pipelines_Project_2.md
└── PowerBI_Project_2.md

Code

---

## 🎯 Purpose of This Overview

This overview acts as:

- A quick introduction for recruiters  
- A navigation guide for GitHub visitors  
- A summary of the project’s architecture  
- A reference point before diving into detailed documentation  
