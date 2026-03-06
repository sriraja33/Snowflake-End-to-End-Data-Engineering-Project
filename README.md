# Snowflake-End-to-End-Data-Engineering-Project
## Introduction
This project demonstrates a complete end-to-end data engineering workflow implemented entirely on Snowflake, following a modern Medallion Architecture (Bronze, Silver, Gold) for scalable and structured data processing.

The pipeline begins with raw data ingestion into the Bronze layer, where data is stored in its original format for traceability and auditing. In the Silver layer, the data is cleaned, standardized, and transformed to ensure consistency and quality. Finally, the Gold layer contains curated, analytics-ready datasets optimized for business reporting and downstream consumption.

All transformations and data modeling are performed within Snowflake, leveraging its scalable compute and storage capabilities. The final analytical datasets are explored and visualized directly in Snowsight, Snowflake’s native analytics and dashboarding interface.

## Data Architecture
![Data Architecture.jpg](https://github.com/sriraja33/Snowflake-End-to-End-Data-Engineering-Project/blob/main/Data%20Architecture.jpg)

## Technology Used


1. Scripting Langugae - SQL
2. Snowflake Storage
3. Snowsight (Reporting)

## Dataset Used

[Dataset](https://github.com/sriraja33/Snowflake-End-to-End-Data-Engineering-Project/blob/main/hotel_bookings_raw.csv)


## Scripts for the Project

1) [Bronze Layer - Ingestion](https://github.com/sriraja33/Snowflake-End-to-End-Data-Engineering-Project/blob/main/Bronze%20Layer%20SQL.txt)
2) [Silver Layer - Transform](https://github.com/sriraja33/Snowflake-End-to-End-Data-Engineering-Project/blob/main/Silver%20Layer%20SQL.txt)
3) [Gold Layer - Analytics Storage](https://github.com/sriraja33/Snowflake-End-to-End-Data-Engineering-Project/blob/main/Gold%20Layer%20SQL.txt)



## Sample Dashboard (Snowsight)

![Dashboard.jpg](https://github.com/sriraja33/Snowflake-End-to-End-Data-Engineering-Project/blob/main/Sample_Dashboard.jpg)
