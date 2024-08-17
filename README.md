# Global-Terrorism-Dataset-Analysis
This repository contains an analysis of the Global Terrorism Dataset and a dashboard visualizing the findings.
The project was completed using Jupyter Notebook and includes data acquisition, preprocessing, analysis, and visualization.

# Project Overview
This project aims to analyze global terrorism incidents using the Global Terrorism Dataset.
The analysis includes data preprocessing, statistical analysis, and visualization to identify trends,
most affected regions, attack types, and more.
The project also includes a performance comparison between Pandas and Dask for handling large datasets.

# Project Structure
- `notebooks/`: Jupyter notebooks containing the analysis and visualizations.
- `dashboard/`: Files related to the dashboard visualization.
- `data/`: The cleaned dataset used for analysis.
- `report.pdf`: The PDF report summarizing the findings from the analysis.

# Installation
To run the notebooks or dashboard locally, you'll need the following Python libraries:
- Pandas
- Numpy
- Dask
- Matplotlib
- Seaborn
- Power BI to open the dashboard

# Analysis and Findings
The analysis covers several aspects of the dataset, including:
## Most Frequent Values in Categorical Columns:
- Most afected region: South Asia
- Most affected country: Afghanistan
- Most attack type used: Bombing/Explosion
- Most Weapon type used: Explosives
- Most terrorist group: Taliban
- Most affected target: Private Citizens & Property
## Most Frequent Values in Numeric Columns:
Most frequent year for attacks: 2015

## Trends in terrorist attacks over the years.
## Relationship between the number of casualties and the type of attack.

# Key Visualizations
Line plot showing the trend of terrorist attacks over the years.
![Capture1](images/photo.png)

Bar plot of the number of attacks by region and by country.
Heatmap to visualize correlations between different features.
Scatter plot showing the relationship between the number of casualties and the type of attack.

# Dashboard
The dashboard provides an interactive way to explore the dataset and visualize the findings. 
It includes:
Overview Page
Attackes Page: It describes number of attacks by region, country, year, attack type.
Success Rate Page: It describes Success rate of attacks by region, country, year, group name, target, weapon.
Killed Page: It describes number of killed by region, country, year, nationality, group name, weapon.
