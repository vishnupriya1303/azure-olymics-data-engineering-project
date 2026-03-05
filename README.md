Built an end-to-end Azure data pipeline using the Tokyo Olympics dataset. Data was ingested from Kaggle API/GitHub API into Azure Data Lake Storage using Azure Data Factory. Secure access was configured via App Registration, and Azure Databricks was used to connect to ADLS and perform data transformations.

The transformed data was written back to ADLS and then loaded into Azure Synapse Analytics for analytical querying. Finally, Power BI was connected to Synapse to create dashboards visualizing insights such as country-wise medal counts and genderwise avg, Coach influence.
