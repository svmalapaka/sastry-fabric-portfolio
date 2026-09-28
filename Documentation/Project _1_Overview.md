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

