# Azure Databricks Retail Analytics Data Warehouse  
**End-to-End Modern Data Platform | Medallion Architecture | Delta Live Tables | Power BI**

[Official Report](https://github.com/AlissaAIDataPro/azure-databricks-end-2-end-project/blob/main/E-2-E%20Project_AlissaKhan.pdf)

Production-grade retail analytics data warehouse built entirely on Azure Databricks:
- Incremental ingestion via **Auto Loader**
- **Bronze → Silver → Gold** medallion architecture
- **SCD Type 2** on Products dimension (full history tracking)
- **Delta Live Tables** for Gold layer
- Orchestrated with **Databricks Workflows**
- Business insights served via **Power BI**

### Tech Stack
Azure Databricks • Delta Lake • Delta Live Tables • PySpark • SQL • Unity Catalog • Azure Data Lake Gen2 • Power BI

### Key Features
- Exactly-once processing with checkpointing
- Schema evolution + malformed records rescued automatically
- Daily incremental loads simulated and proven
- Top 5% of products drive 68% of revenue (Pareto in action)
- Regional + category profitability dashboards

### Live Demo Screenshots
| Pipeline Overview | Power BI Dashboard | SQL Query in SQL Editor |
|-------------------|--------------------|-------------------|
| ![Workflow](https://github.com/AlissaAIDataPro/azure-databricks-end-2-end-project/blob/main/End-2-End-Pipeline.png) | ![Dashboard](https://github.com/AlissaAIDataPro/azure-databricks-end-2-end-project/blob/main/Power%20BI%20Pipeline%20Dashboard.png) | ![SCD2](https://github.com/AlissaAIDataPro/azure-databricks-end-2-end-project/blob/main/SQL%20Query.png) |
