# 🚕 Rides Data Ingestion & Analytics Platform

## Overview
This project simulates a real-world ride-hailing analytics system.
It ingests raw ride data, validates and cleans it using Python,
stores it in PostgreSQL, and performs analytical queries for business insights.

The project focuses on Python, SQL, and PostgreSQL, with a strong emphasis
on data engineering and database administration fundamentals.

## Tech Stack
- Python (data ingestion & cleaning)
- PostgreSQL (relational database)
- SQL (analytics & optimization)
- pandas (CSV handling)
- psycopg2 (PostgreSQL connector)

## Architecture
Raw Data (Kaggle) → Python Ingestion → Data Validation → PostgreSQL → Analytics Queries

## Features
- Batch ingestion of ride data
- Data quality validation & logging
- Normalized PostgreSQL schema
- Performance-optimized analytical queries
- Indexing & partitioning strategies

## Database Design
- drivers
- passenger
- rides

## Analytics Performed
- Peak ride hours
- Total rides per day
- Average fare per ride
- Average fare per km
- Daily revenue trends
- Driver performance ranking
- Ride cancellation analysis

## Performance Optimization
- Index tuning using EXPLAIN ANALYZE
- Date-based partitioning on rides table

## How to Run
1. Create PostgreSQL database
2. Run `schema.sql`
3. Install dependencies:
  pip install -r requirements.txt
5. Run ingestion script:
  python ingestion/ingest_rides.py

## Future Improvements
- Automate ingestion using cron or airflow
- Store raw data separately from processed data
- Real-time streaming (Kafka)
- Add cloud deployment using AWS RDS

## Author
Maira Rehman
Aspiring Database Admin / Data Engineer
