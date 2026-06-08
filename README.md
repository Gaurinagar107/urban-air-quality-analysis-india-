# urban-air-quality-analysis-india-
Overview

This project presents a comprehensive analysis of urban air quality across major Indian cities using environmental data from the Central Pollution Control Board (CPCB). The study combines exploratory data analysis, statistical visualization, and machine learning techniques to understand pollution trends and predict Air Quality Index (AQI) levels.

The analysis focuses on four key pollutants—SO₂, NO₂, PM₁₀, and PM₂.₅—across multiple cities between 2019 and 2023. In addition to identifying temporal and spatial pollution patterns, a Random Forest Regression model was developed to forecast AQI values and evaluate predictive performance across different urban environments.

Key Objectives

Analyze long-term air quality trends across Indian cities.
Identify seasonal and geographical variations in pollutant concentrations.
Compare pollution patterns between metropolitan and regional urban centers.
Develop machine learning models for AQI prediction.
Evaluate model performance using MSE, MAE, R², and residual analysis.
Generate insights that support environmental monitoring and policy decision-making.
Dataset

Source: Central Pollution Control Board (CPCB), Government of India

Pollutants Analyzed:

Sulphur Dioxide (SO₂)
Nitrogen Dioxide (NO₂)
Particulate Matter (PM₁₀)
Fine Particulate Matter (PM₂.₅)

Study Period:

2019–2023 (excluding 2020 due to COVID-19-related monitoring disruptions)
Methodology
Data Processing
Data cleaning and preprocessing using Pandas and NumPy
Handling missing values and standardizing city-level datasets
Temporal feature extraction and transformation
Exploratory Data Analysis
Trend analysis across cities and years
Seasonal pollution assessment
Heatmap visualization of AQI patterns
Comparative pollutant analysis
Machine Learning
Random Forest Regression
Feature Engineering:
Year
Month
Day
Day of Week
Day of Year
Week of Year
Quarter
Month Start/End Indicators
City Encoding
Model Evaluation
Mean Squared Error (MSE)
Mean Absolute Error (MAE)
R² Score
Residual Error Analysis
Key Findings
PM₂.₅ emerged as the most critical contributor to poor air quality across most cities.
Northern inland cities consistently recorded higher particulate pollution levels than coastal cities.
Strong seasonal pollution peaks were observed during winter months.
SO₂ levels remained relatively stable and within acceptable limits in most locations.
Enhanced feature engineering improved AQI prediction accuracy, with the Random Forest model achieving an R² score of approximately 0.82.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Random Forest Regression
Future Improvements
Incorporate meteorological variables such as temperature, humidity, and wind speed.
Explore advanced forecasting techniques such as XGBoost and LSTM models.
Develop an interactive dashboard for real-time AQI monitoring and visualization.
Author

Gauri Nagar
BBA Analytics & Big Data, UPES
