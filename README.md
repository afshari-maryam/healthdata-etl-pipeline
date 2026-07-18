# healthdata-etl-pipeline

End-to-end ETL pipeline that extracts raw health/sensor data, cleans and
transforms it with Python (pandas), and loads it into a relational
database (MySQL/MariaDB) for analytics and reporting.

## Goals
- Practice real-world data modeling and normalization
- Build clean, maintainable Python scripts for data processing
- Write analytical SQL queries (joins, aggregations, window functions)

## Tech Stack
- Python (pandas, SQLAlchemy)
- MySQL / MariaDB
- Docker (for local database setup)

## Status
✅ Complete

## Structure (planned)
- `extract/` — scripts to pull raw data
- `transform/` — cleaning and modeling logic
- `load/` — database loading scripts
- `sql/` — schema and analytical queries
- `docker-compose.yml` — local dev environment
