# Colorado Motor Vehicle Sales Data Analysis Project

## Overview
This project analyzes motor vehicle sales data across various counties in Colorado, segmented by year and quarter. The objective is to uncover trends, identify significant findings, and provide actionable insights for businesses, policymakers, and stakeholders. Predictive models, such as ARIMA and SARIMA, are also implemented to forecast future sales trends.

## Features
- **Data Cleaning and Preparation**: Ensuring consistency and accuracy in the dataset.
- **Exploratory Data Analysis (EDA)**: Visualization and statistical analysis of sales data.
- **Time Series Analysis**: Identifying trends, seasonality, and stationarity.
- **Predictive Modeling**: Forecasting future sales using ARIMA and SARIMA models.
- **Key Insights and Recommendations**: Business and policy suggestions based on findings.

## Dataset
The dataset used in this project, `colorado_motor_vehicle_sales.csv`, contains the following columns:
- `Year`: The calendar year of the sales data.
- `Quarter`: The quarter of the year (Q1 to Q4).
- `County`: Name of the county in Colorado.
- `Sales`: Total dollar amount of motor vehicle sales.

## Key Findings
1. **Maximum Sales**: Highest sales were recorded in Q3 of 2015 in Arapahoe County ($916.91 million).
2. **Minimum Sales**: Lowest sales occurred in Q1 of 2009 in Fremont County ($6.27 million).
3. **High-Performing Counties**: Arapahoe, El Paso, Jefferson, Adams, and Denver.
4. **Seasonal Trends**: Q3 consistently shows peak sales, while Q1 has the lowest sales.
5. **Predictive Modeling**: SARIMA model effectively forecasts future sales, capturing seasonal trends and patterns.

## Technologies Used
- **Python**: Core programming language
  - `Pandas`: Data manipulation
  - `Matplotlib` & `Seaborn`: Visualization
  - `Statsmodels`: Statistical analysis and modeling
  - `ARIMA`/`SARIMA`: Time series forecasting
- **Jupyter Notebook**: For interactive development and analysis

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/RafiQamar/colorado-vehicle-sales-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd colorado-vehicle-sales-analysis
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Colorado\ Motor\ Vehicle\ Sales\ Data\ Analysis\ Project.ipynb
   ```
2. Run the cells step-by-step to explore the analysis and visualizations.
3. Modify the notebook to experiment with the data or test additional models.

## File Structure
```
project-root/
├── data/
│   └── colorado_motor_vehicle_sales.csv  # Dataset
├── notebooks/
│   └── Colorado Motor Vehicle Sales Data Analysis Project.ipynb  # Analysis notebook
├── README.md                             # Project description
├── requirements.txt                      # Python dependencies
├── Colorado Motor Vehicle Sales Data Analysis Report.pdf                      # Analysis report
└── visuals/                              # Generated visualizations
```

## Results
The final report summarizes key insights, statistical findings, and model forecasts. It includes actionable recommendations for optimizing sales strategies and policy interventions.

## Contributions
Contributions are welcome! Please fork the repository and create a pull request with detailed information about your changes.


## Contact
For any questions or feedback, feel free to reach out:
- **Email**: rafiqamar9@gmail.com
- **Linkedin**:[Rafi Qamar](https://www.linkedin.com/in/rafi-qamar/)
- **GitHub**: [RafiQamar](https://github.com/RafiQamar)

---
Thank you for exploring this project!
