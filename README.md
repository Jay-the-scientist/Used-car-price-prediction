# Automobile Data Analysis

## Objective
Analyze factors affecting price, fuel efficiency and vehicle performance using a historical automobile dataset.

## Description
This project involves exploring and modeling a dataset containing specifications of various automobiles. The goal is to identify relationships between attributes like engine size, horsepower, and weight with miles-per-gallon (MPG), and to build predictive models to predict price based on the features.

## Installation
Install required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Dataset
- **Source:** UCI Machine Learning Repository – Auto MPG Dataset
- **Content:** 398 entries including features such as MPG, cylinders, displacement, horsepower, weight, acceleration, model year, and origin.

## Tools & Technologies
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology
- **Data Cleaning:** Handled missing values and data type conversions.
- **Exploratory Data Analysis (EDA):** Visualized distributions and correlations (e.g., weight vs. MPG).
- **Feature Engineering:** Created new features and transformed categorical variables.
- **Modeling:** Linear Regression and Multiple Linear Regression models were trained and evaluated.
- **Evaluation:** Used R² score and RMSE to assess model performance.

## Insights Gained
- Heavier cars tend to have lower MPG, confirming a negative correlation between weight and fuel efficiency.
- Horsepower also negatively impacts MPG, though to a lesser degree.
- Linear regression offered a reasonable predictive baseline for MPG.

## Visualizations
