# Mobility Data Management Project

An individual Advanced Data Management course project at the University of Milano-Bicocca. It explores relational, document, Spark, and graph-oriented approaches to mobility data.

## What is in the repository

- **Report:** [ADM_report.pdf](ADM%20project/ADM_report.pdf)
- **Synthetic data generator:** `generate_data.py` creates users, stations, trips, and trip events across Italian cities. It accepts a seed for repeatable generation.
- **Relational phase:** SQLite schema and queries under `pt1_relational/`
- **Spark phases:** query work under `spark_pt1/` and `spark_pt2/`
- **Benchmark:** `benchmark.py` contains timing code for comparing data query approaches
- **Graph phase:** graph-related work is under `graph_pt2/`

The project code and report document the course work. The repository does not currently include a single environment setup covering the SQLite, MongoDB, Spark, and graph components, so check the scripts and report for the requirements of each phase.

## Main project files

- `generate_data.py`
- `benchmark.py`
- `pt1_relational/schema.py`
- `pt1_relational/queries.py`
- `spark_pt1/query.py`
- `spark_pt2/queries.py`

