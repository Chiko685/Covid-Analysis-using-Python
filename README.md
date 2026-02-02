## Global COVID-19 Data Analysis and Visualization
This project provides an in-depth analysis of the global COVID-19 pandemic using data sourced from Worldometer and other curated datasets. The analysis focuses on identifying trends, comparing country-level impacts, and visualizing critical health metrics using Python's data science ecosystem.

## 📊 Key Features & Analysis

### 1. Global Metrics & Trends

a. Maximum Impact Identification: Analysis of which countries reached the highest levels of total cases, deaths, recoveries, and active cases.

b. Time-Series Tracking: Visualizing the global trend of COVID-19 over time, specifically tracking confirmed cases, new cases, deaths, and recoveries by date.

c. WHO Region Analysis: Breakdown of metrics like total cases and deaths across different WHO regions.

### 2. Specialized Ratios & Insights

a. Testing Capacity: Analysis of the "Population to Tests Done Ratio" to identify countries with potential testing capacity challenges relative to their population size.

b. Severity Ratios:

- Deaths to Confirmed Ratio: Measures the mortality rate among confirmed cases.
- Serious to Deaths Ratio: Insights into the outcome for critical and serious patients.
- Tests to Confirmed Ratio: Evaluates the efficiency and reach of testing programs.

### 3. Benchmarking "Worst-Hit" Regions

a. Top 20 Analysis: Focused visualizations on the 20 countries most affected by max confirmed cases, deaths, and active cases.

b. Interactive Visualizations: Use of treemaps, density heatmaps, and donut charts to represent the hierarchy and distribution of cases globally.

## 🛠️ Tech Stack

- Language: Python
  
- Libraries:
  a. pandas & numpy (Data cleaning and manipulation)

  b. plotly.express (Interactive visualizations and time-series plots)

  c. seaborn & matplotlib (Static statistical visualizations)

  d. os (File system operations)

## 📁 Dataset Overview

### The analysis utilizes several CSV files, including:

- worldometer_data.csv: Latest snapshot of global statistics.
- day_wise.csv: Time-series data for daily global trends.
- full_grouped.csv: Country-level data grouped by date.
- country_wise_latest.csv: Most recent metrics per country.

## 🚀 Getting Started

### Dependencies: Ensure you have the required libraries installed:


- pip install pandas numpy plotly seaborn matplotlib
- Execution: Run the Jupyter Notebook Covid analysis.ipynb.

Data Path: Update the path variable in the notebook to point to your local directory containing the CSV files.

*** Note: This analysis was performed on a dataset capturing trends primarily through 2020 and early 2021.
