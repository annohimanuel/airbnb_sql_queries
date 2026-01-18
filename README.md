# Advanced SQL Queries — NYC Airbnb (SQLite)

## Overview
This project practices intermediate-to-advanced SQL using the NYC Airbnb 2019 dataset.
Workflow: CSV → pandas → SQLite (`airbnb.db`) → SQL analysis queries.

## Skills Demonstrated
- Aggregations, GROUP BY, ORDER BY, LIMIT
- Date functions in SQLite (`strftime`, `julianday`)
- CTEs (`WITH`) for reusable aggregations
- Window functions (`RANK() OVER (...)`)
- KPI-style analysis (host performance, price trends, variability, recency, revenue)

## Key Analyses
- Top hosts by average reviews per month + total reviews
- Monthly price trends and listing counts
- Neighborhoods with highest price variability (max-min)
- Days since last review (recency)
- Top hosts by estimated revenue and revenue rank

## Data
Dataset: NYC Airbnb 2019 (Kaggle)  
Download and place the file in the project root as:
`AB_NYC_2019.csv`

> Note: The dataset is not included in this repo.

## How to Run (Google Colab)
1. Upload `AB_NYC_2019.csv` to your Colab session
2. Open `Advanced SQL Queries.ipynb`
3. Run all cells

## Output
The notebook prints result tables for each task and closes the SQLite connection at the end.
