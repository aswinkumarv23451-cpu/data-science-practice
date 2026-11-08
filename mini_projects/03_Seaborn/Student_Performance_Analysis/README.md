<h1 align="center">Student Academic Performance & Lifestyle Analysis</h1>

<p align="center">
  <strong>Exploratory Data Analysis | Statistical Insights | Data Visualization</strong>
</p>

<p align="center">
  <em>A Python-based study of academic performance, student habits, and lifestyle patterns using real-world educational data.</em>
</p>

<p align="center">
  <strong>Author:</strong> ASWIN KUMAR V
  &nbsp; | &nbsp;
  <strong>Domain:</strong> Data Science
  &nbsp; | &nbsp;
  <strong>Status:</strong> Completed
</p>

<p align="center">
  Python • Pandas • NumPy • Seaborn • Matplotlib • Jupyter Notebook
</p>

---

## 📌 1. Project Overview

This project explores student academic performance and its relationship with lifestyle, study habits, family background, social activities, and other factors.

Using Python and data visualization libraries, the analysis investigates patterns in students' final grades and examines how different personal and academic characteristics are associated with performance.

The project uses the Student Performance dataset from the UCI Machine Learning Repository.

## 🎯 2. Project Objectives

- Understand the structure and characteristics of student performance data.
- Analyse final grades and academic progression.
- Investigate the relationship between study time and academic performance.
- Compare academic performance across genders.
- Explore the association between alcohol consumption and final grades.
- Examine parental education and its relationship with student performance.
- Analyse absences, failures, internet access, free time, going out, and health.
- Identify important patterns through statistical analysis and visualizations.

## 🛠️ 3. Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming |
| NumPy | Numerical operations |
| Pandas | Data cleaning and analysis |
| Seaborn | Statistical visualization |
| Matplotlib | Data visualization |
| Jupyter Notebook | Interactive analysis |
| GitHub | Version control and project documentation |

## 📊 4. Dataset Information

**Dataset:** Student Performance — Mathematics (`student-mat.csv`)

**Source:** UCI Machine Learning Repository

| Dataset Property | Value |
|---|---:|
| Total Records | 395 |
| Total Features | 33 |
| Missing Values | 0 |
| Duplicate Records | 0 |
| Target Variable | G3 |
| Grade Range | 0–20 |

**Important variables:**

- `G1` — First-period grade
- `G2` — Second-period grade
- `G3` — Final grade
- `studytime` — Weekly study time
- `failures` — Previous class failures
- `absences` — Number of school absences
- `Dalc` — Workday alcohol consumption
- `Walc` — Weekend alcohol consumption
- `freetime` — Free time after school
- `goout` — Going out with friends
- `health` — Current health status
- `Medu` — Mother's education
- `Fedu` — Father's education


## 5. Analysis Performed

### 5.1 Data Cleaning and Exploration

- Loaded the dataset using Pandas.
- Examined dataset dimensions and data types.
- Checked missing values and duplicate records.
- Explored descriptive statistics.
- Identified categorical and numerical variables.

### 5.2 Academic Performance Analysis

- Analysed grade distributions.
- Compared G1, G2, and G3.
- Investigated previous failures and final grades.
- Examined study time against final grades.
- Compared grade distributions across genders.

### 5.3 Lifestyle Analysis

- Examined weekday and weekend alcohol consumption.
- Analysed free time and social activities.
- Investigated health and academic performance.
- Explored internet access and final grades.
- Studied the relationship between study time and alcohol consumption.

### 5.4 Family Background Analysis

- Examined mother's education.
- Examined father's education.
- Compared parental education patterns.
- Investigated associations with final grades.

### 5.5 Statistical Analysis

- Descriptive statistics.
- Group-wise mean and median comparisons.
- Correlation analysis.
- Correlation heatmap.
- Study time and alcohol consumption comparison.
- Gender-based statistical comparisons.

## 📈 6. Data Visualizations

This project contains **29 visualizations** created using Seaborn and Matplotlib.

### Academic Performance

**1. Grade Distribution**

![Grade Distribution](outputs/grade_distribution.png)

**2. Grade Progression**

![Grade Progression](outputs/grade_progression.png)

