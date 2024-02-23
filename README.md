# Chiller System Analysis Dashboard

Welcome to the Chiller System Analysis project! This repository contains the code and documentation for investigating the issue of "low chilled water delta T" in a chiller system. In this analysis, we aim to understand the factors contributing to the small temperature difference between the chilled water supply and return, which is less than 3 degrees Celsius.

## Overview

The analysis includes:
- Analysis of data collected during chiller operation (Comp_Power > 10)
- Examination of the issue of "low chilled water delta T" in the chiller system
- Investigation into the relationship between chilled water supply and return temperatures, flow rate, and chiller operation
- Identification of patterns and anomalies to elucidate potential causes of the observed phenomenon

### Data Provided:
The dataset comprises readings for chilled water supply temperature (CHWS_Temp), chilled water return temperature (CHWR_Temp), chiller power consumption (Comp_Power), and chilled water flow rate (Flow_Rate). Data is available for each of the 4 chillers in the system (ACPC 1 to 4), with separate temperature, power, and flow rate sensors for each chiller.

### Data Preparation
- Utilized Python and Pandas to clean, transform, and prepare the dataset for analysis.
- Supplementary Jupyter Notebooks in the `Chiller Water System Data` directory showcase our data analysis, pre-processing steps, and data exploration that contributed to the subsequent visualizations.

### Tableau Visualizations
- Created using Tableau, offer an interactive exploration of the "low chilled water delta T" issue. 
- Focusing on visualizing temperature readings during chiller operation and exploring correlations with flow rate, we aim to provide valuable insights to optimize the chiller system's performance and address the low chilled water delta T problem.

### Tableau Dashboards Online

Explore the interactive Tableau dashboards online:
[https://public.tableau.com/app/profile/kel.l8094/viz/ChilledWaterDeltaTAnalysis_Kelvis/Dashboard12?publish=yes]

![Dashboard Preview](https://github.com/kelvislcy/ChillSystemAnalysis-Investigating-Chiller-System-Performance/blob/main/Chiller%20System%20Analysis%20Dashboard.gif?raw=true
)

## Files Included

- `chiller_data_W.xlsx`: Cleaned and processed dataset used for Tableau visualizations.
- `Chilled Water Delta T Analysis.twbx`: Tableau workbook file containing interactive dashboards.
