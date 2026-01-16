# 📈 Daily Stock Price ETL (Databricks + AWS S3)

## Overview
A production-style ETL pipeline that fetches daily stock prices, transforms them using **PySpark on Databricks**, and stores the data in **AWS S3 as a Delta Lake**. The pipeline runs daily and supports incremental data ingestion.

## Tech Stack
- Databricks
- PySpark
- Python
- AWS S3
- Delta Lake
- Yahoo Finance API

## Workflow
1. Extract daily stock data from an external API  
2. Transform and clean data using PySpark  
3. Load data into AWS S3 in Delta format  

## Storage
