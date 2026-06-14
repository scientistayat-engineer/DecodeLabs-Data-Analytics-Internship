# 📊 Project 1: Exploratory Data Analysis & Feature Masking Engine
### 🏢 Organization: Decode Labs Data Automation Engine
### 🔬 Track: Core Exploratory Data Analysis & Diagnostic Discovery
### 🆔 Intern Profile: Ayat Adnan | Title: Data Analytics Intern

---

## 📋 Section 1: Phase Ingestion & Baseline Cleansing

### 🔹 Project Objective
This module establishes the core exploratory layer for raw transactional data. The target focus is to programmatically isolate null values, analyze the shape and volume of rows, treat anomalies, and construct engineered variables (such as `TotalPrice`) to prepare the data for downstream predictive models without corrupting historical systems.

### 🛠️ Core Operations Implemented
1. **Structural Auditing:** Investigating dimensions, column schemas, and row health counts.
2. **Missing Matrix Filtering:** Dropping unmapped customer transactions safely.
3. **Mathematical Feature Derivation:** Compiling absolute row-level transactional weights via the formula:
   $$TotalPrice = Qty \times Price$$

---
