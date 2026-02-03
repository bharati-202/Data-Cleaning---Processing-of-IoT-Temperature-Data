# Data Cleaning & Processing of IoT Temperature Data

This repository provides a comprehensive workflow for cleaning and processing IoT temperature data collected from various sensors. The project demonstrates essential data preprocessing steps, including handling missing values, detecting and removing outliers, and visualizing temperature trends over time.

## Features

- **Missing Value Handling:** The code identifies missing temperature readings and fills them using the mean value, ensuring the dataset remains consistent for analysis.
- **Outlier Detection:** Two popular methods are implemented for outlier removal:
  - **Z-score Method:** Removes data points where temperature values are more than three standard deviations from the mean.
  - **IQR Method:** Filters out values outside the interquartile range (1.5 times the IQR from Q1 and Q3).
- **Visualization:** The notebook includes scatter plots and histograms to help users understand temperature distributions and trends.

## Contents

- `data/IOT-temp.csv`: Raw temperature log data.
- `notebooks/temperature.ipynb`: Jupyter Notebook with step-by-step data cleaning and visualization.
- `requirements.txt`: List of Python dependencies.
- `README.md`: Project overview and instructions.

