# 🍽️ Restaurant Analytics Platform | Azure Databricks

An end-to-end **Data Engineering** project built on **Azure Databricks** that combines **real-time streaming** and **batch processing** to analyze restaurant operations. The project follows the **Medallion Architecture** and demonstrates a modern data engineering workflow using Databricks.

## 🚀 Tech Stack

- Azure Databricks
- Apache Spark (PySpark)
- Azure Event Hubs
- Azure SQL Database
- Delta Lake
- Unity Catalog
- Lakeflow Declarative Pipelines
- Lakeflow Connect (CDC)
- Databricks Workflows

## 📊 Architecture

- **Streaming Source:** Azure Event Hubs (Restaurant Orders)
- **Batch Source:** Azure SQL Database
- **Streaming Ingestion:** Lakeflow Declarative Pipelines
- **Batch Ingestion:** Lakeflow Connect (CDC)
- **Storage:** Delta Lake
- **Data Governance:** Unity Catalog
- **Orchestration:** Databricks Workflows

## 🏅 Medallion Architecture

- 🥉 **Bronze** – Raw streaming and batch data
- 🥈 **Silver** – Cleaned and validated data
- 🥇 **Gold** – Business-ready analytics and aggregations

## ✨ Features

- Real-time streaming ingestion
- Batch CDC ingestion
- Data quality transformations
- Delta Lake tables
- Unity Catalog integration
- Workflow orchestration
- End-to-end ETL pipeline

## Notes

You can use the data already in 00_synthetic_data\data or generate the data using the script 00_synthetic_data\03_run.py


<img width="1106" height="818" alt="data_module" src="https://github.com/user-attachments/assets/23818baa-80e9-4f6f-b1a5-08f5721967f9" />
<img width="5371" height="2685" alt="project_architecture" src="https://github.com/user-attachments/assets/2af7099b-ddb5-4358-8225-29d13ec79450" />
<img width="1600" height="754" alt="Pipeline_job" src="https://github.com/user-attachments/assets/e20422a4-5509-429d-babf-366b01dd2033" />



