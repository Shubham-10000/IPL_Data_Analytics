# IPL_Data_Analytics
This Azure project builds a scalable data pipeline: Azure Data Factory ingests raw data into Data Lake Gen2, then Azure Databricks transforms it. The processed data is analyzed in Azure Synapse Analytics and visualized in Power BI. The architecture enables efficient real-time analytics and valuable business insights.


Description
This project demonstrates a scalable data pipeline using Azure services for ingestion, transformation, analysis, and visualization. It enables real-time analytics and business insights by processing raw data from various sources.

Architecture
Data Source: Collects data from various sources.
Azure Data Factory: Ingests raw data into Data Lake Gen2.
Azure Databricks: Transforms raw data, storing results in Data Lake.
Azure Synapse Analytics: Analyzes transformed data.
Power BI: Visualizes insights on interactive dashboards.
Setup
Data Lake Gen2: Create storage for raw and transformed data.
Data Factory: Set up pipelines for data ingestion.
Databricks: Configure cluster and notebooks for transformation.
Synapse Analytics: Analyze transformed data.
Power BI: Create dashboards for visualization.
Usage
Run the Data Factory pipeline, transform data in Databricks, analyze with Synapse, and view insights in Power BI.
