# Data Cleaning - Titanic Dataset

## Objective
The objective of this project is to clean the Titanic dataset by handling missing values, removing unnecessary columns, checking duplicates, and performing basic data visualization for better understanding of the dataset.

## Dataset
Titanic Dataset (Kaggle)

## Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Steps Performed
- Loaded the Titanic dataset
- Explored the dataset using `head()`, `info()`, and `describe()`
- Checked missing values
- Filled missing values in the **Age** column using **Median**
- Filled missing values in the **Embarked** column using **Mode**
- Removed the **Cabin** column due to a large number of missing values
- Checked for duplicate records
- Saved the cleaned dataset as **cleaned_data.csv**

## Additional Analysis
After cleaning the dataset, basic data visualizations were created using Matplotlib to understand the data better.

Visualizations:
- Survival Count (Bar Chart)
- Passenger Gender Distribution (Bar Chart)
- Passenger Class Distribution (Bar Chart)
- Age Distribution (Histogram)
- Age Box Plot
- Gender Distribution (Pie Chart)

## Files
- CleaningData.ipynb
- train.csv
- cleaned_data.csv
- README.md

## Outcome
The dataset was successfully cleaned and prepared for further data analysis. Basic visualizations were also created to better understand the dataset.