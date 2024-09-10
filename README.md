# Google Playstore Dataset Analysis with PySpark - Databricks

This project demonstrates a basic Exploratory Data Analysis (EDA) on Google Playstore Dataset, [available on Kaggle](https://www.kaggle.com/datasets/lava18/google-play-store-apps), using PySpark within Databricks. The goal of this project is to showcase the capabilities and usability of PySpark for manipulating data.

## Project Overview

In this project, I used the Databricks Community Edition to:
- Perform an EDA on the Google Playstore Dataset.
- Clean the data using PySpark.
- Create visualizations and insights directly with the Databricks SQL, via PySpark session view function.

All source files, including the `.dbc` notebook and the exact dataset used, are included in this repository for future reference.

## How to Replicate

To replicate this analysis:
1. Go to your Databricks account.
2. Import the notebook using the `.dbc` file provided in this repository.
3. Upload the `.csv` file to your Databricks workspace and create a table from it. This step is necessary to re-run the notebook and replicate the analysis.

## Files in this Repository
- **PySpark - Google Play Store.dbc**: Databricks notebook containing the EDA and SQL queries.
- **PySpark - Google Play Store.ipynb**: Local notebook to check the functions used. It won't run the SQL cells.
- **googleplaystore.csv**: The dataset used for the analysis.

## Notes
- This project was conducted using Databricks Community Edition, which provides free access to Databricks functionalities. Feel free to use the notebook and dataset to explore and modify the analysis according to your needs.