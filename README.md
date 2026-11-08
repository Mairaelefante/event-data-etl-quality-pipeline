![Event Data ETL & Quality](cover.svg)

# Event Data ETL Quality Pipeline

**Python ETL · Event data validation · Logging · SQL schema design**

A compact data-engineering pipeline covering event-data extraction, cleaning, validation, traceable logging and SQL-oriented schema design.

**[Source code](event-data-etl-quality-pipeline/src/) · [Tests](event-data-etl-quality-pipeline/tests/) · [SQL](event-data-etl-quality-pipeline/sql/) · [Full project documentation](event-data-etl-quality-pipeline/README.md)**

## What it demonstrates

- Reading raw event records into pandas.
- Standardizing field names and parsing timestamps.
- Handling missing and duplicate records.
- Creating processed output with reproducible pipeline logging.
- Separating source code, test cases, SQL and documentation.

## Run locally

The implementation is inside the nested `event-data-etl-quality-pipeline/` directory. From the repository root:

```bash
cd event-data-etl-quality-pipeline
python3 -m pip install -r requirements.txt
python3 src/etl_pipeline.py
```

Run the tests with:

```bash
python3 -m pip install pytest
python3 -m pytest
```

This is a portfolio ETL demonstration, not a production data platform. See the project directory for inputs and assumptions.
