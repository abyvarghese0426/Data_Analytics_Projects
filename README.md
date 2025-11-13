# Data_Analytics_Projects
DA_Projects_by_Aby_Varghese

Climate Watch : Air Quality and Pollution Trends in Indian Cities
Problem Statement

Air pollution is a major public health concern in India, with frequent episodes of poor air quality affecting millions across urban and regional areas. Understanding the variability of the Air Quality Index (AQI) across different cities and over time is critical to inform policy decisions. This project addresses the need for clear, reproducible analysis of air quality patterns across Indian cities using publicly available datasets.

Aim

To conduct a step-by-step exploratory data analysis (EDA) of air quality across Indian cities over recent years, using the "air-quality-index" dataset to uncover temporal and spatial patterns, distribution of AQI levels, and pollutant-AQI relationships in an easy-to-understand format.

Objectives

Data Exploration — Load and describe the dataset, including data types, missing values, and pollutant columns. Data Cleaning & Preparation — Handle missing and duplicate data, convert date columns, and prepare categorical AQI bands. EDA & Visualizations — Explore univariate, bivariate, and multivariate relationships Insight Derivation — Summarize key findings, such as seasonal trends in AQI.

What is Air Quality Index (AQI)?

The Air Quality Index (AQI) is a number that measures how clean or polluted the air is in a given location. It also indicates the health risks associated with breathing polluted air.

Indian AQI Ranges and its probable impacts

The Air Quality Index (AQI) in India ranges from 0 to 500, with different values indicating different levels of health concern. AQI ranges: 0–50: Good air quality, with little to no risk of air pollution

51–100: Moderate air quality, with a small risk of health concerns for people who are very sensitive to air pollution
101–200: Unhealthy for sensitive groups, with health effects for members of sensitive groups
201–300: Harmful
301–400: Very harmful
401–500: Hazardous

Dataset Description

The dataset is sourced from Kaggle: “Air Quality Index” by sigmajegank. Based on typical structure, it likely comprises:

Date-related attributes : Date, Year, and Month, indicating when measurements were taken.

Location details : City, potentially part of a Location or Station column identifying measurement sites.

Pollutant concentration variables: Key pollutants such as PM2.5, PM10, NO, NO2, NOx, NH3, CO, SO2, O3, Benzene, Toluene, Xylene.

Air Quality indicators:

AQI : numerical Air Quality Index score for daily measurement.

AQI_Bucket or AQI_Band : categorical labels classifying AQI levels (Good, Satisfactory, Moderate, Poor, Very Poor, Severe) svc.ac.in Kaggle .

The dataset likely spans multiple cities (e.g., Bengaluru, Chennai, Delhi, Mumbai, Kolkata, etc.) and covers several years—potentially from 2020 to 2024—providing substantial temporal coverage for trend analysis.

Jupyter Notebook : Climate Watch_ Air Quality and Pollution Trends in Indian Cities.ipynb

Dataset : air-quality-india.csv
