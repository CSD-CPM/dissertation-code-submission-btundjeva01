# Machine Learning Models for Renewable Energy

## MSc Dissertation Project

### Overview

This repository contains the complete implementation developed for the MSc dissertation entitled **"Machine Learning Models for Renewable Energy"**. The study investigates how meteorological conditions influence daily solar energy production at the FEC Novaci photovoltaic power plant in North Macedonia and develops machine learning models capable of accurately forecasting daily energy output.
The project combines exploratory data analysis, feature engineering, machine learning model development, forecasting, and performance evaluation using ten years of operational photovoltaic plant data. The ultimate objective is to provide a practical forecasting tool that can support operational planning and decision-making in renewable energy production.

### Research Objectives

The main objectives of the study are:

* Analyse long-term solar production and weather data.
* Investigate the relationship between meteorological variables and photovoltaic energy generation.
* Develop and evaluate machine learning forecasting models.
* Compare Random Forest, XGBoost, and Linear Regression approaches.
* Identify the most influential features affecting production.
* Forecast future solar energy generation.
* Provide a practical forecasting framework for renewable energy operations.

### Dataset

The analysis is based on operational data collected from the FEC Novaci photovoltaic power plant and includes:

* Daily energy production (kWh/day)
* Temperature
* Cloud coverage
* Wind speed
* Fog occurrence
* Electricity market price data
* Time-based and lag-derived features

The dataset spans approximately ten years of observations and was used for model training, testing, and forecasting.

### Methodology

The project follows a complete machine learning workflow:

1. Data collection and preprocessing.
2. Exploratory data analysis (EDA).
3. Feature engineering and temporal encoding.
4. Model training and hyperparameter tuning.
5. Model evaluation and comparison.
6. Feature importance analysis.
7. Production forecasting and revenue estimation.

### Models Implemented

The following machine learning models were evaluated:

* Random Forest Regressor
* XGBoost Regressor
* Linear Regression

### Results

The Random Forest model achieved the best overall performance:

* R² = 0.9781
* MAPE = 4.17%
* MAE ≈ 9.6 MWh/day

The model successfully captured seasonal production patterns and generated accurate forecasts for future energy production.

### Repository Contents

* `dissertation.ipynb` – Complete notebook containing preprocessing, analysis, modelling, visualisations, and forecasting.
* Generated figures and evaluation outputs embedded within the notebook.
* Full implementation of the forecasting workflow used throughout the dissertation.

### Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn

### Author

**Brankica Tundjeva**

MSc Data Science and Artificial Intelligence

University of York Europe Campus (CITY College)

### Academic Year

2025–2026
