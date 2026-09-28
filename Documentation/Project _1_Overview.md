# 📘 Portfolio Project 1 — Sales Lakehouse Overview

This document provides a high-level overview of Portfolio Project #1, including the architecture, components, workflows, and documentation structure. It serves as the entry point for anyone reviewing the project.

---

## 🏗️ Project Summary

Portfolio Project #1 demonstrates a complete end-to-end Microsoft Fabric implementation using the Medallion Architecture:

- Bronze → Silver → Gold data layers  
- Lakehouse storage  
- Pipelines for ingestion, cleaning, and analytics  
- SQL Endpoint for reporting  
- Power BI Gold Validation Report  

The project is designed to be simple, clean, and easy for recruiters and engineers to understand.

---

## 🧱 Architecture Overview

### **Medallion Layers**
- **Bronze:** Raw CSV ingestion  
- **Silver:** Cleaned, standardized datasets  
- **Gold:** Aggregated business-ready analytics  

### **Lakehouse**
- Organized into `/Files` and `/Tables`  
- Supports SQL Endpoint for Power BI  

### **Pipelines**
- Bronze Pipeline  
- Silver Pipeline  
- Gold Pipeline  
- Unified Medallion Pipeline  

### **Power BI**
- Gold Validation Matrix  
- Category-level breakdown  
- SQL Endpoint connectivity  

---

## 📁 Repository Structure

Fabric-Portfolio/
Documentation

- Project_1_Overview.md
- Lakehouse_Project_Structure.md
- Pipelines_Documentation.md
- Power_BI_Report_Documentation.md
- Fabric_Shortcuts.md
- Project_Documentation.md
  
 Project2/                ← future project folder
- Project_2_Overview.md
- Lakehouse_Project_2.md
- Pipelines_Project_2.md
- PowerBI_Project_2.md

- Lakehouse/
- Pipelines/
- Reports/
- Screenshots/

```markdown
This structure ensures clarity and scalability as you add more portfolio projects

---

## 📄 Documentation Included

Project 1 includes the following markdown files:

- **Lakehouse_Project_Structure.md**  
- **Pipelines_Documentation.md**  
- **Power_BI_Report_Documentation.md**  
- **Fabric_Shortcuts.md**  
- **Project_Documentation.md**  
- **Portfolio_Project_1.md**  

Each file covers a specific part of the project.

---

## 🎯 Purpose of This Overview

This overview acts as:

- A quick introduction for recruiters  
- A navigation guide for GitHub visitors  
- A summary of the project’s architecture  
- A reference point before diving into detailed documentation  

---
