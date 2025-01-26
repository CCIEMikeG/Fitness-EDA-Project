# Intensity and Calories Analysis

---

## Overview

This branch focuses on analyzing Fitbit data to explore trends in activity intensity and calories burned over time. The project involves data cleaning, aggregation, visualization, and statistical modeling to provide actionable insights.

---

## Objectives

- Aggregate and clean the data to identify daily and hourly trends.
- Analyze fluctuations in activity intensity and calories burned.
- Apply statistical methods, including correlation and regression, to assess relationships.
- Visualize trends using clear and informative charts.
- Perform time series analysis to detect seasonality and trends.
- Forecast future patterns using advanced modeling techniques.

---

## Project Steps

1. Data loading and preparation:
	- Import Fitbit data from multiple CSV files.
	- Merge datasets and convert date columns for proper analysis.
	
2. Aggregation:
	- Group data by date to calculate daily totals for calories burned and average intensity.
	
3. Visualization:
	- Create visualizations to illustrate daily and hourly trends.
	
4. Statistical analysis:
	- Examine correlations and build predictive models.
	- Use time series decomposition to uncover patterns.
	
5. Forecasting:
	- Predict future trends using tools like Prophet.
	
---

## File Structure

- Jupyter Notebook: Contains the full analysis, including visualizations and results.

- Data Files:
	- hourlyCalories_merged.csv
	- hourlyIntensities_merged.csv
	- dailyActivity_merged.csv
	
- Output Files:
	- merged_hourly_data.csv
	- daily_trends.csv
	
---

## Data Source

This analysis uses the FitBit Fitness Tracker Data available on Kaggle:
https://www.kaggle.com/datasets/arashnic/fitbit/data?select=mturkfitbit_export_4.12.16-5.12.16

---

## Results

The analysis highlights significant trends in activity intensity and calorie burn, supported by visualizations and statistical insights.

---

## License

This project is licensed under the MIT License. See the LICENSE file in the repository for details.