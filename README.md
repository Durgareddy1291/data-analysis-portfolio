# Multi-Domain Data Analysis Portfolio

A professional data analysis portfolio containing six end-to-end projects across retail, education, weather, healthcare, finance, and real estate.

The portfolio demonstrates practical skills in **Python, Pandas, NumPy, Matplotlib, statistical analysis, data cleaning, validation, visualization, and business insight generation**.

---

## Portfolio Overview

| # | Project | Domain | Main Analysis |
|---|---|---|---|
| 1 | Supermarket Sales Analysis | Retail | Sales trends, products, customers, branches |
| 2 | Student Performance Analysis | Education | Scores, pass/fail, attendance, study behavior |
| 3 | Weather Data Analysis | Weather | Temperature, rainfall, seasons, extreme events |
| 4 | Healthcare Data Analysis | Healthcare | Costs, departments, satisfaction, readmission |
| 5 | Finance Data Analysis | Finance | Price trends, returns, volatility, volume |
| 6 | House Price Analysis | Real Estate | Price drivers, location, property size, value |

---

# Projects

## 1. Supermarket Sales Analysis

### Objective
Analyze supermarket transaction data to understand sales performance, customer behavior, product performance, branch performance, and sales timing.

### Key Analysis
- Product-line sales
- Branch performance
- Customer type analysis
- Gender-based sales analysis
- Daily sales trends
- Day-of-week performance
- Hourly sales patterns
- Correlation analysis

### Key Findings
- Health & Beauty generated the highest product-line sales.
- Branch B had the highest total sales.
- Thursday was the strongest sales day.
- 18:00 was the peak sales hour.
- Numeric sales variables showed generally weak linear correlations.

### Visualizations
- Product sales
- Customer sales
- Branch sales
- Daily sales trend
- Day-of-week sales
- Hourly sales
- Correlation matrix

---

## 2. Student Performance Analysis

### Objective
Analyze student academic performance and identify relationships between attendance, study hours, test preparation, and examination outcomes.

### Key Analysis
- Subject scores
- Overall performance
- Pass/fail rates
- Attendance impact
- Study-hours impact
- Test-preparation impact
- Gender comparison
- Parental education analysis
- Correlation analysis

### Key Findings
- Overall pass rate was **48.70%**.
- Students who completed test preparation had a higher pass rate.
- Attendance had a positive relationship with overall score.
- Study hours had a positive relationship with overall score.
- Test preparation was associated with improved average performance.

### Visualizations
- Average subject scores
- Pass/fail distribution
- Attendance vs performance
- Study hours vs performance
- Test preparation scores
- Parental education scores
- Correlation matrix

---

## 3. Weather Data Analysis

### Objective
Analyze weather observations to identify temperature trends, rainfall patterns, seasonal behavior, and extreme weather events.

### Key Analysis
- Temperature trends
- Monthly rainfall
- Seasonal rainfall
- Weather-condition distribution
- Extreme weather events
- Wind behavior
- Correlation analysis

### Key Findings
- Clear conditions were the most frequent weather condition.
- Monsoon recorded the highest seasonal rainfall.
- Temperature remained centered around approximately **27°C**.
- The analysis identified heat, cold, heavy-rain, and high-wind events.
- Weather variables showed generally weak linear correlations in the simulated dataset.

### Visualizations
- Monthly temperature
- Monthly rainfall
- Seasonal rainfall
- Extreme weather events
- Weather correlation matrix
- Temperature trend
- Weather-condition distribution

---

## 4. Healthcare Data Analysis

### Objective
Analyze healthcare records to understand patient characteristics, treatment costs, length of stay, satisfaction, departments, diagnoses, and readmissions.

### Key Analysis
- Department performance
- Treatment costs
- Length of stay
- Cost per day
- Patient satisfaction
- Readmission rates
- Diagnosis-level analysis
- Correlation analysis

### Key Findings
- The overall readmission rate was **14.8%**.
- Cardiology had the highest department-level readmission rate.
- Treatment cost per day showed a strong negative relationship with length of stay.
- Patient satisfaction varied across departments.
- Readmission rates differed across diagnoses.

### Visualizations
- Patients by department
- Department treatment cost
- Readmission by department
- Diagnosis cost
- Satisfaction by department
- Stay vs cost
- Satisfaction distribution

---

## 5. Finance Data Analysis

### Objective
Analyze simulated financial market data to understand price movement, returns, trading volume, volatility, and moving-average signals.

### Key Analysis
- Price trends
- Daily returns
- Trading volume
- Rolling volatility
- Monthly returns
- Moving averages
- Bullish/bearish signals
- Correlation analysis
- OHLC data validation

### Key Findings
- Starting closing price was approximately **₹101.04** and ending closing price approximately **₹686.77** in the simulated series.
- Overall simulated price return was approximately **579.68%**.
- Average daily return was approximately **0.16%**.
- Daily return volatility was approximately **1.98%**.
- The 20-day moving-average signal was bullish for approximately **61.53%** of analyzed observations.
- OHLC consistency checks were completed successfully.

