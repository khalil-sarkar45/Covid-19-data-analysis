🦠 COVID-19 Global Data Analysis Using Python
📌 Project Overview

This project presents a comprehensive data analysis of the global COVID-19 pandemic using Python. It follows the complete data analysis lifecycle, including data acquisition, cleaning, transformation, analysis, comparison, and visualization.

The analysis is based on official time-series COVID-19 datasets and aims to uncover trends, patterns, and comparisons across countries and over time.

This project is submitted as an Individual Project and is supported by a detailed PDF report and a fully reproducible codebase.

🎯 Objectives

Analyze global COVID-19 confirmed cases and deaths

Perform country-wise aggregation and comparisons

Apply proper data cleaning and transformation techniques

Generate meaningful statistical insights

Create advanced and informative data visualizations

Maintain a professional and reproducible project structure

📂 Project Structure
covid-19-data-analysis/
├── dataset/
│   ├── time_series_covid19_confirmed_global.csv
│   └── time_series_covid19_deaths_global.csv
├── covid19_analysis.py
├── requirements.txt
├── README.md
└── COVID19_Data_Analysis_Report.pdf

📊 Dataset Description

The datasets used in this project are time-series global COVID-19 data, containing:

Country / Region

Province / State (if applicable)

Latitude & Longitude

Daily cumulative confirmed cases

Daily cumulative deaths

📁 Source format: CSV
📅 Time range: From initial outbreak to March 2023

🛠️ Technologies & Libraries Used

Python 3

Pandas – data manipulation and cleaning

NumPy – numerical operations

Matplotlib – data visualization

Seaborn – advanced statistical plots

SciPy – statistical analysis

All dependencies are listed in requirements.txt.

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/khalil-sarkar45/covid-19-data-analysis.git
cd covid-19-data-analysis

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run the Analysis
python covid19_analysis.py

🔍 Methodology

The project follows a structured data analysis pipeline:

Data Acquisition

Loading global COVID-19 datasets from CSV files

Data Cleaning

Handling missing values

Removing unnecessary columns

Ensuring correct data types

Data Transformation

Aggregating data country-wise

Reshaping time-series data for analysis

Analysis & Comparison

Country-level comparison of cases and deaths

Trend analysis over time

Statistical summaries

Visualization

Line charts for case trends

Heatmaps for correlations

Comparative plots across countries

📈 Key Insights

Countries show significantly different growth patterns in confirmed cases

Death trends closely follow confirmed case surges with a time lag

Aggregated country-level analysis provides clearer global insights than province-level data

Visualizations highlight pandemic waves and regional differences

(Detailed insights are available in the attached PDF report.)

📄 Report

A  detailed  report is included in this repository:

📘 COVID19_Data_Analysis_Report

The report contains:

Abstract

Introduction

Methodology

Analysis

Comparison

Results

Conclusion

References
