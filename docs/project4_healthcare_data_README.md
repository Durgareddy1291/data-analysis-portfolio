# Project 4 — Healthcare Patient & Hospital Performance Analysis

## Project Overview

This project analyzes 2,000 simulated healthcare patient records to identify patterns in hospital department performance, treatment costs, length of stay, patient satisfaction, and readmission rates.

The analysis demonstrates practical data-analysis techniques using Python, Pandas, NumPy, and Matplotlib.

## Objectives

- Analyze patient demographics and hospital departments
- Compare treatment costs across departments and diagnoses
- Analyze hospital length of stay
- Evaluate patient satisfaction
- Calculate readmission rates
- Identify relationships between key healthcare metrics
- Perform data validation and statistical analysis
- Generate actionable recommendations

## Dataset

The dataset contains **2,000 simulated patient records**.

### Main Variables

- Patient ID
- Age
- Gender
- Department
- Diagnosis
- Length of Stay
- Treatment Cost
- Satisfaction Score
- Readmission
- Age Group
- Cost per Day
- Satisfaction Level

> **Important:** The dataset is simulated for educational and portfolio demonstration purposes. It is not intended for clinical decision-making.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Data Quality Validation

The dataset passed the following validation checks:

- **2,000 records**
- **12 columns**
- **0 missing values**
- **0 duplicate rows**
- **2,000 unique patient IDs**
- Valid age range: 18–80
- Valid hospital stay range: 1–14 days
- Valid satisfaction range: 1–10
- Valid readmission categories
- Valid department and diagnosis categories

## Key Findings

### Treatment Cost

The average treatment cost was **₹51,319.68**, with a median of **₹50,800.46**.

General Medicine had the highest average treatment cost at approximately **₹52,473.54**.

### Length of Stay

The average hospital stay was **7.40 days**, with a median of **7 days**.

Hypertension patients had the highest diagnosis-level average stay at **7.67 days**.

### Patient Satisfaction

The overall average satisfaction score was **5.43/10**.

Low satisfaction represented **686 patients (34.3%)**, making patient experience an important improvement area.

### Readmission

The overall readmission rate was **14.8%**.

Cardiology had the highest department-level readmission rate at **16.83%**.

Hypertension had the highest diagnosis-level readmission rate at **16.45%**.

### Correlation

Treatment Cost and Cost per Day had a moderate positive correlation of **0.425**.

Length of Stay and Cost per Day had a stronger negative correlation of **-0.614**.

Most other relationships were weak.

## Visualizations

The project includes seven visualizations:

1. Patient Distribution by Department
2. Average Treatment Cost by Department
3. Readmission Rate by Department
4. Average Treatment Cost by Diagnosis
5. Patient Satisfaction by Department
6. Length of Stay vs Treatment Cost
7. Patient Satisfaction Distribution

## Business Recommendations

1. Improve patient communication and service quality to increase satisfaction.
2. Monitor departments with higher readmission rates.
3. Provide stronger post-discharge follow-up for higher-risk diagnosis groups.
4. Review high-cost departments and diagnoses for opportunities to improve resource efficiency.
5. Analyze longer hospital stays to improve discharge planning.
6. Develop a healthcare dashboard for continuous KPI monitoring.

## Project Structure

```text
data-analysis-portfolio/
├── data/
│   └── healthcare_data.csv
├── notebooks/
│   └── 04_healthcare_data_analysis.ipynb
├── reports/
│   └── healthcare_data_analysis_report.pdf
├── visualizations/
│   ├── healthcare_department_patients.png
│   ├── healthcare_department_cost.png
│   ├── healthcare_readmission_by_department.png
│   ├── healthcare_diagnosis_cost.png
│   ├── healthcare_satisfaction_by_department.png
│   ├── healthcare_stay_vs_cost.png
│   └── healthcare_satisfaction_distribution.png
└── docs/
    └── project4_healthcare_data_README.md
```

## Conclusion

This project demonstrates a complete healthcare data-analysis workflow including data generation, cleaning, validation, statistical analysis, correlation analysis, visualization, insight generation, and business recommendations.

The workflow can be adapted to real healthcare datasets from hospitals, public-health organizations, or government open-data platforms.
