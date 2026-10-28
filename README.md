## Online Retail Data Cleaning and Quality Analysis

# Project Overview

This project focuses on cleaning and assessing the data quality of an online retail transaction dataset using Python and Pandas. It identifies missing values, duplicate records, and unusual transaction values to better understand the quality and reliability of the data.

# Dataset

The dataset contains transactions from a UK-based online retailer between December 2010 and December 2011.

Source: "UCI Online Retail Dataset" (https://archive.ics.uci.edu/dataset/352/online+retail)

# Tools and Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

# Key Tasks

- Explored the dataset and examined its structure.
- Identified and removed duplicate records.
- Analyzed missing values.
- Standardized product descriptions by removing extra whitespace.
- Investigated zero and negative unit prices.
- Examined negative quantities and potential cancellation transactions.
- Generated data quality reports and visualizations.

# Key Findings

- Original dataset: 541,909 rows.
- Records after duplicate removal: 536,641.
- Missing customer IDs: 135,037 rows.
- Missing product descriptions: 1,455 rows.
- Negative quantities: 10,587 rows.

Unusual values were investigated rather than automatically removed, preserving potentially meaningful transaction information.

# Project Files

- "data_cleaning.ipynb" — Data cleaning and quality analysis workflow.
- "online_retail_cleaned.csv" — Cleaned dataset.
- "data_quality_report.csv" — Column-level data quality report.
- "data_quality_summary.csv" — Summary of data quality issues.
- PNG files — Data quality visualizations.

# Objective

To demonstrate practical data cleaning, exploratory data analysis, and data quality assessment using Python.
