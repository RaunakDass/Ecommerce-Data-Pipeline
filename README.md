

# E-commerce Data Pipeline

## Overview
This project involves building an efficient and automated e-commerce data pipeline using Microsoft Azure and Databricks. The pipeline is designed based on the medallion architecture, which leverages the power of Delta Lake to structure data into Bronze, Silver, and Gold layers. This design pattern ensures data quality and accessibility for analytics and reporting.

## Features
- **Cloud Platform**: Utilized Microsoft Azure to deploy and manage the e-commerce data pipeline.
- **Medallion Architecture**: Implemented a layered data architecture:
  - **Bronze Layer**: Raw data ingestion
  - **Silver Layer**: Data cleansing and transformation
  - **Gold Layer**: Optimized data for analytics and reporting, utilizing the concept of One Big Table (OBT) for simplified access and analysis.
- **Delta Lake**: Enabled the medallion architecture to ensure ACID transactions and scalable metadata handling.
- **Automation**: Employed Microsoft Azure Triggers to automate the pipeline, initiating data processing whenever new data is added.
- **PySpark**: Used PySpark for data processing and transformation within Databricks.

## Technologies
- **Microsoft Azure**: Cloud platform for infrastructure and services
- **Databricks**: Unified data analytics platform
- **Delta Lake**: Storage layer that brings reliability to data lakes
- **PySpark**: Python API for Apache Spark, used for data processing

## Getting Started
To set up and run this project, follow these steps:
- Set up an Azure account and configure necessary services (Azure Databricks, Azure Storage, etc.).
- Clone this repository to your local machine.
- Follow the provided notebooks and scripts to deploy the pipeline in your Azure environment.

![Screenshot 2024-06-22 225638](https://github.com/RaunakDass/Ecommerce-Data-Pipeline/assets/142901720/e80c7fa2-aee2-42d8-9364-1b78f1da13e8)

![Screenshot 2024-06-22 225702](https://github.com/RaunakDass/Ecommerce-Data-Pipeline/assets/142901720/1309c4e5-4640-4436-93dd-364d272b1148)

![Screenshot 2024-06-22 230430](https://github.com/RaunakDass/Ecommerce-Data-Pipeline/assets/142901720/9d349f56-9898-479d-bfac-0fa97dd1520c)

![Pasted image 20240305124127](https://github.com/RaunakDass/Ecommerce-Data-Pipeline/assets/142901720/40fe79dc-9698-4ebd-9a2d-c73c8823b44a)

![Pasted image 20240305124541](https://github.com/RaunakDass/Ecommerce-Data-Pipeline/assets/142901720/2536b01b-89b8-4ca7-8ee3-9860b3ba46a6)


## Contributing
Feel free to submit issues or pull requests if you have suggestions for improvements or find any bugs.



