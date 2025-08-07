# ETL Project with Data Fusion, Airflow, and BigQuery
End-to-end GCP data pipeline using Python, Cloud Storage, Data Fusion, BigQuery, Airflow (Composer), and Looker for employee data ingestion, transformation, and visualization.

# Overview

The project aims to perform the following tasks:


**Data Extraction**: Extract structured data using Python scripts and store it in Cloud Storage.

**Data Masking & Encoding**: Apply transformations and mask sensitive fields using Cloud Data Fusion (Wrangler) before loading the data.

**Data Loading**: Load clean, transformed data into Google BigQuery for analysis.

**Data Orchestration**: Use Apache Airflow via Cloud Composer to schedule and manage pipeline execution.

**Data Visualization**: Visualize insights in Looker from BigQuery datasets.

# Architecture Diagram

<img width="900" height="776" alt="image" src="https://github.com/user-attachments/assets/4060650f-edcf-4af3-a756-59c49ca517a5" />





# Components

**VS Code + Python**: Code environment for data simulation and pipeline logic.

**Cloud Storage**: Acts as a raw layer (landing zone) for extracted files.

**Cloud Data Fusion (Wrangler)**: Performs data wrangling, encoding, and transformations.

**BigQuery**: Stores transformed data, serves as a central analytics warehouse.

**Looker**: Dashboards built directly on top of BigQuery datasets.

**Cloud Composer (Airflow)**: Manages and schedules the data pipeline through DAGs.
