# Forecating_Danish_GDP_Growth 

## Overview
This repository contains the code and analysis for forecasting Danish GDP growth, focusing on the period from 1973 to 2019. The project applies various econometric models, including LASSO regression, static, and dynamic models, to evaluate and forecast real GDP growth in Denmark using key economic variables.

## Authors
Mariano De Martino, Mariasole Olivetta, Francesco Palluda.

This project was conducted as part of our Econometrics course at Bocconi Univerisity.

## Methodology 
Data preprocessing: Handling missing data and ensuring stationarity of the GDP growth variable.

Model Selection:

LASSO Regression: Starting with seven regressors, including central bank policy rate, CPI, industrial production index, net exports, unemployment rate, population, and international liquidity. LASSO helped shrink the less significant variables, eventually removing net exports.

Static Model: Reduced the number of regressors to CPI, unemployment, population, and economic activity based on model selection criteria.

Dynamic Model: An ARDL (Auto Regressive Distributed Lag) model with lags selected using the Akaike Information Criterion (AIC).
Model Evaluation: We used R-squared, Adjusted R-squared, AIC, and various forecast accuracy measures (such as Root Mean Squared Error) to compare model performance.

## Results

LASSO Regression: Simplified the model by removing non-contributing variables, leading to more efficient forecasting.

Static Model: Provided a higher Adjusted R-squared and lower AIC, making it a better model for the given data.

Dynamic Model: Chosen based on the AIC minimization approach, with 1 lag of unemployment rate and AR(1) selected as the optimal structure.

## Forecast Performance
Our models performed reasonably well on the evaluation sample (2010-2019), with varying forecast errors.

The LASSO model outperformed the static and dynamic models in terms of forecast accuracy, as evidenced by lower Mean Absolute Percent Error (MAPE).

## Acknowledgments
The data used in this analysis was sourced from the IMF, World Bank, and Macrotrend.
## Contacts 
For further inquiries, feel free to contact Mariano De Martino at mariano.demartino@studbocconi.it.