**3. Grade Boxplot**

![Grade Boxplot](outputs/grade_boxplot.png)

**4. Performance by Gender**

![Grade by Gender](outputs/grade_by_gender.png)

**5. Study Time vs Final Grades**

![Study Time vs Grades](outputs/studytime_vs_grades.png)

**6. Study Time Boxplot**

![Study Time Boxplot](outputs/studytime_boxplot.png)

**7. Previous Failures vs Grades**

![Failures vs Grades](outputs/failures_vs_grades.png)

**8. Absences vs Grades**

![Absences vs Grades](outputs/absences_vs_grades.png)

### Gender-Based Analysis

**9. Gender Distribution**

![Gender Distribution](outputs/gender_distribution.png)

**10. Study Time by Gender**

![Study Time by Gender](outputs/studytime_by_gender.png)

**11. Study Time and Gender Grades**

![Study Time Gender Grades](outputs/studytime_gender_grades.png)

**12. Study Time Gender Percentage**

![Study Time Gender Percentage](outputs/studytime_gender_percentage.png)

**13. Study Time Gender FacetGrid**

![Study Time Gender FacetGrid](outputs/studytime_gender_facetgrid.png)

### Family Background Analysis

**14. Mother's Education vs Grades**

![Mother Education vs Grades](outputs/mother_education_vs_grades.png)

**15. Father's Education vs Grades**

![Father Education vs Grades](outputs/father_education_vs_grades.png)

**16. Parent Education Comparison**

![Parent Education Comparison](outputs/parent_education_comparison.png)

### Lifestyle Analysis

**17. Weekday Alcohol Consumption vs Grades**

![Weekday Alcohol vs Grades](outputs/weekday_alcohol_vs_grades.png)

**18. Weekend Alcohol Consumption vs Grades**

![Weekend Alcohol vs Grades](outputs/weekend_alcohol_vs_grades.png)

**19. Alcohol Comparison**

![Alcohol Comparison](outputs/alcohol_comparison.png)

**20. Study Time and Alcohol Scatterplot**

![Study Time Alcohol Scatter](outputs/studytime_alcohol_scatter.png)

**21. Combined Study Time and Alcohol Scatterplot**

![Study Time Alcohol Combined Scatter](outputs/studytime_alcohol_combined_scatter.png)

**22. Study Time and Alcohol Heatmap**

![Study Time Alcohol Heatmap](outputs/studytime_alcohol_heatmap.png)

**23. Study Time and Alcohol Jointplot**

![Study Time Alcohol Jointplot](outputs/studytime_jointplot.png)

**24. Free Time vs Grades**

![Free Time vs Grades](outputs/freetime_vs_grades.png)

**25. Going Out vs Grades**

![Going Out vs Grades](outputs/goout_vs_grades.png)

**26. Health vs Grades**

![Health vs Grades](outputs/health_vs_grades.png)

**27. Internet Access vs Grades**

![Internet Access vs Grades](outputs/internet_vs_grades.png)

### Advanced Statistical Visualization

**28. Lifestyle Pairplot**

![Lifestyle Pairplot](outputs/lifestyle_pairplot.png)

**29. Student Performance Correlation Heatmap**

![Student Performance Correlation Heatmap](outputs/student_performance_correlation_heatmap.png)

## 📉 7. Key Findings

### Academic Performance

- The average final grade (`G3`) is approximately 10.42 out of 20.
- The average grades decrease slightly from G1 to G3.
- Students with no previous failures show a higher average final grade than students with previous failures.
- Study time has a small positive correlation with final grades.

### Study Habits

- Students in the higher study-time categories show higher average final grades than some lower study-time groups.
- Study time and weekday alcohol consumption have a negative correlation of approximately -0.196.
- Study time and weekend alcohol consumption have a negative correlation of approximately -0.254.

### Lifestyle

- Going out has a negative correlation of approximately -0.133 with final grades.
- Alcohol consumption has a weak negative correlation with final grades.
- Absences have a negligible linear correlation with final grades.
- Free time and health show very weak linear correlations with final grades.

### Academic Correlations

