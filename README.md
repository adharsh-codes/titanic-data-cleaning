# Titanic Data Cleaning and Exploratory Analysis

**Author:** Adharsh

## Project Overview

This project focuses on cleaning and preparing the Titanic passenger dataset using Python, Pandas, and Matplotlib.

## Objectives

- Load and inspect the Titanic dataset.
- Identify and handle missing values.
- Encode categorical columns.
- Visualize passenger age distribution.
- Export the cleaned dataset as a CSV file.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Project Workflow

### 1. Data Loading and Inspection
Loaded the dataset using Pandas and inspected it with `head()`, `info()`, and `describe()`.

### 2. Missing Value Handling
- Filled missing `Age` values using the median.
- Filled missing `Embarked` values using the mode.
- Removed `Cabin` because it contained many missing values.

### 3. Categorical Encoding
- Encoded `Sex`: male = 0, female = 1.
- Applied one-hot encoding to `Embarked`, creating `Embarked_C`, `Embarked_Q`, and `Embarked_S`.

### 4. Data Visualization
Created a histogram using Matplotlib to visualize passenger age distribution.

### 5. Exporting the Dataset
Saved the cleaned dataset as `titanic_cleaned.csv`.

## Final Results

| Metric | Result |
|---|---:|
| Original rows | 891 |
| Original columns | 12 |
| Final rows | 891 |
| Final columns | 13 |
| Missing values after cleaning | 0 |

## Project Files

- `Titanic_Data_Cleaning.ipynb` - Notebook containing code and analysis.
- `titanic_cleaned.csv` - Cleaned dataset.
- `README.md` - Project documentation.

## How to Run

1. Install Python and Jupyter Notebook.
2. Install dependencies:

   `python -m pip install pandas matplotlib`

3. Place `train.csv` in the notebook's working directory.
4. Open `Titanic_Data_Cleaning.ipynb`.
5. Run the notebook cells in order.

## Learning Outcomes

- Data inspection and cleaning with Pandas.
- Handling missing values.
- Encoding categorical features.
- Creating visualizations with Matplotlib.
- Exporting cleaned datasets.

## Future Improvements

- Perform additional exploratory data analysis.
- Explore relationships between passenger attributes and survival.
- Build a survival prediction model as a separate extension.

---

**Author:** Adharsh