### Visualizations
- Price trend
- Daily returns
- Trading volume
- Volatility
- Monthly returns
- Moving-average signals
- Correlation matrix

> **Note:** The finance dataset is simulated and is intended for portfolio and analytical demonstration purposes, not investment advice.

---

## 6. House Price Analysis

### Objective
Analyze residential property data to identify the major factors associated with property prices and evaluate property value across locations, property types, sizes, and price segments.

### Dataset
- **300 properties**
- **0 missing values**
- **0 duplicate rows**
- **300 unique Property IDs**

### Key Analysis
- Price distribution
- Area vs price
- Location-based pricing
- Property-type pricing
- Price segmentation
- Bedroom analysis
- Property-age analysis
- Price per area

### Key Findings
- Average property price: approximately **₹2.49 crore**.
- Median property price: approximately **₹2.24 crore**.
- Maximum property price: approximately **₹5.87 crore**.
- Area had a strong positive correlation with price of **0.796**.
- City Center properties had the highest average price at approximately **₹3.31 crore**.
- Rural properties had the lowest average price at approximately **₹1.65 crore**.
- Apartments had the highest average price among property types at approximately **₹2.71 crore**.
- Premium properties averaged approximately **₹4.07 crore**.
- Average price per area was approximately **₹9,542.84**.

### Visualizations
- House price distribution
- Area vs house price
- Average price by location
- Average price by property type
- Average price by price segment
- Average price by bedrooms
- Average price by age group

---

# Skills Demonstrated

## Data Analysis
- Data loading
- Data cleaning
- Data transformation
- Feature engineering
- GroupBy analysis
- Aggregation
- Descriptive statistics
- Correlation analysis
- Trend analysis
- Segmentation

## Python
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Data Quality
- Missing-value checks
- Duplicate checks
- Unique-ID validation
- Data-type validation
- Numerical-value validation
- Domain-specific validation
- OHLC consistency checks for finance data

## Data Visualization
The portfolio includes **40+ visualizations** covering:

- Bar charts
- Histograms
- Scatter plots
- Line charts
- Correlation matrices
- Distribution charts
- Trend charts
- Comparison charts

## Business Analysis
Each project includes:
- Executive summary
- Key findings
- Business insights
- Actionable recommendations
- Data quality validation
- Professional PDF reporting

---

# Repository Structure

```text
data-analysis-portfolio/
│
├── README.md
├── requirements.txt
│
├── data/
│   ├── supermarket_sales.csv
│   ├── student_performance.csv
│   ├── weather_data.csv
│   ├── healthcare_data.csv
│   ├── finance_data.csv
│   └── house_prices (1).csv
│
├── notebooks/
│   ├── 01_supermarket_sales_analysis.ipynb
│   ├── 02_student_performance_analysis.ipynb
│   ├── 03_weather_data_analysis.ipynb
│   ├── 04_healthcare_data_analysis.ipynb
│   ├── 05_finance_data_analysis.ipynb
│   └── 06_house_price_analysis.ipynb
│
├── reports/
│   ├── supermarket_sales_analysis_report.pdf
│   ├── student_performance_analysis_report.pdf
│   ├── weather_data_analysis_report.pdf
│   ├── healthcare_data_analysis_report.pdf
│   ├── finance_data_analysis_report.pdf
│   └── house_price_analysis_report.pdf
│
├── visualizations/
│   └── project visualization PNG files
│
├── docs/
│   ├── project1_supermarket_sales_README.md
│   ├── project2_student_performance_README.md
│   ├── project3_weather_data_README.md
│   ├── project4_healthcare_data_README.md
│   ├── project5_finance_data_README.md
│   └── project6_house_price_README.md
│
├── presentation/
└── src/
```

---

# How to Run the Projects

## 1. Clone or download the repository

Place the project folder on your computer.

## 2. Install dependencies

```bash
pip install -r requirements.txt
```

## 3. Open Jupyter Notebook

```bash
jupyter notebook
```

## 4. Open a project notebook

Navigate to the `notebooks/` folder and open the required `.ipynb` file.

## 5. Run the notebook

Run the cells sequentially from top to bottom.

---

# Requirements

Recommended Python libraries:

```text
pandas
numpy
matplotlib
jupyter
```

---

# Portfolio Highlights

### 6
**Data Analysis Projects**

### 40+
**Visualizations**

### 6
**Professional Reports**

### 6
**Project Documentation Files**

### 5+
**Domains Covered**

Retail • Education • Weather • Healthcare • Finance • Real Estate

---

# Overall Conclusion

This portfolio demonstrates an end-to-end approach to data analysis: collecting or creating datasets, validating data quality, cleaning and transforming data, performing statistical analysis, creating meaningful visualizations, identifying patterns, and converting findings into actionable business recommendations.

The projects are designed to demonstrate practical analytical thinking across multiple domains rather than focusing only on technical code.

> **Dataset note:** Several projects use simulated datasets for portfolio demonstration. Findings from simulated data should not be interpreted as real-world facts.

---

## Author

**Durga Prasad Reddy**

Data Analysis | Python | Pandas | NumPy | Data Visualization | Statistical Analysis
