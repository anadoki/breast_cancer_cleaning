# Breast Cancer Dataset – Cleaning and Exploratory Data Analysis

This is a small practice project where I worked through the process of cleaning and exploring the Breast Cancer dataset from Kaggle.

Dataset link: https://www.kaggle.com/datasets/wasiqaliyasir/breast-cancer-dataset

The goal was not to build a machine learning model, but to get comfortable with pandas, data profiling, and understanding the structure of a dataset before doing anything else with it.

## Tools Used

- Python (3.11)
- Jupyter Lab
- Virtual Environment (venv)
- pandas, numpy
- matplotlib, seaborn

## Process

### Data Setup

- Created a virtual environment and installed required libraries
- Loaded the dataset in Jupyter Lab
- Inspected the first few rows, shape, column names, and data types

### Data Cleaning

- Renamed columns to lowercase with underscores
- Dropped unnecessary columns like `id`
- Checked for missing values and confirmed there were none

### Feature Profiling

- Wrote a loop to calculate min, quartiles, median, max for each numeric feature
- Detected outliers using the IQR method
- Created an outlier summary table showing how many outliers each feature contains

### Visual Exploration

- Created histograms to understand the distribution of key features
- Used boxplots grouped by diagnosis to see how features differ between benign and malignant tumors
- Generated a correlation heatmap to check for highly correlated features

### Target Variable Encoding

- Mapped the `diagnosis` column from M/B to 1/0 for future modeling

### Output

- Exported a cleaned version of the dataset (`breast_cancer_clean.csv`)
- Saved the outlier summary table as `outlier_summary.csv`

## Files in This Repository

- `breast_cancer_cleaning.ipynb`: Notebook with all steps from loading to exporting
- `breast_cancer_clean.csv`: Cleaned dataset
- `outlier_summary.csv`: Outlier profile of numeric features
- `README.md`: Project summary

## Why I Did This

This was my first hands-on project using pandas and data analysis techniques. I wanted to practice loading and inspecting data, cleaning it properly, profiling features, and building visual understanding through EDA. This project helped me understand how to structure an analysis and document each step clearly.

