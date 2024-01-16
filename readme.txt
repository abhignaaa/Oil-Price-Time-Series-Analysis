# Project2_SDM2 - Daily Oil Price Time Series Analysis

## Authors
- Abhigna Tanguturi
- Mahendra Reddy Gopu
- Mantri Pragada Venkata Sesha Aditya
- Subbarao Koduri

## Date
May 6, 2023

## Overview
This project involves the analysis of daily oil prices through time series techniques using R. The main objectives include loading the dataset, handling missing data through interpolation, and applying various time series forecasting models such as ETS and Holt-Winters.

- `oil_data.csv`: Dataset containing daily oil prices.


## Instructions
1. **Install Required Libraries**: Ensure that you have the necessary R libraries installed by running the code in the R Markdown file.

2. **Load the Dataset**: The dataset (`oil_data.csv`) is loaded and explored to understand its structure.

3. **Handling Missing Data**: Missing values in the daily oil prices are filled using the `imputeTS` library, specifically the `na_interpolation` function.

4. **Time Series Plotting**: The original time series plot is generated to visualize the daily oil prices. A subsequent plot with imputed data is also provided.

5. **Time Series Decomposition**: The time series is decomposed to explore trends, seasonality, cyclicality, and residuals.

6. **ETS Models and Holt-Winters Models**: Different ETS (Error, Trend, Seasonality) models and Holt-Winters models are applied for time series forecasting.

7. **Forecasting Evaluation**: The accuracy of the forecasting models is assessed using the `accuracy` function, and plots of the forecasts are generated.

8. **Summary and Insights**: The project concludes with a summary of the analysis and insights derived from the time series data.

## Usage
1. Open the `oilpricets.Rmd` file in RStudio.
2. Run each code chunk sequentially to perform the analysis.


