# Pipelines Documentation — Medallion Automation

This document explains the Bronze, Silver, Gold, and unified Medallion pipelines used in Portfolio Project #1.

---

## 🥉 Bronze Pipeline

**Purpose:** Raw ingestion  
**Steps:**
- Load CSVs from `/Files/Bronze`
- Append to Bronze tables
- Validate row counts

---

## 🥈 Silver Pipeline

**Purpose:** Cleaning + standardization  
**Steps:**
- Read Bronze tables
- Apply schema alignment
- Remove nulls
- Write to Silver tables

---

## 🥇 Gold Pipeline

**Purpose:** Business-ready analytics  
**Steps:**
- Read Silver tables
- Aggregate category-level metrics
- Create validation matrices
- Write to Gold tables

---

## 🔄 Medallion Pipeline (Unified)

**Purpose:** End-to-end automation  
**Flow:**
Bronze → Silver → Gold  
Triggered manually or scheduled  
