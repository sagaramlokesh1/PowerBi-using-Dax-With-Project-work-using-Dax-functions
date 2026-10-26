# 📊 Power BI & DAX Projects

## 🩺 Healthcare Heart Disease Analysis Dashboard

**Tools:** Power BI, DAX, Power Query, Python (Pandas), Excel

### Project Overview
Developed an interactive healthcare dashboard to analyze heart disease patterns and identify important patient risk factors.

### 🔧 Data Preparation
- Cleaned and transformed healthcare data using **Power Query**.
- Handled missing values, duplicate records, inconsistent formats, and outliers.
- Created a structured data model for reporting and analysis.

### 📐 DAX Functions Used

Created calculated measures using DAX to analyze healthcare KPIs and provide dynamic insights.

```DAX
Total Patients = COUNTROWS(HeartDisease)

Heart Disease Cases =
CALCULATE(
    COUNTROWS(HeartDisease),
    HeartDisease[HeartDisease] = 1
)

Average Age =
AVERAGE(HeartDisease[Age])

Average Cholesterol =
AVERAGE(HeartDisease[Cholesterol])

Average Max Heart Rate =
AVERAGE(HeartDisease[MaxHeartRate])

Heart Disease % =
DIVIDE(
    [Heart Disease Cases],
    [Total Patients],
    0
)
```

### 📊 Dashboard Features
- Total Patients KPI
- Heart Disease Cases
- Heart Disease Percentage
- Average Age
- Average Cholesterol
- Average Maximum Heart Rate
- Age-wise Heart Disease Analysis
- Gender-wise Analysis
- Cholesterol and Blood Pressure Analysis
- Interactive filters and slicers

### 📈 Power BI Skills Demonstrated
- Data Cleaning & Transformation
- Power Query
- Data Modeling
- DAX Measures
- Calculated Measures
- KPI Development
- Interactive Visualizations
- Slicers & Filters
- Dashboard Design
- Business Insights

### 💡 Key Learning
Gained practical experience in using **DAX functions, Power Query, data modeling, and Power BI visualizations** to transform healthcare data into interactive dashboards and meaningful insights.
