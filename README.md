# Breast Cancer Dataset – Cleaning & EDA

>This is a small practice project where I worked through the process of cleaning and exploring the Breast Cancer dataset.
>
>The goal wasn’t to build a model here, but to really get comfortable with Pandas, data profiling, and understanding what’s inside a dataset before doing anything else with it.
## Process
- Created a virtual environment to install numpy,pandas,matplotlib
- Loaded and inspected the dataset in Jupyter Lab
- Looked at the first few rows, checked the shape, and reviewed column names and data types.
- Cleaned up the structure
- Renamed columns so they’re consistent (lowercase, underscores instead of spaces).
- Dropped a completely empty column that had no use.
- Checked for missing values
- Confirmed there were none to worry about.
- Profiled numeric features
- Wrote a loop to calculate min, quartiles, median, max, and detect outliers using the IQR method.
- Created an outlier summary table showing how “outlier‑heavy” each feature is.
- Explored with visuals
- Made boxplots and histograms for a few columns to see distributions and confirm what the summary table showed.
- Encoded the target variable
- Mapped diagnosis from M/B to 1/0 for easier numeric work later.
- Saved the results
- Exported a cleaned dataset (breast_cancer_clean.csv)
- Saved my outlier summary (outlier_summary.csv)
## Files in this repo
**breast_cancer_cleaning.ipynb** – the notebook with all steps, from loading to saving.
**breast_cancer_clean.csv** – cleaned version of the dataset.
**outlier_summary.csv** – outlier profile for all numeric columns.
**README.md** – this file!
## Why I did this
This is my first practice project with Pandas and data analysis in general. I wanted a hands‑on way to practice with Pandas and data cleaning and profiling. Learnt about boxplots as well. 

