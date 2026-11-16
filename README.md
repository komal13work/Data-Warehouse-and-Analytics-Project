# Data-Warehouse-and-Analytics-Project

Built a data warehouse in SQL Server from two source systems, a CRM and an ERP, through bronze, silver and gold. The files and scripts of the free full project.


🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:

<img width="1740" height="872" alt="image" src="https://github.com/user-attachments/assets/c77b4075-fe82-4ef2-80a0-1bb6e3d821d3" />



Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.

Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.

Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.

📖 Project Overview

Design the architecture: a modern data warehouse with three layers, bronze, silver and gold.
Build the ETL pipelines: load the source files and move the data through the layers.
Model the data: facts and dimensions, ready for reports.
Analyze it: answer business questions with SQL.
