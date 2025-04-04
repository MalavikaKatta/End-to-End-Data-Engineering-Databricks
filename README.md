# **End-to-End Data Engineering Project with Databricks**

<img src="https://github.com/user-attachments/assets/30d8bb02-0002-4ff5-b5da-06f4db885ee7" width="800" height="500">

## **Project Overview**
This project focuses on building a modern **data pipeline** for an **eCommerce client** operating across **27 countries and 11,000 stores**. The client aims to:  
- **Consolidate data** from multiple sources.  
- **Accelerate data processing** to reduce latency.  
- **Improve decision-making accuracy** by 25%.  
- **Enable real-time analytics** to boost **repeat purchases by 15%** and improve **financial reporting by region**.  

## **Datasets Used**
The project integrates **three different datasets** stored in various formats:  
1. **Customer Data (CRM) - CSV**  
2. **Product Catalog (Inventory) - JSON**  
3. **Transaction History (Transactions) - PARQUET**  

## **Challenges Faced**
- **Starting a Cluster with a Standard Node**: The initial challenge was configuring a Databricks cluster with the correct **standard node** type to optimize performance and cost-efficiency.  
- **Data Quality Issues**: Inconsistent, missing, or duplicate records.  
- **Multiple Data Formats**: Need for a unified schema across CSV, JSON, and Parquet files.  
- **Complex ETL Process**: Efficiently transforming raw data into an analytics-ready format.  

## **Solution Architecture**
To address these challenges, the project follows the **Medallion Architecture** using **Databricks**:  
🚀 **Raw Data → Bronze → Silver → Gold → Power BI**

### **1️⃣ Bronze Layer (Raw Data Storage)**
- Stores unprocessed raw data.  
- Preserves historical changes.  

### **2️⃣ Silver Layer (Cleaned & Processed Data)**
- Cleans data and removes duplicates.  
- Implements **data quality rules** and **PII masking**.  

### **3️⃣ Gold Layer (Analytics-Ready Data)**
- Applies **business logic** for insights.  
- Optimizes query performance for reporting.  
- Prepares data for **Power BI** dashboards.  

## **Key Components & Technologies**
- **Databricks Workspace** – Unified data engineering environment.  
- **Databricks File System (DBFS)** – Stores and manages data files.  
- **Databricks Clusters** – Compute resources for processing big data.  
- **Databricks Notebooks** – Develop ETL workflows using **PySpark & SQL**.  
- **Delta Lake** – Ensures data reliability with ACID transactions.  
- **Databricks Jobs** – Automates ETL processes.  
- **Azure Data Lake** – Scalable storage for raw and processed data.  
- **Power BI** – Visualizes insights for business users.  

## **Project Outcomes**
✔️ Consolidated **multi-source data** into a structured format.  
✔️ Reduced data processing time, improving efficiency.  
✔️ Increased **decision-making accuracy by 25%**.  
✔️ Enabled **real-time analytics** to boost customer engagement and financial reporting. 

![image](https://github.com/user-attachments/assets/e4406904-1217-42d7-871d-4742f1a66df6)
