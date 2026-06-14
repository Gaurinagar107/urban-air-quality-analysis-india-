# 🌍 Urban Air Quality Analysis in India

## 📌 Overview
This project presents a comprehensive analysis of urban air quality across major Indian cities using environmental data from the **Central Pollution Control Board (CPCB)**[cite: 1]. The study combines exploratory data analysis, statistical visualization, and machine learning techniques to understand pollution trends and predict Air Quality Index (AQI) levels[cite: 1].

The analysis focuses on four key pollutants—**SO₂, NO₂, PM₁₀, and PM₂.₅**—across multiple cities between **2019 and 2023**[cite: 1]. In addition to identifying temporal and spatial pollution patterns, a **Random Forest Regression model** was developed to forecast AQI values and evaluate predictive performance across different urban environments[cite: 1].

---

## 🎯 Key Objectives
* 📈 **Analyze long-term air quality trends** across Indian cities[cite: 1].
* 🍂 **Identify seasonal and geographical variations** in pollutant concentrations[cite: 1].
* 🏙️ **Compare pollution patterns** between metropolitan and regional urban centers[cite: 1].
* 🤖 **Develop machine learning models** for AQI prediction[cite: 1].
* 📊 **Evaluate model performance** using MSE, MAE, R², and residual analysis[cite: 1].
* 💡 **Generate insights** that support environmental monitoring and policy decision-making[cite: 1].

---

## 📊 Dataset
* **Source:** Central Pollution Control Board (CPCB), Government of India[cite: 1]
* **Pollutants Analyzed:**
  * 🧪 Sulphur Dioxide (SO₂)[cite: 1]
  * 💨 Nitrogen Dioxide (NO₂)[cite: 1]
  * 🌫️ Particulate Matter (PM₁₀)[cite: 1]
  * 😷 Fine Particulate Matter (PM₂.₅)[cite: 1]
* **Study Period:** 2019–2023 *(excluding 2020 due to COVID-19-related monitoring disruptions)*[cite: 1]

---

## ⚙️ Project Architecture & Methodology



### 1. Data Processing
* Data cleaning and preprocessing using `Pandas` and `NumPy`[cite: 1].
* Handling missing values and standardizing city-level datasets[cite: 1].
* Temporal feature extraction and transformation[cite: 1].

### 2. Exploratory Data Analysis
* Trend analysis across cities and years[cite: 1].
* Seasonal pollution assessment[cite: 1].
* Heatmap visualization of AQI patterns[cite: 1].
* Comparative pollutant analysis[cite: 1].

### 3. Machine Learning
* **Algorithm:** Random Forest Regression[cite: 1]
* **Feature Engineering Matrix:**[cite: 1]
  * `Year`, `Month`, `Day`, `Day of Week`[cite: 1]
  * `Day of Year`, `Week of Year`, `Quarter`[cite: 1]
  * `Month Start/End Indicators`[cite: 1]
  * `City Encoding`[cite: 1]

---

## 🖼️ Visualizations & Analysis
Below are the key analytical screenshots and dashboards generated during execution[cite: 1]:

| Analysis Component | Visual Output |
| :--- | :--- |
| **Trend & Distribution Analysis**<br>Initial visual assessment of dataset distributions and historical pollution benchmarks[cite: 1]. | ![_📊 Distribution Trend_](./Screenshot%202026-04-09%20170359.png)[cite: 1] |
| **Pollutant Concentration Tracking**<br>Granular observation mapping variance across selected monitoring stations[cite: 1]. | ![_📈 Pollutant Tracking_](./Screenshot%202026-04-09%20170429.png)[cite: 1] |
| **Geographical & Spatial Variations**<br>Cross-city pollutant comparisons detailing regional variances between inland and coastal hubs[cite: 1]. | ![_🌍 Spatial Variation_](./Screenshot%202026-04-09%20170509.png)[cite: 1] |
| **Seasonal Peaks & Correlation Matrix**<br>Heatmaps showing how particulate matter behaves across different seasons and quarters[cite: 1]. | ![_🍂 Seasonal Metrics_](./Screenshot%202026-04-09%20170804.png)[cite: 1] |
| **Random Forest Model Outputs**<br>Evaluation metrics demonstrating predictive vs. actual AQI values alongside residual diagnostic metrics[cite: 1]. | ![_🤖 Model Evaluation_](./Screenshot%202026-04-10%20130153.png)[cite: 1] |

---

## 📈 Model Performance Summary
| Metric | Value |
| :--- | :--- |
| **R² Score** | **~0.82**[cite: 1] |
| **Mean Absolute Error (MAE)** | Optimized via robust temporal engineering[cite: 1] |
| **Mean Squared Error (MSE)** | Evaluated via residual error diagnostics[cite: 1] |

---

## 🔍 Key Findings
* 😷 **PM₂.₅** emerged as the most critical contributor to poor air quality across most cities[cite: 1].
* 🏔️ **Northern inland cities** consistently recorded higher particulate pollution levels than coastal cities[cite: 1].
* ❄️ **Strong seasonal pollution peaks** were observed during winter months[cite: 1].
* 🧪 **SO₂ levels** remained relatively stable and within acceptable limits in most locations[cite: 1].
* 🛠️ **Enhanced feature engineering** significantly improved AQI prediction accuracy, with the Random Forest model achieving an **R² score of approximately 0.82**[cite: 1].

---

## 🛠️ Technologies Used
* **Languages:** Python 🐍
* **Data Core:** Pandas, NumPy[cite: 1]
* **Visualization:** Matplotlib, Seaborn[cite: 1]
* **Machine Learning:** Scikit-learn (Random Forest Regression)[cite: 1]

---

## 🚀 Future Improvements
* 🌤️ Incorporate meteorological variables such as temperature, humidity, and wind speed[cite: 1].
* ⚡ Explore advanced forecasting techniques such as **XGBoost** and **LSTM models**[cite: 1].
* 💻 Develop an interactive dashboard for real-time AQI monitoring and visualization[cite: 1].

---
**Author:** ✒️ **Gauri Nagar**[cite: 1]  
*BBA Analytics & Big Data, UPES*[cite: 1]

```
