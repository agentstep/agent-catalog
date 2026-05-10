# SQL Analyst — managed-agent template

Takes natural language questions about data, writes optimized SQL queries, executes them, explains results in plain English, and exports to CSV.

## What it does

1. Accepts a natural language question about the data (e.g., "What were our top 10 customers by revenue last quarter?")
2. Inspects the database schema to understand available tables and relationships
3. Writes an optimized SQL query with proper JOINs, aggregations, and filters
4. Executes the query and validates the results make sense
5. Explains the findings in plain English with key insights highlighted
6. Exports results to CSV or formatted table on request
