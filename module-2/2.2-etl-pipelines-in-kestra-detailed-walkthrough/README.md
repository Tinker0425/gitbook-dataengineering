---
cover: >-
  https://images.unsplash.com/photo-1631195701773-01810c4985b3?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHwxfHxwdXJwbGUlMjBmbG93fGVufDB8fHx8MTczODUzODkwMHww&ixlib=rb-4.0.3&q=85
coverY: 0
---

# 2.2 - ETL Pipelines in Kestra: Detailed Walkthrough

This week, we're gonna build ETL pipelines for Yellow and Green Taxi data from NYC’s Taxi and Limousine Commission (TLC). You will:

1. Extract data from [CSV files](https://github.com/DataTalksClub/nyc-tlc-data/releases).
2. Load it into Postgres or Google Cloud (GCS + BigQuery).
3. Explore scheduling and backfilling workflows.

This introductory flow is added just to demonstrate a simple data pipeline which extracts data via HTTP REST API, transforms that data in Python and then queries it using DuckDB. For this stage, a new separate Postgres database is created for the exercises.
