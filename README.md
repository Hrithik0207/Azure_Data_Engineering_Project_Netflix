Project Highlights

Azure Data Factory (ADF): Created dynamic pipelines to efficiently ingest data from GitHub APIs.

Medallion Architecture: Organized data into Bronze (Raw), Silver (Transformed), and Gold (Serving) layers to ensure quality and accessibility.

Azure Databricks: Performed complex data transformations using Spark to optimize data processing workflows.

Azure Synapse Analytics: Built a robust data warehouse for detailed data analysis and reporting.

Power BI Integration: Connected Synapse Analytics with Power BI to create interactive and insightful dashboards.

Dataset Management: Managed comprehensive datasets with schema validation and data governance best practices.

Dynamic Pipelines: Implemented parameterization and looping to handle multiple datasets dynamically.

Architecture The project follows the Medallion Architecture, which organizes data into three distinct layers to maintain quality, scalability, and accessibility:

<img width="1034" height="411" alt="image" src="https://github.com/user-attachments/assets/7d2e89c6-f335-4588-a86c-86dace216ebd" />


Bronze (Raw) Layer:

Purpose: Store raw data as-is from the source without any transformations. Source: GitHub APIs. Tools: Azure Data Factory.

Silver (Transformed) Layer:

Purpose: Clean, transform, and enrich the raw data for analysis. Tools: Azure Databricks.

Gold (Serving) Layer:

Purpose: Serve refined data to stakeholders through a data warehouse. Tools: Azure Synapse Analytics, Power BI.

image

Technologies Used

Azure Data Factory (ADF): Orchestration and data integration.

Azure Databricks: Data processing and transformation.

Azure Synapse Analytics: Data warehousing and analytics.

Power BI: Data visualization and reporting.

GitHub APIs: Data source for ingestion.

Azure Data Lake Storage Gen2: Storage solution for raw and processed data.
