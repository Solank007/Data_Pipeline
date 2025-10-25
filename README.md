Reddit Data Pipeline
A complete data pipeline solution to extract, transform, and load (ETL) Reddit data into a Redshift data warehouse. This project demonstrates end-to-end data engineering using modern cloud and orchestration tools.

Overview
This data pipeline enables:
Extraction: Pull Reddit posts and comments using the Reddit API.
Storage: Save raw data to Amazon S3.
Transformation: Clean, deduplicate, and enrich data using AWS Glue and Amazon Athena.
Loading: Load the transformed data into Amazon Redshift for analytics.
Orchestration: Manage workflows and scheduling with Apache Airflow and Celery.
The pipeline ensures a reliable, automated, and scalable flow from source to warehouse.

Components:
Reddit API: Source of raw data.
Apache Airflow & Celery: Orchestrate ETL jobs and distribute tasks.
PostgreSQL: Temporary storage and metadata tracking.
Amazon S3: Raw and intermediate data storage.
AWS Glue: Data cataloging and ETL transformations.
Amazon Athena: Query and transform large datasets with SQL.
Amazon Redshift: Centralized data warehouse for analytics.
