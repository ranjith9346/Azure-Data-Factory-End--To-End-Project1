# Azure-Data-Factory-End--To-End-Project1

This is my first complete end-to-end data engineering project. In this project, I created an end-to-end ETL pipeline starting from an on-prem SQL Server Database, moving into the Azure cloud.

My goals for this project were:

To develop a general understanding of data engineering and pipeline creation.

To gain hands-on experience with the Azure cloud platform and offered services.

To produce a functional and stable end product to showcase on GitHub and my resume.


Project Steps
--------------------------------------------------------------
On-Prem SQL Server Database:

Before starting on the cloud, I installed SQL Server Express to host the local server and set up SQL Server Management Studio.

Github:
---------------------------------------------------------------
I created this repository to track the progression of the project.

When Azure Data Factory, Azure Databricks were created: I completed Git configuration within the instances so any changes or publishes were pushed to a branch for easy audit/documentation.

Microsoft Azure:
--------------------------------------------------------------
Once in Azure, I established the resource group and all necessary Azure resources within the group.

Azure Data Lake Storage Gen2: I created the storage containers for the Bronze, Silver, and Gold layers.

Azure Data Factory (ADF): I engineered the pipelines to extract the data from the on-prem database and to execute the Bronze Layer, as well as created linked services to support the flow of data through the pipeline.

Azure DataFlow: I made 2 Dataflows and transformed data from the Bronze to Silver layer and Silver to Gold layer.
