# Shopping Festival Sales Pattern Analysis
### Exploratory Data Analysis and Sales Trend Visualization of Shopping Festival Transactions

---

## Overview

What can transaction data reveal about shopping behaviour and sales performance?

This project explores a shopping festival dataset to uncover patterns across product categories, regions, and time. Using Python-based Exploratory Data Analysis (EDA), it transforms raw transaction records into summaries and visualizations that make sales patterns easier to understand.

The focus is on **turning raw data into meaningful insights** through data cleaning, statistical exploration, aggregation, and visualization.

## Project at a Glance

| Component | Details |
|---|---|
| Domain | Data Analytics |
| Language | Python |
| Environment | Google Colab / Jupyter Notebook |
| Dataset | `sales_data.csv` |
| Records | 20,000 |
| Features | 17 columns |

## The Analysis Pipeline

`Raw Data` → `Inspection` → `Cleaning` → `Transformation` → `Analysis` → `Visualization`

Each stage builds on the previous one to prepare the dataset for meaningful exploration.

## What This Project Explores

**01 — Numerical Exploration**

Using NumPy arrays to perform calculations, indexing, slicing, and statistical operations on numerical data.

**02 — Data Manipulation**

Using Pandas to inspect records, filter transactions, sort values, and summarize data by category.

**03 — Data Cleaning and Wrangling**

Checking missing values and duplicates, transforming columns, standardizing values, and reshaping data for analysis.

**04 — Time-Based Analysis**

Examining sales across dates and aggregating transactions into monthly and quarterly summaries.

**05 — Visual Storytelling**

Using charts to explore category-wise sales, regional performance, sales distributions, and relationships between sales and profit.

## Tools Behind the Analysis

| Library | Role |
|---|---|
| NumPy | Numerical computing and array operations |
| Pandas | Data manipulation, cleaning, and aggregation |
| Matplotlib | Plotting and chart customization |
| Seaborn | Statistical data visualization |

## Getting Started

Run the project using Google Colab or Jupyter Notebook.

1. Clone or download this repository.
2. Open `Shopping_Festival_Sales_Pattern_Analysis.ipynb`.
3. Make `sales_data.csv` accessible to the notebook.
4. If necessary, update the dataset path in the code.
5. Execute the cells in order to reproduce the analysis.

Required libraries:

```python
numpy
pandas
matplotlib
seaborn
```

Install them if needed:

```bash
pip install numpy pandas matplotlib seaborn
```

## Dataset Notes

The dataset was downloaded from Kaggle and contains 20,000 transaction records across 17 columns. The recorded order dates span **1 January 2023 to 31 December 2025**.

The available fields cover order details, customer and product information, categories, regions, quantities, sales, profit, payment methods, and ratings.

## Project Outcome

The project demonstrates a complete exploratory workflow, from inspecting and preparing transaction data to summarizing patterns and communicating findings through visualizations.

It also provides practical experience with NumPy, Pandas, data wrangling, time-series aggregation, and statistical plotting.

---

*Built as a Python-based data analytics project focused on exploring shopping festival transactions and communicating patterns through data.*
