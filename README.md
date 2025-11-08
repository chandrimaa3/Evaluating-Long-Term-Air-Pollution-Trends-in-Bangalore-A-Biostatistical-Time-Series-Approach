# Evaluating Long-Term Air Pollution Trends in Bangalore: A Biostatistical Time Series Approach

## 📌 Project Overview

This project applies advanced biostatistical time-series analysis to evaluate long-term air pollution trends in Bangalore and assess their potential public health implications. Building on a comprehensive literature review of global and Indian air quality studies, this applied project bridges the gap between raw environmental data and actionable public health insights.

It leverages historical daily AQI data to identify seasonal patterns, forecast future pollution levels using statistical models (ARIMA), and translate these technical forecasts into health risk categories based on standard epidemiological guidelines.

## 🎯 Objectives

+ Literature-Informed Analysis: Guided by previous research gaps, focus on specific pollutants and seasonal variations relevant to Bangalore's urban context.

+ Data Harmonization: Consolidate and clean multi-year daily air quality datasets from monitoring stations.

+ Trend & Seasonality Detection: Utilize time-series decomposition to isolate long-term trends from seasonal fluctuations (e.g., winter spikes).

+ Predictive Modeling: Develop and validate ARIMA models to forecast near-term AQI levels.

+ Public Health Translation: Interpret forecasted levels into actionable health advisories for vulnerable populations (e.g., asthmatics, elderly), directly addressing public health concerns highlighted in global burden of disease studies.

## 📚 Literature Review & Background

A foundational literature review (see docs/literature_review.pptx) identified key research gaps that this project aims to address:

+ **Gap:** Need for more localized, city-specific forecasting models that account for unique urban factors in Indian cities like Bangalore.

+ **Gap:** Bridging the disconnect between technical meteorological forecasting and practical public health communication.

+ **Focus:** This project specifically targets these gaps by applying proven statistical methods to local data to generate health-centric outputs.

<img width="757" height="590" alt="image" src="https://github.com/user-attachments/assets/0420fb37-01ff-4f7e-b279-1f399b7b956a" />


## 🛠️ Technologies & Methods

+ **Language:** Python 3.x

+ **Data Manipulation:** Pandas, NumPy

+ **Visualization:** Matplotlib, Seaborn

+ **Statistical Modeling:** Statsmodels (ARIMA/SARIMA), Scikit-learn

+ **References:** WHO Air Quality Guidelines, CPCB Standards

## 📊 Key Findings & Health Implications

+ **Seasonal Trends:** Confirmed significant degradation in air quality during Monsoon and increasing in Winter, aligning with findings from similar urban studies in India.
<img width="543" height="514" alt="image" src="https://github.com/user-attachments/assets/a97cb074-2ce0-45a6-954f-11ca9e098f95" />

+ **Forecast Accuracy:** The ARIMA model successfully captured short-term volatility, providing a reliable baseline for weekly health advisories.

+ **Health Outlook:** Forecasts indicate a Moderate risk period ahead.

+ **Biostatistical Recommendation:** Based on current trends, public health notifications for sensitive groups should be prioritized during the months of Winter.

## 🔮 Future Improvements

+ Incorporate meteorological variables (temperature, humidity) for multivariate SARIMAX modeling as suggested in recent literature.

+ Compare statistical (ARIMA) results with machine learning approaches (LSTM, Prophet) for enhanced accuracy.

**Author:** Chandrima Hazra

**Data Source:** Central Pollution Control Board (CPCB), India
