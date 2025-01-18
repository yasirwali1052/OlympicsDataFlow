# OlympicsDataFlow
**Description for Repository:**   This project demonstrates an end-to-end data engineering solution for Tokyo Olympics data. The pipeline fetches data via HTTP API, ingests it into Azure Data Lake Storage using Azure Data Factory, performs transformations in Databricks, and stores the transformed data back into Azure Data Lake Gen2.
![ProjectArchitecture](https://github.com/user-attachments/assets/f6085a28-a04c-48cd-a249-80faefd59107)
**Detailed Description for Repository:**

This project provides an end-to-end data engineering solution for Tokyo Olympics data, showcasing how to design a static pipeline using Azure services. The workflow includes data ingestion, transformation, and preparation for analytics. Here's a step-by-step explanation:

1. **Data Ingestion via Azure Data Factory (ADF):**  
   - The data is fetched from an HTTP API using Azure Data Factory.  
   - A static pipeline is created in ADF to periodically pull data from the API endpoint.  
   - The raw data is ingested and stored in Azure Data Lake Storage Gen2, ensuring secure and scalable storage for the incoming data.

2. **Data Transformation with Azure Databricks:**  
   - The raw data stored in Azure Data Lake is connected to Azure Databricks for processing.  
   - Databricks performs basic data transformations, such as cleaning, normalization, and structuring the data for analysis.  
   - Apache Spark within Databricks is used to handle large-scale data efficiently.

3. **Storing Transformed Data Back in Azure Data Lake Gen2:**  
   - Once the data is transformed, it is written back to Azure Data Lake Gen2 in a structured and organized format.  
   - This step ensures that the transformed data is ready for downstream analytics.

4. **Analytics and Visualization with Power BI:**  
   - Using Power BI, insights and dashboards are created to analyze key metrics and trends from the Tokyo Olympics dataset.  


