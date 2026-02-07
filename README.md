# databricks-fmcg-lakehouse-project

This project demonstrates an end-to-end data engineering pipeline built on Databricks using the Lakehouse architecture for an FMCG business scenario involving a company acquisition. An existing FMCG company acquires another company and needs to consolidate data from both organizations into a single, unified analytics platform.

The pipeline handles historical data loads from the acquired company and then continues with incremental data processing to capture daily changes. Raw data from multiple sources is ingested into the Bronze layer as-is, transformed and standardized in the Silver layer by resolving schema differences, duplicates, and data quality issues, and finally modeled into business-ready Gold tables for reporting and analytics.

Delta Lake is used extensively to support merge operations, handle slowly changing data, and ensure reliable incremental updates. The final Gold layer provides consolidated views of products, customers, and sales across both companies, enabling accurate reporting and business insights.

# Tech Stack

Databricks Platform

Apache Spark (PySpark)

Spark SQL

Delta Lake (MERGE, ACID transactions, schema enforcement)

Lakehouse Architecture (Bronze, Silver, Gold layers)

Databricks Workflows (Jobs & task orchestration)

Incremental & Historical Data Processing

Data Cleaning & Transformation

Dimensional Data Modeling (Fact & Dimension tables)

GitHub (Version control & project collaboration

# Intended Audience

Data Engineers, Analytics Engineers, and anyone interested in building production-grade data pipelines on Databricks.
