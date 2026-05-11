# 🚖 NYC Taxi Lakehouse Analytics Project

An end-to-end Azure Data Engineering project built using **Azure Data Factory, Azure Databricks, ADLS Gen2, PySpark, Delta Lake, and Power BI** following the **Medallion Architecture (Bronze → Silver → Gold)** approach.

The project ingests NYC Taxi parquet datasets from external web/API sources, processes and transforms the data using PySpark, builds curated Delta Lake analytical marts, and enables downstream BI reporting.

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

## Bronze Layer

* Dynamic ingestion of monthly parquet files using ADF
* Raw data storage in ADLS Gen2

## Silver Layer

* Schema normalization and schema drift handling
* Data quality validations and anomaly detection
* Dimensional enrichment using lookup datasets
* Partitioned curated datasets using PySpark

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
