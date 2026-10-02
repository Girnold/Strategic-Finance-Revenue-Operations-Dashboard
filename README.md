# Strategic Finance: Revenue & Operations Dashboard

## Project Overview
This project simulates an end-to-end data engineering and analytics workflow. It demonstrates the ability to architect synthetic financial datasets, build automated Python cleaning pipelines, extract strategic insights using advanced SQL, and visualize macroeconomic trends in Tableau.

## Business Value
This project automates the transition from raw transaction logs to actionable executive insights by:
* Automating Data Prep: Reducing manual cleaning to a single Python script utilizing pandas and numpy.
* Isolating Inefficiencies: Identifying statistically significant operational cost anomalies down to the specific region and transaction using PostgreSQL Window Functions and CTEs.
* Driving Decisions: Providing a high-level Tableau dashboard to track Net Profit Margins across 4 global regions and 5 departments.

## Technology Stack
* Python: pandas, numpy
* SQL: PostgreSQL, CTEs, Window Functions, Statistical Analysis
* Data Visualization: Tableau

## Repository Structure
* data_pipeline.py: Python script generating synthetic data, handling nulls, and computing margins.
* advanced_analytics.sql: SQL queries calculating YoY growth, rolling averages, and Z-score anomaly detection.
* raw_financial_data.csv: Uncleaned baseline dataset.
* cleaned_financial_data.csv: Output dataset ingested into BI tool.
* Dashboard_Preview.png: Static export of the final Tableau Dashboard.
