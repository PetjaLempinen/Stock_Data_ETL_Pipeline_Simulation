# Stock Data ETL Pipeline Simulation

This project demonstrates how to extract structured financial data, inject realistic inconsistencies and missing values, and transform it into a clean, SQL-ready format.
The pipeline includes: Data scrambling, data cleaning/transforming, SQL integration and Visualization using histograms.

# Project Overview

- Extract: Raw stock data imported from CSV
- Scramble: Injected noise, missing values, and inconsistent formats to simulate real-world messiness
- Transform: Cleaned and standardized data using pandas (e.g. date parsing, numeric conversion, NaN handling)
- Load: Final dataset loaded into MySQL (`nordea_etl_project` database)
- Visualize: Histograms of price, volume, and daily change to explore distribution and volatility

# Technologies Used

- Python (pandas, matplotlib, numpy)
- MySQL (via phpMyAdmin)
- Jupyter Notebook
- GitHub







