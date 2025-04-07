# 🔷 End-to-End Azure Data Engineering Project

This project demonstrates how to build a **modern data pipeline** using Azure services — from data ingestion to transformation, and finally to reporting. It was developed as part of my learning journey as a Data Science student exploring cloud-based data engineering.

---

## 🚀 Project Overview

This pipeline is built using:

- **Azure Data Factory** for data ingestion and orchestration
- **Azure Data Lake Storage Gen2** for storing raw and transformed data
- **Azure Databricks (Apache Spark)** for scalable data transformation using PySpark
- **Azure Synapse Analytics (Serverless SQL Pools)** for querying data directly from the Data Lake via external tables
- **Power BI** for creating final visual reports

---

## 🧠 What I Learned

- How to build and orchestrate **ETL/ELT workflows** using ADF and Databricks
- Designing **layered architecture** (raw → curated → consumption) in a Data Lake
- Using **external tables** in Synapse to query Parquet/CSV files directly — reducing cost and complexity
- Leveraging **Serverless SQL** for efficient, pay-per-query analytics
- Creating **interactive dashboards** using Power BI
- Best practices for **partitioning**, **data pipeline optimization**, and **interview prep topics** for Azure Data Engineering roles

---

## 🏗️ Architecture Overview

```plaintext
[External Source]
       ↓
Azure Data Factory (Ingestion)
       ↓
Azure Data Lake (Raw Zone)
       ↓
Azure Databricks (Transform with PySpark)
       ↓
Azure Data Lake (Curated Zone)
       ↓
Azure Synapse (Serverless SQL + External Tables)
       ↓
Power BI (Reporting & Dashboarding)
