# Time-Series-Analysis-and-Forecasting-with-Python

Welcome to the comprehensive guide on Time-Series Analysis and Forecasting using Python. This repository is designed to equip you with the knowledge, tools, and techniques to tackle the challenges of analyzing and forecasting time-series data. Whether you're a beginner curious about the basics of time-series analysis or an advanced practitioner aiming to delve into the depths of forecasting models, this guide has something for you.

The contents are structured to provide a logical progression, starting with an introduction to the concepts and practices of time-series analysis, followed by data visualization techniques, exploratory data analysis (EDA), and more in-depth data analysis. We then transition into various forecasting methodologies, including classical statistical models, cutting-edge deep learning approaches, and the application of Facebook's Prophet tool for both univariate and multivariate forecasting scenarios.

Cheers!!

## Contents

- **[Datasets Info](Datasets_Info.md)**

- **[Introduction to Time Series Analysis(Theory)](Introduction_TSA.md)**
  
     - Taxonomy of Time Series Analysis Domain
     - Best Practices for Forecasting Model Selection
     - Simple and Classical Forecasting Methods
     - Time Series to Supervised Learning Problem
     - Deep Learning for Time Series Forecasting

- **[Time Series Data Visualization](Time_Series_Data_Visualization_Basics.ipynb)**

    - Plotting of Pandas Df
    - Adding title
    - Adding Axis label
    - X limits by slice
    - X limit by argument
    - Color and Style
    - X ticks spacing
    - Date formatting
    - Major and Minor axis values
    - Gridlines

- **[Time Series EDA](Time_Series_Data_EDA.ipynb)**
    
    - Introduction with time series data
    - Time resampling
    - Time downsampling/upsampling
    - Time Shifting
    - forward shift
    - backward shift
    - Rolling window mean
    - Expanding window mean/cumulative mean

- **[Time Series Data Analysis](Time_Series_Data_Analysis.ipynb)**

    - Introduction to statsmodels
    - Hodrick Prescott filter - Trend/cyclical components
    - Time Series Stationarity
    - Augmented Dickey-Fuller Test
    - Granger Causality Tests
    - Time series decomposition
    - Additive/multiplicative models
    - Moving Average
    - Simple Exponentially weighted moving average(EWMA)
    - Double EWMA
    - Holt-Winters Method(Triple EWMA)

- **[Time Series Forecasting Classical Methods](Time_Series_Forecasting_Traditional_Methods.ipynb)**

    - Forecasting with Holts-Winter Method
    - Autocorrelation function(ACF)
    - Partial autocorrelation function(PACF)
    - Autocovariance for 1D
    - Autocorrelation for 1D
    - Autoregressive model(AR(p))
    - Autoregressive Moving Average(ARMA) Model
    - Autoregressive Integrated Moving Average(ARIMA)
    - Error/Trend/Seasonal Decomposition(ETS Decomposition)
    - Seasonal Autoregressive Integrated Moving Averages(SARIMA)
    - Seasonal AutoRegressive Integrated Moving Average with EXogenous Variable.

- **[Time Series Forecasting with Deep Learning](#)**

    - [MLPs for time series forecasting](Time_Series_Forecasting_With_MLPs.ipynb)
    - [LSTMs for time series forecasting](Time_Series_Forecasting_With_LSTMs.ipynb)
    - [CNNs for time series forecasting](Time_Series_Forecasting_With_CNNs.ipynb)
    - Transformers for time series forecasting(under construction)
 
- **[Time Series Forecasting with FBProphet](#)**
    -  [Univariate and Multivariate Time Series Forecasting With FBProphet](Time_Series_Forecasting_With_Prophet.ipynb)

- **[AutoML For Time Series Forecasting](#)**
    -  [Automating Time Series Forecsting with FLAML](Automating_Time_Series_Forecsting_with_FLAML.ipynb)

## About the Maintainer

This project is currently maintained by Sai Santhosh Kambhampati.

Sai Santhosh is a Software Engineer with 4+ years of experience developing scalable, enterprise-grade applications. Proficient in Java, Spring Boot, REST APIs, SQL, and cloud platforms like AWS. Experienced in full-stack development, system design, and CI/CD pipelines. He is recognized for writing clean, maintainable code and delivering high-impact solutions in fast-paced environments.

Feel free to reach out for questions, suggestions, or collaborations.

- Email: saisanthoshkambhampati23@gmail.com