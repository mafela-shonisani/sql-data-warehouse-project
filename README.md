# SQL Data Warehouse Project

## Overview

Welcome to my SQL Data Warehouse Project! 🚀

This project demonstrates the design and implementation of a modern data warehouse using SQL Server and the Medallion Architecture (Bronze, Silver, and Gold layers). The project integrates CRM and ERP datasets, transforming raw data into business-ready information that supports analytics, reporting, and decision-making.

This project showcases my skills in SQL development, data warehousing, ETL processes, data modeling, and analytics.

---

## Data Architecture

The project follows the Medallion Architecture:

### Bronze Layer

* Stores raw data from source systems.
* Data is loaded directly from CSV files into SQL Server.
* No transformations are applied.

### Silver Layer

* Cleans and transforms raw data.
* Handles missing values, duplicates, and data inconsistencies.
* Standardizes data formats for downstream use.

### Gold Layer

* Stores business-ready data.
* Implements dimensional modeling using fact and dimension tables.
* Supports reporting, dashboards, and analytical queries.

---

## Project Objectives

The primary objective of this project is to build a modern SQL Data Warehouse that consolidates CRM and ERP data into a centralized repository for analytics and reporting.

### Key Goals

* Import data from multiple source systems.
* Design a layered data warehouse architecture.
* Build ETL pipelines using SQL Server.
* Clean and transform raw data.
* Create analytical data models.
* Generate business insights through SQL queries.

---

## Technologies Used

* Microsoft SQL Server
* SQL Server Management Studio (SSMS)
* T-SQL
* CSV Files
* Git & GitHub
  

---

## Data Sources

The project uses data from two business systems:

### CRM Data

* Customer Information
* Product Information
* Sales Details

### ERP Data

* Customer Information
* Customer Locations
* Product Categories

---

## Database Structure

### Schemas

```text
bronze
silver
gold
```

### Bronze Tables

```text
bronze.crm_cust_info
bronze.crm_prd_info
bronze.crm_sls_details
bronze.erp_cust_az12
bronze.erp_loc_a101
bronze.erp_px_cat_g1v2
```

---

## ETL Process

### Extract

Raw CRM and ERP datasets are extracted from CSV files.

### Transform

Data quality issues are resolved through:

* Data validation
* Duplicate removal
* Standardization
* Data type conversion

### Load

Cleaned data is loaded into Silver tables and transformed into Gold analytical models.

---

## Data Warehouse Workflow

```text
CSV Files
    ↓
Bronze Layer
    ↓
Silver Layer
    ↓
Gold Layer
    ↓
Analytics & Reporting
```

---

## Analytics and Reporting

The Gold Layer supports business analysis in the following areas:

### Customer Analysis

* Customer demographics
* Customer segmentation
* Customer purchasing behavior

### Product Analysis

* Product performance
* Product category analysis
* Top-selling products

### Sales Analysis

* Revenue trends
* Sales performance
* Order analysis

---

## Repository Structure

```text
sql-data-warehouse-project/
│
├── datasets/
│
├── docs/
│   ├── data_architecture.drawio
│   ├── data_flow.drawio
│   ├── data_models.drawio
│   ├── data_catalog.md
│
├── scripts/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── tests/
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## Key Skills Demonstrated

* SQL Development
* Data Warehousing
* ETL Pipeline Development
* Data Modeling
* Data Integration
* Data Quality Management
* Business Analytics
* Database Design

---

## Future Improvements

* Incremental data loading
* SQL Server Agent automation
* Power BI dashboard integration
* Data quality monitoring
* Advanced analytics and reporting

---

## Author

**Shonisani Mafela**

Final-Year BSc Mathematical Sciences Student (Computer Science & Statistics)

Interested in:

* Data Analytics
* Machine Learning
* Data Warehousing
* Business Intelligence
* Data Engineering

---

## Project Status

✅ Bronze Layer Completed

🔄 Silver Layer In Progress

📊 Gold Layer and Analytics Coming Soon
