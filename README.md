🏠 Airbnb Data Engineering Pipeline

Built an end-to-end data pipeline using AWS S3, Snowflake, and dbt to transform raw Airbnb data into analytics-ready datasets.

🔹 What This Project Does

Ingests raw CSV data (bookings, hosts, listings)

Applies layered transformation (Bronze → Silver → Gold)

Implements incremental loading

Tracks historical changes using SCD Type 2 snapshots

Produces fact tables and denormalized analytics tables

🔹 Tech Stack

Snowflake (Data Warehouse)

dbt (Transformations & Modeling)

AWS S3 (Storage)

Python

Git

🔹 Key Highlights

Designed medallion architecture for structured data flow

Built modular dbt models with reusable macros

Created analytics-ready fact and dimension tables

Added data quality tests and documentation

Maintained clean schema separation (Bronze, Silver, Gold)
