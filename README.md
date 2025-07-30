COVID-19 Global Data Tracker

Project Overview

This project analyzes global COVID-19 data using Python, pandas, and visualization libraries to identify trends in cases, deaths, and vaccination progress across countries. The project provides a comprehensive data analysis report in a Jupyter Notebook with visualizations and narrative insights.

Objectives

- Import and clean COVID-19 global data
- Analyze time trends (cases, deaths, vaccinations)
- Compare metrics across countries/regions
- Visualize trends with charts
- Communicate findings in a structured report

Data Source

Dataset: [Our World in Data - COVID-19 Data](https://github.com/owid/covid-19-data/tree/master/public/data)

File used: `owid-covid-data.csv`  
Key Columns Analyzed

- `date`
- `location`
- `total_cases`
- `total_deaths`
- `new_cases`
- `new_deaths`
- `total_vaccinations`
- `population`

Data Cleaning Steps

- Filtered selected countries: Kenya, USA, India
- Converted `date` to datetime format
- Handled missing values using `fillna()` and replacement
- Calculated new metrics: `death_rate = total_deaths / total_cases`

Exploratory Data Analysis

- Line charts for total cases and deaths over time
- Bar charts for top countries by total cases
- Comparisons of daily new cases and vaccinations
- Vaccination trends and percentages analyzed per country

 Visual Tools Used

- `pandas`
- `matplotlib`
- `seaborn`
- `plotly.express` for choropleth maps
- `geopandas` for spatial visualizations

Sample Insights

- The USA had the highest total cases and deaths globally.
- India showed a rapid rise in vaccinations from mid-2021.
- Kenya’s peak cases and death rates were significantly lower compared to global hot zones.
- Death rate declined as vaccination increased in most countries.



