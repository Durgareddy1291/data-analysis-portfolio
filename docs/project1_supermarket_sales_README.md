# Supermarket Sales Analysis

## Developer Arena Internship — Project 1

### Domain
Retail / Supermarket Sales

## Project Overview

This project analyzes supermarket transaction data to identify sales patterns, best-performing product categories, customer behavior, branch performance, and peak sales periods.

The project demonstrates practical skills in data cleaning, transformation, exploratory data analysis, statistical analysis, visualization, and business insight generation.

## Objectives

- Analyze daily and time-based sales patterns.
- Identify best-selling product categories.
- Compare branch performance.
- Analyze customer segments.
- Examine day-of-week and hourly sales.
- Calculate mean, median, and correlation statistics.
- Validate dataset quality.
- Generate actionable business recommendations.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset Overview

The dataset contains 2,000 supermarket transactions and includes fields such as:

- Invoice ID
- Branch
- City
- Customer Type
- Gender
- Product Line
- Unit Price
- Quantity
- Tax
- Total
- Date
- Time
- Payment
- Rating

## Data Quality

- Records: **2,000**
- Missing values: **0**
- Duplicate rows: **0**
- Date converted to datetime for time-based analysis.
- Additional time features were derived for year, month, day name, and hour.

## Key Findings

### Product Performance

**Health & Beauty** generated the highest total sales at **₹96,970.32**.

**Fashion Accessories** generated the lowest total sales at **₹77,551.72**.

### Branch Performance

**Branch B** recorded the highest total sales, while **Branch C** recorded the lowest.

### Day-of-Week Performance

**Thursday** was the highest-sales day, while **Sunday** was the lowest-sales day.

### Peak Hour

The highest sales occurred at approximately **18:00**.

### Customer Behavior

Member and Normal customers showed broadly similar sales performance, indicating that both segments are important for overall revenue.

## Statistical Analysis

The project includes:

- Mean
- Median
- Grouped statistics
- Correlation analysis
- Day-of-week trends
- Hourly sales trends

The mean total transaction value was approximately **₹259.64**, while the median was approximately **₹258.04**.

## Visualizations

The project includes:

1. Product sales comparison
2. Customer sales comparison
3. Branch sales comparison
4. Daily sales trend
5. Day-of-week sales
6. Hourly sales
7. Correlation matrix

## Business Recommendations

1. Maintain sufficient inventory for high-performing product categories.
2. Investigate lower-performing categories and branches.
3. Increase staffing and operational readiness during peak evening demand.
4. Use targeted promotions during weaker sales periods.
5. Monitor customer ratings and sales together to improve customer experience.
6. Review branch-level performance regularly to identify operational opportunities.

## Project Files

```text
data-analysis-portfolio/
│
├── data/
│   └── supermarket_sales.csv
│
├── notebooks/
│   └── 01_supermarket_sales_analysis.ipynb
│
├── visualizations/
│   ├── product_sales.png
│   ├── customer_sales.png
│   ├── branch_sales.png
│   ├── daily_sales_trend.png
│   ├── day_of_week_sales.png
│   ├── hourly_sales.png
│   └── correlation_matrix.png
│
└── reports/
    └── supermarket_sales_analysis_report.pdf
```

## How to Run

1. Install the required Python packages.
2. Open `notebooks/01_supermarket_sales_analysis.ipynb`.
3. Ensure `supermarket_sales.csv` is available in the `data` folder.
4. Run the notebook cells from top to bottom.
5. Review the generated analysis and visualizations.

## Conclusion

This project demonstrates an end-to-end retail data analysis workflow and shows how transaction data can be transformed into useful insights for inventory planning, staffing, promotions, and branch-level decision making.
