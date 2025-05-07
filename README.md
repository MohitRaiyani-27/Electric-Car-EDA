# Electric-Car-EDA
# 🔋 Electric Vehicle Exploratory Data Analysis (EDA)

This project dives into a dataset of electric vehicles to uncover trends, patterns, and insights related to EV specifications such as range, battery capacity, power, and more. The analysis is done using Python in a Jupyter Notebook with clear visualizations and commentary.

## 📌 Project Overview

The goal of this project is to perform an in-depth exploratory data analysis (EDA) on a dataset of electric vehicles. We aim to:

- Understand the distribution of EV brands and models.
- Analyze battery capacity, power output, and vehicle efficiency.
- Investigate the relationship between features like range and battery size.
- Identify outliers and interesting trends in the EV market.

## 📁 Files Included


## 🧪 Technologies Used

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn

## 📊 Key Analyses & Visuals

- **Missing Value Heatmaps**: To assess data quality and coverage.
- **Top Brands by Model Count**: Bar chart of most represented EV brands.
- **Distribution of Power (kW)**: Histograms showing how power varies among EVs.
- **Range vs. Battery Capacity**: Scatter plots examining correlation between range and battery size.
- **Boxplots** for range and power to detect outliers.
- **Efficiency Calculations**: Derived feature showing how efficiently EVs convert battery to range.

## 🔍 Notable Findings

- **Tesla** leads in range and performance but isn't the most common brand.
- **Battery Capacity and Range** have a strong positive correlation.
- Some older EV models show lower efficiency, indicating rapid improvements in EV tech over time.
- A few models appear as outliers with exceptionally high or low power-to-range ratios.

## 📂 Dataset Info

- **Rows**: 239,746
- **Columns**: 20+
- Fields include: `Make`, `Model`, `Range_km`, `Battery_kWh`, `Power_kW`, `Efficiency`, etc.

> **Note**: This dataset may have been cleaned for missing values and feature engineering before EDA.

## 📈 Future Work

- Time-series analysis on EV evolution by year.
- Price-to-performance modeling.
- Geographical analysis if location data is available.

## 🤝 Acknowledgments

Thanks to the data source providers and the open-source community for tools that made this analysis possible.


