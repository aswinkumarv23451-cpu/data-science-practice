Bike Sharing Demand Analysis Using Python & NumPy

A data analytics project exploring real-world bike-sharing rental patterns using Python, NumPy and Matplotlib.

Project Overview

This project analyses the UCI Bike Sharing Dataset (2011–2012) to understand how seasons, weather conditions, working days, customer segments and time influence bike rental demand.

The project uses numerical computing, statistical analysis, data filtering, correlation analysis and visualization to extract meaningful insights.

Problem Statement

How can historical bike-sharing data be analysed to identify rental demand patterns and support better operational and business decisions?

Technologies Used

- Python
- NumPy
- Matplotlib
- Jupyter Notebook
- Git and GitHub

Dataset

UCI Bike Sharing Dataset

- Daily records: 731
- Hourly records: 17,379
- Period: 2011–2012

Dataset source: https://archive.ics.uci.edu/dataset/275/bike+sharing+dataset

Project Features

- Daily rental demand classification
- Seasonal demand analysis
- Weather condition analysis
- Working-day vs non-working-day comparison
- Casual vs registered customer analysis
- Hourly rental demand analysis
- Temperature, humidity and windspeed statistics
- Correlation matrix analysis
- Top five highest-demand days identification
- Data visualization using Matplotlib

Key Findings

- Total daily rentals: 3,292,679
- Registered customers contribute approximately 81.17% of total rentals.
- Fall has the highest average daily rental demand.
- Spring has the lowest average daily rental demand.
- 5 PM has the highest average hourly rental demand.
- 4 AM has the lowest average hourly rental demand.
- Temperature has the strongest positive correlation with daily rental demand among the weather variables analysed.

Data Visualizations

1. Seasonal Rental Demand

"Seasonal Demand" (outputs/seasonal_demand.png)

2. Hourly Rental Demand

"Hourly Demand" (outputs/hourly_demand.png)

3. Customer Segment Distribution

"Customer Segments" (outputs/customer_segments.png)

4. Correlation Heatmap

"Correlation Heatmap" (outputs/correlation_heatmap.png)

Business Recommendations

- Improve bike availability during peak demand hours.
- Plan seasonal inventory according to historical demand.
- Introduce offers to attract casual customers.
- Develop customer retention strategies for registered users.
- Consider weather conditions when planning operations.

Project Structure

Bike_Sharing_Analysis/
│
├── data/
│   ├── day.csv
│   └── hour.csv
│
├── notebooks/
│   └── bike_sharing_numpy.ipynb
│
├── outputs/
│   ├── seasonal_demand.png
│   ├── hourly_demand.png
│   ├── customer_segments.png
│   ├── correlation_heatmap.png
│   └── analysis_results.txt
│
└── README.md

How to Run

1. Clone this repository.
2. Install Python and the required libraries.
3. Open the notebook using Jupyter Notebook.
4. Select the appropriate Python kernel.
5. Run the notebook cells sequentially.

Install the required libraries:

pip install numpy matplotlib notebook

Future Improvements

- Perform deeper exploratory data analysis using Pandas.
- Build interactive dashboards.
- Develop bike rental demand prediction models using Scikit-learn.
- Explore machine learning techniques for demand forecasting.

Conclusion

This project demonstrates practical applications of NumPy and Python in real-world data analysis. It transforms raw bike-sharing data into statistical findings, visual insights and actionable business recommendations.