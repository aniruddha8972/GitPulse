# 🚀 GitPulse -- Enterprise GitHub Events Analytics Platform

## Project Overview

GitPulse is an end-to-end Data Engineering project built on **Databricks
Community Edition** using the **GitHub Events API**.

It implements a Medallion Architecture (**Bronze → Silver → Gold**) with
incremental loading, data quality validation, logging, auditing,
metadata-driven processing, and business KPI generation.

## Business Problem

Organizations need an automated way to analyze GitHub public activity,
identify trends, and monitor repository and developer engagement.

## Architecture

``` text
GitHub Events API
        │
        ▼
 Bronze Ingestion
        │
        ▼
 Bronze (Raw JSON)
        │
        ▼
 Silver (Clean & Standardized)
        │
        ▼
 Gold (Business KPIs)
        │
        ▼
 SQL Analytics
```

## Technology Stack

-   Databricks Community Edition
-   Apache Spark (PySpark)
-   Delta Lake
-   Python
-   SQL
-   GitHub Events API
-   Git & GitHub

## Repository Structure

``` text
GitPulse/
├── docs/
├── notebooks/
├── sql/
├── sample_data/
├── images/
└── README.md
```

## Business KPIs

-   Daily Active Repositories
-   Daily Active Developers
-   Push Events
-   Pull Requests
-   Fork Events
-   Watch Events
-   Hourly Activity
-   Top Repositories
-   Top Contributors

## Pipeline Workflow

1.  Ingest GitHub Events API
2.  Load Bronze layer
3.  Transform to Silver
4.  Generate Gold KPIs
5.  Execute Data Quality checks
6.  Capture Audit Logs
7.  Publish analytics

## Documentation

-   BRD
-   SRD
-   ADD
-   HLD
-   LLD
-   STM
-   Data Dictionary
-   Data Quality Framework
-   Logging & Audit Design
-   Error Handling & Recovery Strategy
-   Metadata Design Document

## Author

**Aniruddha Giri**

Data Engineer \| Azure \| Databricks \| PySpark \| SQL \| Python
