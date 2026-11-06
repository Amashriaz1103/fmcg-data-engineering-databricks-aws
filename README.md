# FMCG Data Engineering Pipeline | AWS & Databricks

## Project Overview
An end-to-end FMCG data engineering project built using AWS and Databricks. The project processes FMCG business data through a structured data pipeline and prepares analytical datasets using the Medallion Architecture.

## Architecture
The project follows the Bronze, Silver and Gold data architecture.

- **Bronze:** Initial data ingestion and storage.
- **Silver:** Data cleaning, transformation and dimension processing.
- **Gold:** Fact processing and business-ready analytical datasets.

## Technology Stack
- AWS
- Amazon S3
- Databricks
- PySpark
- Python
- SQL
- Delta Lake
- Databricks Genie

## Project Structure

- `setup/` – Catalog setup, utility functions and date dimension creation.
- `Dimension_data_processing/` – Customer, pricing and product dimension processing.
- `Fact_data_processing/` – Full and incremental fact loading.
- `sql/` – SQL queries and enriched fact views.

## Key Implementations
- Databricks catalog and schema setup.
- Date dimension creation.
- Customer, product and pricing dimension processing.
- Full fact data loading.
- Incremental fact data loading.
- Enriched fact view creation.
- FMCG sales analysis using Databricks Genie.

## How to Explore
The notebooks are exported from Databricks in Jupyter Notebook format (`.ipynb`). Open them in Jupyter or VS Code to review the implementation.

## Author
Data Engineering Project Portfolio