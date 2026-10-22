# U.S. Airline On-Time Performance Analysis

## Overview

An end-to-end data analysis of U.S. airline on-time performance using flight records from the U.S. Bureau of Transportation Statistics (BTS). The project follows the full analytics process — data cleaning, SQL analysis, exploratory data analysis, visualization, and recommendations — to identify what drives flight delays and where airlines and airports can reduce them.

## Business Questions

- Which carriers, airports, and routes have the worst arrival delays, and how consistent are they over time?
- How do delays vary by time of day, day of week, and season?
- What share of delays comes from late-arriving aircraft versus carrier, weather, and air-system causes?
- Which routes would benefit most from schedule buffers or operational changes?

## Data Source

U.S. Bureau of Transportation Statistics, Airline On-Time Performance data (transtats.bts.gov) — flight-level records including scheduled and actual departure/arrival times, delay minutes by cause, carrier, origin, and destination.

## Process

1. **Data cleaning (Python, pandas):** standardize carrier and airport codes, handle missing and cancelled-flight records, validate delay fields, and build a clean analysis table.
2. **SQL analysis:** aggregate delay metrics by carrier, airport, route, and time period; rank delay drivers.
3. **Exploratory analysis (Python):** examine distributions, trends, and outliers across time and geography.
4. **Visualization (Matplotlib, Power BI):** charts and a dashboard of delay trends, worst-performing routes, and delay-cause breakdowns.
5. **Findings and recommendations:** summarize the largest delay drivers and propose operational changes for the highest-impact routes.

## Tools

Python, pandas, Jupyter Notebook, SQL, Matplotlib, Power BI, Git, GitHub

## Repository Structure

- `data/` — raw and cleaned datasets
- `notebooks/` — cleaning and exploratory analysis notebooks
- `sql/` — analysis queries
- `dashboards/` — Power BI dashboard files and exports
