# Weather Data Analysis and Classification

## Overview
This project explores weather data through detailed analysis and applies machine learning classification algorithms to predict weather conditions. The focus is on understanding patterns within the data and evaluating multiple models for effective weather prediction.

## Features
- Exploratory Data Analysis (EDA) to uncover trends and anomalies.
- Visualizations of weather parameters such as temperature and wind speed.
- Application of five classification models: Logistic Regression, SVM, Naive Bayes, Decision Tree, and K-Nearest Neighbors (KNN).
- Model performance evaluation using accuracy metrics and confusion matrices.

## Dataset
The dataset contains weather data for Seattle with 1,461 records and 6 attributes:
- **Date**: Observation date
- **Temp_max**: Maximum temperature
- **Temp_min**: Minimum temperature
- **Wind**: Wind speed
- **Weather**: Observed weather condition (e.g., sunny, rainy)

Source: [Kaggle Weather Dataset](https://www.kaggle.com/datasets/ananthr1/weather-prediction)

## Methodology
1. **Data Preprocessing**: Cleaning, type conversions, and label encoding.
2. **Visualization**: Distribution plots, pair plots, line graphs, and violin plots for trends and relationships.
3. **Model Training and Testing**:
    - Train-test split (75%-25%)
    - Models evaluated include:
      - Logistic Regression (79.5% accuracy)
      - SVM (79.5% accuracy)
      - Naive Bayes (84.15% accuracy)
      - Decision Tree (73.77% accuracy)
      - KNN (67.6% accuracy)

## Tools and Libraries
- **Data Handling**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Machine Learning**: Scikit-learn

## Results
The Naive Bayes model showed the highest accuracy (84.15%), demonstrating its effectiveness for this dataset. Visualizations provided further insights into weather patterns.
