# Weather Forecasting Models

This repository contains datasets and models for weather forecasting using historical data. Specifically, it includes weather data for Malmö and Istanbul across different timeframes, and performance metrics of machine learning models such as RNN, GRU and LSTM used for forecasting.

## Datasets

Three CSV files are included in this project, each containing weather data for two cities (Malmö and Istanbul). The data covers various atmospheric conditions such as temperature, humidity, and precipitation.

1. **1-year Malmö Dataset (malmo_one_year.csv)**: This dataset includes weather data from Malmö over the past year.
2. **5-year Malmö Dataset (malmo_weather_five_years.csv)**: This dataset includes weather data from Malmö spanning five years.
3. **5-year Istanbul Dataset (five_years_ist_weather.csv)**: This dataset contains weather data from Istanbul over five years.


## Models and Results

The following machine learning models were implemented to predict weather conditions based on the historical data:

### 1. Recurrent Neural Network (RNN)

- **Train Loss**: 0.0059
- **Validation Loss**: 0.0086
- **Test Loss**: 0.0141

### 2. Long Short-Term Memory (LSTM)

- **Train Loss**: 0.0066
- **Validation Loss**: 0.0097
- **Test Loss**: 0.0105

### 3. LSTM (5 years Malmö data)

- **Train Loss**: 0.0028
- **Validation Loss**: 0.0033
- **Test Loss**: 0.0027

The performance metrics indicate that the LSTM model trained on the 5-year Malmö dataset provided the best results, with the lowest losses on both training and testing datasets.