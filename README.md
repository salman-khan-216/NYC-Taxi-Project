# 🚖 NYC Taxi Lakehouse Analytics Project

An end-to-end Azure Data Engineering project built using **Azure Data Factory, Azure Databricks, ADLS Gen2, PySpark, Delta Lake, and Power BI** following the **Medallion Architecture (Bronze → Silver → Gold)** approach.

The project ingests NYC Taxi parquet datasets from external web/API sources, processes and transforms the data using PySpark, builds curated Delta Lake analytical marts, and enables downstream BI reporting.

---

# 📌 Project Overview

The project ingests publicly available NYC Taxi trip datasets from web/API sources into Azure Data Lake Storage Gen2 and processes them through multiple transformation layers using Azure Databricks.

The pipeline handles:

* Dynamic ingestion of monthly parquet datasets
* Schema drift and datatype inconsistencies
* Data quality validations
* Business-rule validations
* Anomaly detection
* Dimensional enrichment
* KPI aggregation
* Delta Lake business marts
* BI integration with Power BI

The final output is a scalable Lakehouse analytics platform optimized for reporting and analytical consumption.

---

# ⚙️ Technologies Used

* Azure Data Factory (ADF)
* Azure Databricks
* PySpark
* ADLS Gen2
* Delta Lake
* Power BI
* Unity Catalog
* SQL
* Parquet

---

# 🏗️ Architecture Overview
<img width="1706" height="958" alt="NYC-Taxi Architecture" src="https://github.com/user-attachments/assets/31b9df78-b880-4778-ad47-73b79fca852b" />


## Bronze Layer

* Raw parquet ingestion from external web/API sources
* Dynamic Azure Data Factory pipelines
* ADLS Gen2 raw storage

## Silver Layer

  * Schema normalization
  * Data quality validations
  * Business-rule validations
  * Suspicious/anomaly trip identification
  * Derived metrics and analytical enrichment
  * Partitioned curated datasets

## Gold Layer

* Delta Lake analytical marts
* KPI reporting datasets
* Payment, zone, borough, and hourly analytics
* BI-ready aggregated tables

---

# 🔥 Key Features

* Dynamic ADF ingestion pipelines
* Medallion Architecture implementation
* Schema drift resolution for parquet datasets
* Data quality and business-rule validations
* Delta Lake business marts with ACID support
* Power BI integration for analytics and reporting

---

# 📊 Analytics Built

* Daily KPI Analytics
* Borough Performance Analytics
* Zone-Level Analytics
* Hourly Trip Pattern Analytics
* Payment Analytics
* Anomaly Monitoring

---

# 🔐 Security

Implemented secure connectivity between Databricks and ADLS Gen2 using:

* Azure Service Principal
* RBAC-based access control

---

# 🚀 Key Learnings

* Lakehouse Architecture
* Delta Lake
* PySpark Transformations
* Data Quality Engineering
* Partition Optimization
* BI-Oriented Data Modeling

---

# 👨‍💻 Salman Khan Patan
