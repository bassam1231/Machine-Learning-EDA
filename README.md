# Titanic Dataset Exploratory Data Analysis (EDA)

## Overview
This repository contains an exploratory data analysis (EDA) project on the Titanic dataset. The goal of this analysis is to explore the dataset, clean and preprocess the data, and uncover insights regarding the survival of passengers based on different features.

## Dataset
The dataset used in this analysis includes three files:
- **train.csv**: Training dataset with labeled survival outcomes.
- **test.csv**: Unlabeled dataset used for testing predictions.
- **gender_submission.csv**: Sample submission file.

### Key Observations
- **Age Distribution**:
  - Most passengers are young adults.
  - 76 passengers were younger than 40 years old.
  - 341 passengers were older than 40 years old, with most in their 30s.
  - **82% of the passengers were young adults.**

- **Class Distribution**:
  - The third class was the most occupied.
  - Passenger distribution by class:
    1. **Third Class**: 217 passengers
    2. **First Class**: 107 passengers
    3. **Second Class**: 93 passengers
  - **More than 52% of passengers traveled in third class.**

- **Gender Distribution**:
  - **Males:** 265 passengers
  - **Females:** 152 passengers
  - **Passengers were more likely to be male (~64% male).**

- **Survival Rates**:
  - **Total Survivors:** 152 passengers (~36% survival rate)
  - **Total Deaths:** 266 passengers (~64% mortality rate)

## Objectives
- Perform data cleaning and handle missing values.
- Conduct exploratory analysis to understand patterns and correlations.
- Visualize key insights using graphs and plots.
- Identify factors that influenced passenger survival.

## Key Steps in the Analysis

### 1. Data Cleaning & Preprocessing
- Handling missing values in columns like `Age`, `Cabin`, and `Embarked`.
- Encoding categorical variables.
- Creating new features (e.g., family size, title extraction from names).

### 2. Exploratory Data Analysis (EDA)
- Summary statistics and data distributions.
- Visualizing survival rates across different features.
- Correlation analysis among numerical variables.

### 3. Visualizations
- Survival rate distribution.
- Survival by gender, class, and embarkation point.
- Age distribution and survival rates.
- Correlation heatmaps.

## Technologies Used
- **Python**: Primary programming language.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: For data preprocessing and feature engineering.

## How to Use

### Clone the Repository
```bash
git clone https://github.com/your-username/Titanic-EDA.git
cd Titanic-EDA
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run the Jupyter Notebook
```bash
jupyter notebook Titanic_EDA.ipynb
```

## Future Improvements
- Feature engineering for predictive modeling.
- Building a machine learning model to predict survival.
- Deployment of an interactive dashboard for visualization.

---
