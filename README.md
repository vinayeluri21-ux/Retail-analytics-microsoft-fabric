# Retail-analytics-microsoft-fabric
End to End retail analytics using Microsoft fabric and Medallion Architecture  

vinay eluri <vinayeluri97@gmail.com>
3:25 PM (0 minutes ago)
to me

# Retail Analytics using Microsoft Fabric

## Overview
This project demonstrates an end-to-end retail analytics solution
using Microsoft Fabric, OneLake, and Medallion Architecture.

Source data is ingested from Azure Data Lake Storage (ADLS),
processed through Bronze, Silver, and Gold layers,
and served to Power BI for reporting.

## Architecture
- Azure Data Lake Storage (orders.csv, returns.xlsx, inventory.json)
- Microsoft Fabric Lakehouse (Parquet format)
- Medallion Architecture:
- Bronze: Raw data ingestion
- Silver: Data cleansing and enrichment
- Gold: Aggregated business metrics
- Power BI (Direct Lake)

## Technologies Used
- Microsoft Fabric
- Azure Data Lake Storage
- PySpark
- Delta / Parquet
- Power BI

## Use Case
Retail sales, returns, and inventory analytics.

## Outcome
- Scalable Lakehouse architecture
- Business-ready KPIs
- High-performance reporting

