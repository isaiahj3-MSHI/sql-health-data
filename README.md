# SQL for Health Data

My SQL practice repo as I learn health informatics. Queries run against synthetic patient data (Synthea CSV export) using DuckDB.

## Topics
- [ ] SELECT, WHERE, ORDER BY
- [ ] Aggregates and GROUP BY (e.g. patients per condition)
- [ ] JOINs across patients, encounters, conditions and observations
- [ ] Window functions (e.g. most recent lab per patient)
- [ ] CTEs for multi-step cohort queries

## Layout
```
queries/     .sql files, one per exercise, with the question as a comment
data/        local data (git-ignored; synthetic only)
```

## Tools
SQL, DuckDB, SQLite, DBeaver

## Data note
Only synthetic (Synthea) data. No real patient information.
