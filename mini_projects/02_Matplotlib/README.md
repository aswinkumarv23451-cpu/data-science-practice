# 🌍 World Happiness & Quality of Life Analysis (2024)

## 📌 Project Overview

An exploratory data analysis project using the World Happiness Report 2024 dataset to understand global happiness patterns and investigate the factors associated with happiness.

The project applies Python, NumPy, and Matplotlib to perform statistical analysis, identify patterns, detect outliers, and create meaningful visualizations.

## 🎯 Project Objectives

- Analyze happiness scores across countries.
- Identify the happiest and least happy countries.
- Compare happiness levels across geographical regions.
- Study relationships between happiness and other factors.
- Perform statistical analysis and outlier detection.
- Present findings through professional visualizations.

## 📂 Project Structure

    World_Happiness_Analysis/
    │
    ├── data/
    │   └── world_happiness_2024.csv
    │
    ├── notebooks/
    │   └── world_happiness_analysis.ipynb
    │
    ├── outputs/
    │   ├── top_10_happiest.png
    │   ├── bottom_10_happiest.png
    │   ├── happiness_score_distribution.png
    │   ├── gdp_vs_happiness.png
    │   ├── social_support_vs_happiness.png
    │   ├── regional_happiness_comparison.png
    │   ├── happiness_score_variation.png
    │   ├── correlation_heatmap.png
    │   └── world_happiness_dashboard.png
    │
    ├── analysis.txt
    └── README.md

## 📊 Dataset Information

**Dataset:** World Happiness Report 2024

**Original Records:** 143

**Clean Records:** 140

**Incomplete Records Removed:** 3

**Total Features:** 12

### Key Features Analyzed

- Happiness Score
- Log GDP per Capita
- Social Support
- Healthy Life Expectancy
- Freedom to Make Life Choices
- Generosity
- Perceptions of Corruption

**Dataset Source:**

https://raw.githubusercontent.com/Escavine/World-Happiness/main/World-happiness-report-2024.csv

## 🛠️ Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook
- CSV Data Processing

## 📈 Analysis Performed

1. Dataset loading and cleaning
2. Descriptive statistical analysis
3. Top 10 happiest countries
4. Bottom 10 happiest countries
5. Happiness score distribution
6. GDP vs Happiness analysis
7. Social Support vs Happiness analysis
8. Regional happiness comparison
9. Box plot and outlier detection
10. Correlation analysis
11. Final analytical dashboard

## 🔍 Key Findings

- **Highest Happiness Score:** Finland (7.741)
- **Lowest Happiness Score:** Afghanistan (1.721)
- **Average Happiness Score:** 5.5308
- **Highest Regional Average:** North America and ANZ (6.93)
- **Lowest Regional Average:** South Asia (3.90)

### Correlation with Happiness

- Social Support: 0.814
- GDP per Capita: 0.769
- Healthy Life Expectancy: 0.760
- Freedom: 0.644
- Perceptions of Corruption: 0.452
- Generosity: 0.130

Social support showed the strongest positive correlation with happiness among the analyzed factors.

These correlations indicate statistical relationships, not causation.

## 📊 Visualizations

The project includes nine visualizations:

- Top 10 Happiest Countries
- Bottom 10 Happiest Countries
- Happiness Score Distribution
- GDP vs Happiness
- Social Support vs Happiness
- Regional Happiness Comparison
- Happiness Score Variation
- Correlation Heatmap
- World Happiness Dashboard

All generated visualizations are available in the `outputs/` directory.

## 💡 Skills Demonstrated

- Data loading and preprocessing
- Handling incomplete records
- NumPy arrays and numerical operations
- Descriptive statistics
- Correlation analysis
- Outlier detection using IQR
- Data visualization using Matplotlib
- Analytical thinking and interpretation
- Jupyter Notebook documentation

## 🚀 How to Run

1. Clone this repository.
2. Open the project folder.
3. Install the required libraries:

       pip install numpy matplotlib

4. Open the notebook:

       notebooks/world_happiness_analysis.ipynb

5. Run the notebook cells sequentially.

## 🎓 Project Outcome

This project strengthened practical skills in Python-based data analysis, statistical interpretation, and visualization.

It demonstrates the application of data science techniques to a real-world global dataset.

---

## Detailed Analysis Report

For the complete analytical report, including statistical tables, detailed interpretations, correlation results and business findings, refer to:

📄 **[View Detailed Analysis Report](./analysis.md)**

---

<p align="center">
  <strong>End of Report</strong>
</p>

<p align="center">
  <em>Turning data into meaningful insights.</em>
</p>

<p align="center">
  <strong>Author: ASWIN KUMAR V</strong><br>
  B.Tech – Artificial Intelligence and Data Science<br>
  <a href="https://github.com/aswinkumarv23451-cpu">GitHub Profile</a>
</p>