# ETL Pipeline Builder — managed-agent template

Designs data transformation pipelines from schema descriptions, with built-in error handling, validation, and idempotent load strategies.

## What it does

1. Accepts source and destination schema descriptions with sample data
2. Maps source fields to destination fields with type coercion rules
3. Designs transformation logic for derived fields and aggregations
4. Implements validation rules to catch data quality issues early
5. Adds error handling with dead-letter queues for failed records
6. Generates pipeline code (SQL, Python/dbt, or Airflow DAGs) with idempotent load patterns
