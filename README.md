# 📊 Data Warehouse & Analytics Project (Portfolio)

This project demonstrates a comprehensive data warehousing and analytics solution — from building a modern data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in **Data Engineering**, **ETL**, and **Analytics**.

---

## 🏗️ Data Architecture

The data architecture follows the **Medallion Architecture** with **Bronze**, **Silver**, and **Gold** layers:

- **Bronze Layer:**  
  Stores raw data as-is from source systems. Data is ingested from CSV files into a SQL Server Database.

- **Silver Layer:**  
  Includes data cleansing, standardization, and normalization processes to prepare data for analysis.

- **Gold Layer:**  
  Contains business-ready data modeled into a star schema for reporting and analytics.

---

## 📖 Project Overview

This project includes:

- **Data Architecture:** Designing a modern data warehouse using Medallion Architecture.
- **ETL Pipelines:** Extracting, transforming, and loading data from source systems into the warehouse.
- **Data Modeling:** Developing fact and dimension tables optimized for analytical queries.
- **Analytics & Reporting:** Creating SQL-based reports and dashboards for actionable insights.  
---

### 📦 Data Warehouse (Data Engineering)

**Objective:**  
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and strategic decision-making.

**Specifications:**

- **Data Sources:** Import data from two systems (ERP & CRM) provided as CSV files.
- **Data Quality:** Cleanse and resolve quality issues before analysis.
- **Integration:** Combine sources into a single, user-friendly data model for analytical queries.
- **Scope:** Focus on the latest dataset only (historization not required).
- **Documentation:** Provide clear documentation for the data model to support business stakeholders and analytics teams.

---

### 📊 BI Analytics & Reporting (Data Analysis)

**Objective:**  
Develop SQL-based analytics to deliver insights into:

- Customer behavior  
- Product performance  
- Sales trends  

These insights will empower stakeholders with key business metrics for data-driven decision-making.


## 📂 Repository Structure

```bash
data-warehouse-project/
│
├── datasets/                           # Raw ERP and CRM datasets
│
├── docs/                               # Documentation & diagrams
│   ├── etl.drawio                      # ETL techniques and workflow diagrams
│   ├── data_architecture.drawio        # Overall project architecture
│   ├── data_catalog.md                 # Dataset field descriptions and metadata
│   ├── data_flow.drawio                # Data flow diagrams
│   ├── data_models.drawio              # Star schema data models
│   ├── naming-conventions.md           # Table, column, and file naming standards
│
├── scripts/                            # SQL ETL and transformation scripts
│   ├── bronze/                         # Raw data ingestion scripts
│   ├── silver/                         # Data cleaning and transformation scripts
│   ├── gold/                           # Analytical model creation scripts
│
├── tests/                              # Data validation and quality test scripts
│
├── README.md                           # Project overview and instructions
├── LICENSE                             # License information
├── .gitignore                          # Files/directories ignored by Git
└── requirements.txt                    # Project dependencies
