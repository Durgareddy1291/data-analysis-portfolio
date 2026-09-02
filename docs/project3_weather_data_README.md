# Project 3 — Weather Data Analysis

## Project Overview

This project analyzes a simulated daily weather dataset covering the period from January 1, 2020 to June 22, 2025. The analysis focuses on temperature trends, rainfall patterns, seasonal variation, weather-condition frequency, extreme weather events, and relationships between key weather variables.

The project demonstrates practical data cleaning, exploratory data analysis, statistical analysis, visualization, validation, and business-oriented interpretation using Python.

## Objectives

- Analyze daily and monthly temperature trends.
- Identify rainfall patterns and seasonal variation.
- Compare weather characteristics across seasons.
- Analyze the distribution of weather conditions.
- Identify extreme heat, cold, heavy-rain, and high-wind events.
- Calculate descriptive statistics including mean, median, minimum, and maximum.
- Examine correlations between temperature, humidity, wind speed, and rainfall.
- Provide practical operational recommendations based on the analysis.

## Dataset

**File:** `weather_data.csv`

**Records:** 2,000 daily observations

**Date range:** January 1, 2020 – June 22, 2025

### Variables

| Column | Description |
|---|---|
| Date | Daily observation date |
| Temperature_C | Temperature in degrees Celsius |
| Humidity_Percent | Relative humidity percentage |
| Wind_Speed_kmh | Wind speed in km/h |
| Rainfall_mm | Daily rainfall in millimeters |
| Weather_Condition | Classified weather condition |
| Year | Year extracted from Date |
| Month | Numeric month extracted from Date |
| Month_Name | Month name |
| Season | Season classification |

> **Note:** The dataset is simulated for portfolio and analytical demonstration purposes. It should not be interpreted as real historical weather data.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Analysis Performed

### Temperature Analysis

- Calculated daily temperature trends.
- Compared average and median temperatures.
- Analyzed monthly temperature patterns.
- Identified the highest and lowest monthly average temperatures.

### Rainfall Analysis

- Calculated average and median rainfall.
- Compared total rainfall across months.
- Analyzed seasonal rainfall patterns.
- Identified heavy rainfall events using a predefined threshold.

### Seasonal Analysis

Weather observations were grouped into:

- Winter
- Summer
- Monsoon
- Post-Monsoon

Temperature, rainfall, humidity, and wind speed were compared across these seasons.

### Extreme Weather Analysis

The following thresholds were used:

- Extreme Heat: Temperature >= 40°C
- Extreme Cold: Temperature <= 15°C
- Heavy Rain: Rainfall >= 20 mm
- High Wind: Wind Speed >= 30 km/h

A total of **48 extreme-weather records** were identified.

## Key Findings

### Temperature

- Overall average temperature: **27.22°C**
- Median temperature: **27.22°C**
- Minimum temperature: **10.79°C**
- Maximum temperature: **45.00°C**
- Highest monthly average temperature: **June (27.68°C)**
- Lowest monthly average temperature: **September (26.79°C)**

### Rainfall

- Average rainfall: **3.76 mm**
- Median rainfall: **2.63 mm**
- Maximum recorded rainfall: **26.33 mm**
- Highest monthly total rainfall: **April (744.44 mm)**
- Lowest monthly total rainfall: **November (510.07 mm)**

### Seasonal Patterns

- Highest seasonal rainfall: **Monsoon (2,277.00 mm)**
- Lowest seasonal rainfall: **Post-Monsoon (1,181.65 mm)**
- Highest average seasonal temperature: **Post-Monsoon (27.46°C)**
- Highest average humidity: **Monsoon (65.43%)**

### Weather Conditions

| Condition | Days | Share |
|---|---:|---:|
| Clear | 1,348 | 67.4% |
| Rainy | 494 | 24.7% |
| Hot | 83 | 4.15% |
| Cool | 43 | 2.15% |
| Heavy Rain | 32 | 1.6% |

### Extreme Events

| Event | Count |
|---|---:|
| Extreme Heat | 8 |
| Extreme Cold | 17 |
| Heavy Rain | 8 |
| High Wind | 15 |

Extreme cold was the most frequent individual extreme-weather category.

### Correlation

The major weather variables showed very weak linear relationships in this simulated dataset.

- Temperature vs Rainfall: **0.001**
- Temperature vs Humidity: **-0.018**
- Wind Speed vs Rainfall: **0.034**
- Humidity vs Wind Speed: **0.035**

These results indicate that strong linear relationships were not present in this simulated dataset.

## Visualizations

The project contains seven visualizations:

1. `temperature_trend.png` — Daily temperature trend
2. `monthly_temperature.png` — Average monthly temperature
3. `monthly_rainfall.png` — Total monthly rainfall
4. `seasonal_rainfall.png` — Seasonal rainfall comparison
5. `extreme_weather_events.png` — Extreme weather event frequency
6. `weather_correlation_matrix.png` — Correlation between weather variables
7. `weather_condition_distribution.png` — Distribution of weather conditions

## Data Validation

Final quality checks confirmed:

- Dataset shape: **2,000 rows × 10 columns**
- Missing values: **0**
- Duplicate rows: **0**
- Unique dates: **2,000**
- Date range: **2020-01-01 to 2025-06-22**
- Temperature range: **10.79°C to 45.00°C**
- Rainfall range: **0.00 to 26.33 mm**

## Business & Operational Recommendations

1. **Plan for seasonal rainfall**
   - Increase preparedness during the Monsoon season.
   - Use historical rainfall patterns to support logistics and outdoor-operation planning.

2. **Prepare for extreme weather**
   - Establish contingency procedures for extreme heat, cold, heavy rainfall, and high winds.
   - Adjust operational schedules when severe conditions are expected.

3. **Optimize resource planning**
   - Use weather trends to support transportation, staffing, outdoor activities, and infrastructure maintenance decisions.

4. **Improve rainfall monitoring**
   - Pay additional attention to months with higher rainfall.
   - Maintain drainage and water-management infrastructure where appropriate.

5. **Expand future analysis**
   - Combine weather observations with air pressure, cloud cover, solar radiation, and location-specific data.
   - Use larger real-world datasets for forecasting and predictive modeling.

## Project Structure

```text
data-analysis-portfolio/
├── data/
│   └── weather_data.csv
├── notebooks/
│   └── 03_weather_data_analysis.ipynb
├── visualizations/
│   ├── temperature_trend.png
│   ├── monthly_temperature.png
│   ├── monthly_rainfall.png
│   ├── seasonal_rainfall.png
│   ├── extreme_weather_events.png
│   ├── weather_correlation_matrix.png
│   └── weather_condition_distribution.png
├── reports/
│   └── weather_data_analysis_report.pdf
└── docs/
    └── project3_weather_data_README.md
```

## Conclusion

The analysis demonstrates an end-to-end weather data analysis workflow using Python. The dataset shows relatively stable temperatures, meaningful seasonal rainfall differences, predominantly clear conditions, and a limited number of extreme-weather events.

Because the dataset is simulated, the results are intended for portfolio demonstration rather than real-world forecasting. The same analytical workflow can be applied to reliable meteorological or government open-data sources for production analysis.
