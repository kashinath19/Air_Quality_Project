# Air_Quality_Project

## Overview
This project analyzes air quality trends in urban cities to raise public health awareness and inform policy decisions. Using a synthetic dataset of 10,500 records, I performed data cleaning, exploratory data analysis (EDA), visualization, and predictive modeling to uncover pollution patterns and forecast future Air Quality Index (AQI) levels. The project demonstrates proficiency in  Excel delivering actionable insights through an interactive dashboard.

## Dataset
The dataset, air_quality_dataset.csv, contains 10,500 rows and 10 columns, including:

Date, City, AQI, PM2.5, PM10, CO, NO2, SO2, O3, Temperature.
It simulates air quality data for cities like Delhi, Mumbai, New York, London, and Tokyo from 2015 to May 2025.
Data Quality Issues: Includes 500 duplicates, 10% null values in PM2.5, NO2, and Temperature, mixed date formats (e.g., "YYYY-MM-DD" vs. "DD/MM/YYYY"), typos in City (e.g., "delhi" vs. "Delhi"), and invalid values (e.g., negative AQI).

## Objectives
Clean and preprocess messy air quality data for analysis.
Analyze pollution trends across cities, identifying high-risk areas and seasonal patterns.
Visualize findings through an interactive  dashboard.
Predict future AQI levels  to support public health initiatives.

## Tools and Technologies

Excel : Data cleaning, EDA and transformation (e.g., handling nulls, removing duplicates), Summary statistics and pivot tables, Interactive dashboard creation.


## Key Features
Data Cleaning:
Removed 500 duplicates .
Imputed 10% null values in PM2.5 and NO2 .
Standardized Date formats and corrected typos in City.
Exploratory Data Analysis (EDA):
Identified Delhi as the most polluted city with an average AQI of 180.
Found strong correlations between PM2.5 and low temperatures (correlation coefficient: 0.75).

## Visualization:
Built a  dashboard with:
Bar chart: Average AQI by city.
Heatmap: PM2.5 levels across months.
Slicers: Filter by year and city.

## Project Structure
generate_air_quality_dataset.py: Python script to create the synthetic dataset.
air_quality_dataset.csv: Synthetic dataset with 10,500 rows.
air_quality_analysis.ipynb: Jupyter Notebook with data cleaning, EDA, and predictive modeling.
air_quality_dashboard.pbix: Power BI file containing the interactive dashboard.
screenshots/: Folder with dashboard and chart screenshots.

## How to Use
Collect Dataset:
Collect the air_quality_dataset.csv from Kaggle.
Explore Analysis:
Open air_quality_analysis.csv in Excel to view data cleaning, EDA, and modeling steps.

## Problems Identified, Tools Used, and Achieved
Problems Identified: Handled 500 duplicates, 10% null values, mixed date formats, and invalid AQI values (e.g., negative AQI) using Excel.
Tools Used:  excel is used for data cleaning ,preprocessing, summaries, and  for visualization.
Achieved: Delivered a  dashboard. 


