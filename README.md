# Sydney Public Transport Reliability Pipeline

Analytics engineering project that ingests, models, and analyzes real-time public transport data from Transport for NSW to measure route reliability and on-time performance. 

This project combines static GTFS schedule data with GTFS-realtime feeds to reconstruct actual service performance from incomplete and evolving data.

## Tech Stack
- Snowflake (data warehouse)
- dbt (data transformation & modeling)
- Python (data ingestion)
- GTFS / GTFS-realtime (data sources)
