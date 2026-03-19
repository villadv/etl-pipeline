# Portfolio Project Summary

## Short Version

I built a medallion-style ETL pipeline in Python and pandas that processes mixed-format transaction data, standardizes inconsistent records across Bronze, Silver, and Gold layers, and produces analytics-ready reporting outputs.

## Website / Project Post Version

This project showcases an end-to-end ETL pipeline designed with a Bronze, Silver, and Gold architecture. In the Bronze layer, I ingested mixed-format CSV and JSON-based transaction files into a unified raw dataset while preserving source metadata and allowing for schema flexibility. In the Silver layer, I cleaned and standardized the dataset by handling nulls, normalizing data types, cleaning categorical text, and consolidating noisy values into consistent analytical fields. In the Gold layer, I produced business-facing summary tables such as team performance, player performance, and world difficulty.

The project highlights practical data engineering skills including schema-flexible ingestion, data quality improvement, type conversion, text normalization, parquet generation, and packaging a notebook-driven workflow into a reproducible GitHub project.

## Suggested Screenshot Layout

### Bronze Screenshot

Use `assets/bronze.png`

Caption:
`Bronze layer ingesting mixed CSV and JSON-based source files into a unified raw dataset with load metadata.`

### Silver Screenshot

Use `assets/silver.png`

Caption:
`Silver layer completion showing the cleaned parquet output and a schema-consistent dataset with standardized types and no critical nulls.`

### Gold Screenshot

Use `assets/gold.png`

Caption:
`Gold layer generating analytics-ready performance summaries, including team-level and player-level reporting outputs.`

## Resume Bullet Version

- Built a Python/pandas ETL pipeline using medallion architecture to process 48,000 records across mixed CSV and JSON inputs into Bronze, Silver, and Gold analytical layers.
- Preserved raw schema flexibility in Bronze, then standardized nulls, booleans, numeric types, and noisy categorical text in Silver.
- Produced analytics-ready parquet outputs for team, player, and world-level reporting and packaged the project for reproducible execution in GitHub.

## GitHub Description Version

Medallion-style ETL pipeline in Python and pandas that ingests mixed-format raw data, standardizes it through Bronze, Silver, and Gold layers, and produces analytics-ready parquet outputs for reporting.
