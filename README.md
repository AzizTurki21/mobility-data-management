# Mobility Data Management Project

An individual Advanced Data Management course project at the University of Milano-Bicocca. It explores relational, document, Spark, and graph-oriented approaches to mobility data.

## What is in the repository

- **Report:** [ADM_report.pdf](ADM%20project/ADM_report.pdf)
- **Synthetic data generator:** `ADM project/project/generate_data.py` creates users, stations, trips, and trip events across Italian cities. It accepts a seed for repeatable generation.
- **Relational phase:** SQLite schema and queries under `ADM project/project/pt1_relational/`
- **Spark phases:** query work under `ADM project/project/spark_pt1/` and `ADM project/project/spark_pt2/`
- **Benchmark:** `ADM project/project/benchmark.py` contains timing code for comparing data query approaches
- **Graph phase:** graph-related work is under `ADM project/project/graph_pt2/`

The project code and report document the course work. The repository does not currently include a single environment setup covering the SQLite, MongoDB, Spark, and graph components, so check the scripts and report for the requirements of each phase.

## Main project files

- `ADM project/project/generate_data.py`
- `ADM project/project/benchmark.py`
- `ADM project/project/pt1_relational/schema.py`
- `ADM project/project/pt1_relational/queries.py`
- `ADM project/project/spark_pt1/query.py`
- `ADM project/project/spark_pt2/queries.py`

