# Titanic Dataset Exploratory Data Analysis (EDA)

## Overview
This repository contains an exploratory data analysis (EDA) project on the Titanic dataset. The goal of this analysis is to explore the dataset, clean and preprocess the data, and uncover insights regarding the survival of passengers based on different features.

## Dataset
The dataset used in this analysis is the Titanic dataset, which includes information about passengers such as:
- PassengerId
- Survived (target variable: 0 = No, 1 = Yes)
- Pclass (Ticket class: 1st, 2nd, 3rd)
- Name
- Sex
- Age
- SibSp (Number of siblings/spouses aboard)
- Parch (Number of parents/children aboard)
- Ticket
- Fare (Passenger fare)
- Cabin
- Embarked (Port of Embarkation: C = Cherbourg, Q = Queenstown, S = Southampton)

## Objectives
- Perform data cleaning and handling of missing values.
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

## Insights and Findings
- **Women had a significantly higher survival rate than men.**
- **Passengers in 1st class had better survival chances than those in 2nd or 3rd class.**
- **Children (lower age group) had a higher likelihood of survival.**
- **Passengers who embarked from Cherbourg (C) had higher survival rates.**

## Future Improvements
- Feature engineering for predictive modeling.
- Building a machine learning model to predict survival.
- Deployment of an interactive dashboard for visualization.

---

📌 *Feel free to contribute by opening issues or submitting pull requests!*
