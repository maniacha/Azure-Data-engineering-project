# Azure-Data-engineering-project
Azure Data Engineering pipeline implementing incremental data loading and SCD Type 1 using Azure Data Factory, ADLS Gen2, Databricks, and PySpark.
# Azure Data Engineering Project

## Overview

This project demonstrates an end-to-end Azure Data Engineering

pipeline using Azure Data Factory, ADLS Gen2 and Azure Databricks.

## Technologies

- Azure Data Factory

- Azure Data Lake Storage Gen2

- Azure Databricks

- PySpark

- Delta Lake

- SQL

## Implementations

- Incremental data loading

- SCD Type 1

- Data transformation using PySpark

- Data cleansing

- Deduplication

- Delta tables

- Bronze, Silver and Gold architecture

## Pipeline Flow

Source

   ↓

Azure Data Factory

   ↓

ADLS Gen2 - Bronze

   ↓

Databricks / PySpark

   ↓

ADLS Gen2 - Silver

   ↓

SCD Type 1

   ↓

Gold

   ↓

Reporting
 
