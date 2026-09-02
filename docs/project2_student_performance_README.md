# Student Performance Analysis

## Developer Arena Internship — Data Analysis Project

### Project Overview

This project analyzes the academic performance of 2,000 simulated students using Python-based data analysis and visualization techniques.

The analysis focuses on academic scores, pass/fail performance, attendance, study hours, test preparation, gender, parental education, descriptive statistics, and correlation analysis.

> **Note:** The dataset is simulated and is used for portfolio and analytical demonstration purposes.

## Objectives

- Analyze student performance across Math, Reading, and Writing.
- Calculate pass and fail rates.
- Examine the relationship between attendance and academic performance.
- Analyze the relationship between study hours and scores.
- Compare students based on test preparation.
- Compare performance across gender and parental education groups.
- Calculate mean, median, and correlation statistics.
- Create clear visualizations and derive actionable educational insights.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The dataset contains 2,000 student records with information including:

- Student ID
- Gender
- Parental Education
- Lunch
- Test Preparation
- Attendance
- Study Hours
- Math Score
- Reading Score
- Writing Score
- Overall Score
- Result

## Data Quality Checks

The final dataset was validated successfully:

- 2,000 records
- 12 columns
- 0 missing values
- 0 duplicate rows
- 2,000 unique Student IDs
- All academic scores within the 0–100 range
- Both Pass and Fail outcomes present

## Key Findings

### Subject Performance

| Subject | Mean Score | Median Score |
|---|---:|---:|
| Math | 48.46 | 48.57 |
| Reading | 50.48 | 50.41 |
| Writing | 50.59 | 50.73 |
| Overall | 49.84 | 49.75 |

Writing had the highest average score, while Math had the lowest.

### Pass/Fail Performance

- Pass rate: **48.70%**
- Fail rate: **51.30%**

The results indicate that a substantial proportion of students could benefit from additional academic support.

### Test Preparation

| Test Preparation | Average Score | Pass Rate | Students |
|---|---:|---:|---:|
| Completed | 52.99 | 64.50% | 724 |
| None | 48.06 | 39.73% | 1,276 |

Students who completed test preparation showed higher average scores and pass rates. This is an observed association in the simulated dataset and should not be interpreted as proof of causation.

### Correlation Analysis

- Attendance vs Overall Score: **0.37**
- Study Hours vs Overall Score: **0.40**
- Math vs Overall Score: **0.68**
- Reading vs Overall Score: **0.64**
- Writing vs Overall Score: **0.69**

Attendance and study hours showed moderate positive relationships with overall performance.

## Visualizations

The project includes visualizations for:

1. Average score by subject
2. Pass/fail distribution
3. Average score by attendance group
4. Average score by study hours
5. Average score by test preparation
6. Average score by parental education
7. Student performance correlation matrix

## Recommendations

- Provide additional Math practice and targeted academic support.
- Identify students with lower attendance for early intervention.
- Encourage consistent and structured study schedules.
- Promote structured test preparation and revision programs.
- Provide early academic intervention for students at risk of failing.
- Focus academic support on individual learning needs.
- Monitor student performance, attendance, and study habits regularly.

## Project Structure

```text
data-analysis-portfolio/
│
├── data/
│   ├── supermarket_sales.csv
│   └── student_performance.csv
│
├── notebooks/
│   ├── 01_supermarket_sales_analysis.ipynb
│   └── 02_student_performance_analysis.ipynb
│
├── visualizations/
│   ├── Project 1 visualizations
│   └── Project 2 visualizations
│
├── reports/
│   └── student_performance_analysis_report.pdf
│
└── README.md
```

## How to Run

1. Open `02_student_performance_analysis.ipynb` in Jupyter Notebook or JupyterLab.
2. Ensure `student_performance.csv` is available in the `data` folder.
3. Run the notebook cells from top to bottom.
4. The analysis and visualizations will be generated from the dataset.

## Conclusion

This project demonstrates practical skills in data cleaning, validation, statistical analysis, exploratory data analysis, visualization, interpretation, and recommendation development using Python.

The analysis provides a complete example of turning structured student data into meaningful insights for an internship data-analysis portfolio.
