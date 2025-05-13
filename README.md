# Databricks-EndToEnd-Project

This project demonstrates an end-to-end data pipeline using Azure Databricks and Unity Catalog, built on the Medallion Architecture (Bronze → Silver → Gold). The pipeline ingests Parquet files from ADLS Gen2, applies:
SCD Type 1 using PySpark (overwrite-style updates)
SCD Type 2 using Delta Live Tables (DLT) with declarative syntax
Governance and access control via Unity Catalog