| Variable | Correlation with G3 |
|---|---:|
| G2 | +0.905 |
| G1 | +0.801 |
| Study Time | +0.098 |
| Absences | +0.034 |
| Free Time | +0.011 |
| Weekend Alcohol | -0.052 |
| Weekday Alcohol | -0.055 |
| Health | -0.061 |
| Going Out | -0.133 |
| Previous Failures | -0.360 |

**Important observation:** Previous-period grades have strong positive correlations with final grades, while previous failures show a moderate negative correlation.

## 💡 8. Important Insights

1. Previous academic performance is strongly associated with final academic performance.
2. Previous class failures are associated with lower final grades.
3. Study time shows a positive but relatively weak relationship with final grades.
4. Lifestyle variables show different patterns, but their individual correlations with final grades are generally weak.
5. Group sizes vary considerably, so comparisons involving smaller groups should be interpreted carefully.

**Note:** Correlation does not imply causation. These findings describe patterns in the dataset and do not establish that any particular lifestyle factor causes changes in academic performance.

## 📁 9. Project Documentation

## Project Structure

```text
03_Seaborn/
└── Student_Performance_Analysis/
    ├── data/
    │   └── student-mat.csv
    ├── notebooks/
    │   └── student_performance_analysis.ipynb
    ├── outputs/
    │   ├── absences_vs_grades.png
    │   ├── alcohol_comparison.png
    │   ├── failures_vs_grades.png
    │   ├── father_education_vs_grades.png
    │   ├── freetime_vs_grades.png
    │   ├── gender_distribution.png
    │   ├── goout_vs_grades.png
    │   ├── grade_boxplot.png
    │   ├── grade_by_gender.png
    │   ├── grade_distribution.png
    │   ├── grade_progression.png
    │   ├── health_vs_grades.png
    │   ├── internet_vs_grades.png
    │   ├── lifestyle_pairplot.png
    │   ├── mother_education_vs_grades.png
    │   ├── parent_education_comparison.png
    │   ├── student_performance_correlation_heatmap.png
    │   ├── studytime_alcohol_combined_scatter.png
    │   ├── studytime_alcohol_heatmap.png
    │   ├── studytime_alcohol_scatter.png
    │   ├── studytime_boxplot.png
    │   ├── studytime_by_gender.png
    │   ├── studytime_gender_facetgrid.png
    │   ├── studytime_gender_grades.png
    │   ├── studytime_gender_percentage.png
    │   ├── studytime_jointplot.png
    │   ├── studytime_vs_grades.png
    │   ├── weekday_alcohol_vs_grades.png
    │   └── weekend_alcohol_vs_grades.png
    ├── analysis.md
    └── README.md
```

- #### 📓 [Jupyter Notebook](notebooks/student_performance_analysis.ipynb)
- #### 📄 [Detailed Analysis Report](/mini_projects/03_Seaborn/Student_Performance_Analysis/anaysis.md)

## 🚀 10. Skills Demonstrated

- Python programming
- Data manipulation using Pandas
- Numerical analysis using NumPy
- Exploratory Data Analysis (EDA)
- Statistical analysis
- Data visualization using Seaborn
- Matplotlib customization
- Correlation analysis
- Group-wise analysis
- Data interpretation
- Technical documentation
- GitHub project management

## 🔮 11. Future Improvements

- Apply Machine Learning models to predict student final grades.
- Perform feature engineering and feature selection.
- Compare regression algorithms.
- Evaluate models using appropriate performance metrics.
- Develop an interactive student performance dashboard.
- Explore additional student datasets for broader analysis.

## 👨‍💻 12. About the Author

**ASWIN KUMAR V**

B.Tech — Artificial Intelligence and Data Science

Interested in Artificial Intelligence, Machine Learning, Data Science, Python Development, and Software Engineering.

<p align="center">
  <a href="https://github.com/aswinkumarv23451-cpu">GitHub Profile</a> |
  <a href="https://www.linkedin.com/in/aswin-kumar-v-740724426/">LinkedIn</a>
</p>

---

<p align="center">
  <strong>Learning by Building | Exploring Data | Turning Insights into Knowledge</strong>
</p>

<p align="center">
  ⭐ If you find this project useful, consider giving it a star!
</p>