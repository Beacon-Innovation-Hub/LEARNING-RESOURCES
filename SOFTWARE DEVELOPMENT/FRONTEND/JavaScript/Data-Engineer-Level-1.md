Level 1 — Data Engineering Foundations

  Build the programming, operating-system, data-format, ingestion, and
  reliability foundations required for data engineering.

Stage: Foundational
Prerequisite: Common Data Foundations
Next: Level 2 — Databases & Data Processing

← Back to Data Engineer Roadmap

------------------------------------------------------------------------

Learning Outcomes

By the end of this level, you should be able to:

-   ☐ Explain the role of a Data Engineer
-   ☐ Distinguish Data Engineering, Data Analysis, and Data Science
-   ☐ Explain ETL and ELT
-   ☐ Work with CSV, JSON, JSONL, and Parquet
-   ☐ Build reusable Python ingestion scripts
-   ☐ Read data from files and APIs
-   ☐ Validate incoming data
-   ☐ Use Linux/command-line tools
-   ☐ Use Git professionally
-   ☐ Log and handle pipeline failures

1. Introduction to Data Engineering

A Data Engineer builds systems that collect, move, validate, transform,
and store data for analysts, scientists, applications, and
decision-makers.

    DATA SOURCES
         ↓
    INGESTION
         ↓
    VALIDATION
         ↓
    TRANSFORMATION
         ↓
    STORAGE
         ↓
    CONSUMPTION

Main Resource

[Data Engineering Zoomcamp]

Watch: Data Engineering Zoomcamp

Understand

-   ☐ Data pipelines
-   ☐ Data sources and sinks
-   ☐ Structured, semi-structured, and unstructured data
-   ☐ Batch vs streaming
-   ☐ ETL vs ELT
-   ☐ Data quality
-   ☐ Data warehouses
-   ☐ Data lakes
-   ☐ Reproducibility
-   ☐ Idempotency

------------------------------------------------------------------------

2. Python for Data Engineering

Focus on Python as an engineering tool rather than only an analysis
language.

Learn

-   ☐ Functions and modules
-   ☐ Virtual environments
-   ☐ File handling
-   ☐ Exceptions
-   ☐ Logging
-   ☐ Type hints
-   ☐ Environment variables
-   ☐ pathlib
-   ☐ datetime
-   ☐ json
-   ☐ csv
-   ☐ HTTP requests
-   ☐ Basic unit testing
-   ☐ Reusable scripts

3. Data Formats

Compare:

    CSV
    JSON
    JSON Lines
    Parquet
    Avro — conceptual introduction

For each format investigate:

-   schema support
-   compression
-   row vs column orientation
-   human readability
-   interoperability
-   analytical performance

4. Linux & Command Line

Practice:

    pwd
    ls
    cd
    mkdir
    cp
    mv
    rm
    cat
    head
    tail
    grep
    find
    wc
    sort
    uniq
    curl
    wget

Also learn paths, permissions, pipes, environment variables, processes,
and basic shell scripts.

5. Git & Reproducibility

-   ☐ Repository structure
-   ☐ .gitignore
-   ☐ Commits
-   ☐ Branches
-   ☐ Pull requests
-   ☐ Code review
-   ☐ README documentation
-   ☐ Dependency files
-   ☐ Configuration separate from code
-   ☐ Never commit secrets

------------------------------------------------------------------------

BIH Scenario — Beacon Technologies Data Intake

Mr KP Ntshalintshali, a senior manager at Beacon Technologies, requests
a reliable intake system for operational information.

Beacon Technologies receives:

    customer_accounts.csv
    service_requests.json
    device_events.jsonl
    monthly_usage.csv

Ms Aseza Mtshali, a senior at ZuluTech Collective, will later use the
prepared data, but the incoming files contain inconsistent naming,
missing fields, invalid dates, duplicates, and different structures.

Your task is to build the first reliable data intake layer.

BIH Lab 01 — Inspect Raw Data

-   ☐ Identify formats
-   ☐ Count records
-   ☐ Inspect fields and types
-   ☐ Find missing values
-   ☐ Find duplicates
-   ☐ Inspect dates
-   ☐ Identify invalid records
-   ☐ Record source metadata

    data/
    ├── raw/
    ├── rejected/
    └── processed/

  Raw source data must remain unchanged.

BIH Lab 02 — Python Ingestion

Build:

    Read Source
        ↓
    Validate Structure
        ↓
    Standardize Names
        ↓
    Convert Types
        ↓
    Separate Invalid Records
        ↓
    Write Valid Records
        ↓
    Log Results

Never silently discard data.

BIH Lab 03 — API Ingestion

Assume:

    GET /api/service-requests

Demonstrate:

-   ☐ HTTP requests
-   ☐ Status-code checking
-   ☐ JSON parsing
-   ☐ Pagination
-   ☐ Error handling
-   ☐ Retry concepts
-   ☐ Ingestion timestamps
-   ☐ Raw-response preservation

------------------------------------------------------------------------

Level 1 Challenge — Reliable Intake

Mr Ntshalintshali asks:

  Can we trust that tomorrow’s files will be processed the same way as
  today’s?

Build a reusable ingestion application.

    level-1-data-intake/
    ├── data/
    │   ├── raw/
    │   ├── processed/
    │   └── rejected/
    ├── src/
    │   ├── ingest.py
    │   └── validate.py
    ├── logs/
    ├── tests/
    ├── requirements.txt
    ├── .gitignore
    └── README.md

Assessment

  Area                          Weight
  --------------------------- --------
  Python                           25%
  Data formats                     15%
  Validation/error handling        20%
  File/API ingestion               15%
  Git/project structure            10%
  Documentation                    15%

Progression requirement: 70%

The assessor should deliberately provide malformed input to test
reliability.

Continue to Level 2 →
