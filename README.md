# ACPML - EDA Assignment - EDA on NYC Taxi Records - BO and Dataset

## Walkthrough

This repository contains the starter materials for an Exploratory Data Analysis (EDA) assignment on New York City yellow taxi trip records. Download the starter Jupyter Notebook from the `notebooks/` folder and perform all analyses inside that notebook.

## Problem Statement

In this case study, you'll be learning Exploratory Data Analytics with the help of a dataset on yellow taxi rides in New York City. Taxis play a crucial role in New York City's urban transport network. With the city's dynamic environment, taxi companies need to continuously adapt and optimise their operations to meet changing demand patterns, ensure profitability, and enhance customer satisfaction.

As an analyst at an upcoming taxi operation in NYC, you are tasked with using the 2023 taxi trip data to uncover insights that could help optimise taxi operations. The goal is to analyse patterns in the data that can inform strategic decisions to improve service efficiency, maximise revenue, and enhance passenger experience. The yellow taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemised fares, rate types, payment types, and driver-reported passenger counts.

## Business Objective (BO) and Dataset

- Business objective: Analyse 2023 yellow taxi trip records to identify operational patterns and opportunities to optimise taxi allocation, reduce idle time, improve service coverage, and increase revenue per trip.
- Dataset format: Parquet (.parquet)
- Temporal coverage: Full dataset available from 2009 to 2024; for this assignment use only 2023 data.
- File layout: The 2023 data is provided as one parquet file per month (12 files total). Do not commit large raw data files to this repository; instead place them under a local `data/` directory or use external storage. See the notebook for recommended download and processing steps.

Along with the trip records, the repository assumes access to geometric data dividing the city into taxi zones (shapefile, .shp). This shapefile will be used for spatial joins and map visualisations — instructions for working with shapefiles are included in the starter notebook.

The data was collected and provided to the NYC Taxi and Limousine Commission (TLC) by technology providers (e.g., vendors and taxi-hailing apps).

## Starter Notebook

Next, download the starter Jupyter Notebook from `notebooks/NYC_Taxi_EDA.ipynb`. The notebook contains all tasks, instructions, and code cells to guide your analysis. Perform all analyses in the starter notebook only.

Notes:
- Recommended Python version: 3.10
- Recommended libraries: pandas, numpy, matplotlib, seaborn, geopandas, folium, scikit-learn
- Do not commit large raw data files to this repository. If you need a small sample for testing, create a sampled CSV/parquet and place it under `data/sample/`.

If you want, I can add a README section with explicit download commands (curl/wget, Kaggle CLI) and a small sample file to run the notebook out-of-the-box. Reply if you want me to add those files or further structure the repository.
