# Project 6 — House Price Analysis

## Project Overview

This project analyzes a dataset of 300 residential properties to identify the key factors associated with house prices. The analysis focuses on property size, bedrooms, bathrooms, age, location, property type, price segments, and price per area.

The project demonstrates practical data analysis using Python and pandas, supported by statistical analysis, data validation, and visualizations.

## Objectives

- Analyze the distribution of house prices.
- Identify relationships between property characteristics and price.
- Compare prices across locations and property types.
- Segment properties into Budget, Mid-Range, and Premium categories.
- Analyze price differences by number of bedrooms and property age.
- Calculate price per area to identify potential value properties.
- Generate actionable business insights and recommendations.

## Dataset

The dataset contains 300 property records and 8 original columns:

`Property_ID`, `Area`, `Bedrooms`, `Bathrooms`, `Age`, `Location`, `Property_Type`, `Price`

Derived columns:

- `Price_Segment`
- `Price_per_Area`
- `Age_Group`

## Key Results

- Average property price: approximately **₹2.49 crore**
- Median property price: approximately **₹2.24 crore**
- Minimum property price: approximately **₹36.95 lakh**
- Maximum property price: approximately **₹5.87 crore**
- Area–Price correlation: **0.796**
- City Center average price: approximately **₹3.31 crore**
- Suburb average price: approximately **₹2.51 crore**
- Rural average price: approximately **₹1.65 crore**
- Apartment average price: approximately **₹2.71 crore**
- Premium properties average price: approximately **₹4.07 crore**
- Average price per area: approximately **₹9,542.84**

## Visualizations

1. House Price Distribution
2. Area vs House Price
3. Average House Price by Location
4. Average House Price by Property Type
5. Average Price by Price Segment
6. Average House Price by Number of Bedrooms
7. Average House Price by Property Age Group

## Business Insights

### Property Size

Property area has the strongest numerical relationship with price, with a correlation of **0.796**.

### Location

City Center properties have substantially higher average prices than Suburban and Rural properties.

### Property Type

Apartments have the highest average price among the three property types analyzed.

### Price Segmentation

Premium properties have an average price of approximately ₹4.07 crore and an average area of approximately 3,952, while Budget properties average approximately ₹1.07 crore and 1,279 area units.

### Value Analysis

The lowest price-per-area properties are concentrated in Rural locations, suggesting potentially better space-for-price value.

### Property Age

New properties have a higher average price than older properties, although age has a much weaker relationship with price than area.

## Business Recommendations

1. Real estate sellers should consider property size and location when setting asking prices.
2. Buyers should compare price per area in addition to total property price.
3. Budget-conscious buyers can explore Rural and Suburban properties for potentially better space-to-price value.
4. Real estate companies can use price segmentation for targeted marketing.
5. Property valuation models should give greater importance to area and location.
6. Real estate dashboards should track price, area, location, property type, age, and price per area.

## Data Quality

- Records: **300**
- Missing values: **0**
- Duplicate rows: **0**
- Unique Property IDs: **300**
- Numerical variables were checked for valid values.
- Derived features were created from validated source data.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Project Structure

```text
06_house_price_analysis.ipynb
data/
└── house_prices (1).csv
visualizations/
├── house_price_distribution.png
├── area_vs_price.png
├── average_price_by_location.png
├── average_price_by_property_type.png
├── average_price_by_segment.png
├── average_price_by_bedrooms.png
└── average_price_by_age_group.png
```

## Conclusion

The analysis indicates that **property area and location are the most important factors associated with house prices in this dataset**. Price segmentation and price-per-area analysis provide additional perspectives for buyers, sellers, and real estate businesses.

> Note: This dataset is used for analytical and portfolio purposes. The relationships identified represent associations within the dataset and should not be interpreted as causal relationships.
