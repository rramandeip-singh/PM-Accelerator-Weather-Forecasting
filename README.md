# Weather Trend Forecasting using Machine Learning

## PM Accelerator Technical Assessment

**Candidate:** Rramandeip Singh

---

# Project Overview

This project presents a complete end-to-end machine learning workflow for weather forecasting using the **Global Weather Repository** dataset. The objective is to analyze global weather observations, identify environmental patterns, and predict temperature using multiple machine learning algorithms.

The project includes data preprocessing, exploratory data analysis (EDA), visualization, feature engineering, predictive modeling, model comparison, anomaly detection, climate analysis, air quality analysis, and geographical weather analysis.

---

# Objectives

- Perform data cleaning and preprocessing
- Explore weather data using statistical analysis and visualization
- Build multiple machine learning models
- Compare forecasting performance
- Identify the most important weather variables
- Detect unusual weather observations
- Analyze climate and air quality trends
- Demonstrate an end-to-end data science workflow

---

# PM Accelerator Mission

PM Accelerator empowers aspiring AI engineers, product managers, designers, and data professionals through hands-on learning and real-world AI projects. The program focuses on practical experience, mentorship, teamwork, and portfolio development to prepare participants for careers in artificial intelligence, machine learning, and data science.

This technical assessment demonstrates the application of those skills by solving a real-world weather forecasting problem using modern machine learning techniques.

---

# Dataset

**Dataset Name**

Global Weather Repository

**Source**

Kaggle

The dataset contains more than **152,000 weather observations** collected from cities around the world.

### Dataset includes

- Temperature
- Humidity
- Atmospheric Pressure
- Wind Speed
- Wind Direction
- Visibility
- UV Index
- Cloud Cover
- Precipitation
- Latitude
- Longitude
- Air Quality (PM2.5, PM10, CO, NO₂, Ozone)
- Date & Time
- Sunrise / Sunset

Total Features:

**41 Weather Variables**

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

# Project Workflow

## 1. Data Collection

- Load Global Weather Repository dataset
- Inspect dataset structure
- Verify data types

---

## 2. Data Cleaning

- Handle missing values
- Remove duplicate records
- Convert date columns
- Prepare numerical features

---

## 3. Exploratory Data Analysis

The project includes:

- Dataset Preview
- Descriptive Statistics
- Temperature Trend Analysis
- Temperature Distribution
- Precipitation Distribution
- Correlation Heatmap
- Boxplots
- Humidity vs Temperature
- Air Quality Analysis
- Climate Trend Analysis
- Geographical Temperature Analysis

---

# Machine Learning Models

## Linear Regression

Used as the baseline forecasting model.

Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## Random Forest

Random Forest predicts temperature using multiple environmental variables including:

- Humidity
- Pressure
- Wind Speed
- Cloud Cover
- UV Index
- Visibility
- Precipitation

Random Forest achieved the best overall performance.

---

## XGBoost

XGBoost was implemented as an advanced gradient boosting algorithm for weather prediction.

Advantages:

- Handles non-linear relationships
- High predictive accuracy
- Ensemble learning
- Strong generalization performance

---

## Ensemble Model

Predictions from

- Linear Regression
- Random Forest
- XGBoost

were combined to produce an ensemble prediction for comparison.

---

# Advanced Analysis

The project also includes:

- Feature Importance Analysis
- Isolation Forest Anomaly Detection
- Air Quality Analysis
- Climate Trend Analysis
- Geographical Weather Analysis

---

# Model Performance

| Model | MAE | RMSE | R² Score |
|------|------:|------:|------:|
| Linear Regression | 7.34 | 9.33 | 0.028 |
| Random Forest | 3.27 | 4.93 | 0.728 |
| XGBoost | 3.70 | 5.22 | 0.696 |

---

# Key Findings

- Dataset contains more than 152,000 weather observations.
- Data preprocessing ensured high-quality data.
- EDA revealed meaningful weather patterns.
- Random Forest significantly outperformed Linear Regression.
- XGBoost also produced highly accurate predictions.
- UV Index, Pressure, and Humidity were the most important features.
- Climate analysis highlighted long-term temperature variations.
- Air quality analysis showed relationships between PM2.5 and temperature.
- Geographical analysis identified the hottest countries in the dataset.

---

# Repository Structure

```
Weather-Trend-Forecasting/

│

├── Weather_Trend_Forecasting.ipynb

├── Weather_Trend_Forecasting.pdf

├── Rramandeip_Singh_Professional_Weather_Report.pdf

├── Weather_Presentation.pptx

├── GlobalWeatherRepository.csv

├── README.md

└── images/
```

---

# Results

Among all evaluated models, **Random Forest** achieved the best predictive performance by producing the lowest prediction errors and the highest R² Score. XGBoost also performed strongly and demonstrated its capability to model complex weather relationships effectively. The ensemble approach provided an additional comparison by combining predictions from multiple models. Overall, the project confirms that ensemble machine learning methods significantly improve weather forecasting accuracy compared to traditional linear models.

---

# Future Improvements

- Deep Learning (LSTM)
- Real-time Weather API Integration
- Hyperparameter Optimization
- Deployment using Streamlit
- Interactive Dashboard
- Cloud Deployment on AWS

---

# Author

## Rramandeip Singh

Post Graduate Certificate

AI Integration & Governance

Humber Polytechnic

Canada

---

# Acknowledgements

- PM Accelerator
- Kaggle
- Scikit-learn
- XGBoost
- Matplotlib
- Seaborn
- Python Community

---

# License

This project was developed for educational and portfolio purposes as part of the PM Accelerator Technical Assessment.

