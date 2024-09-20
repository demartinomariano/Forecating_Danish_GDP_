# Forecating_Danish_GDP_Growth 

## Authors
Mariano De Martino,
Mariasole Olivetta,
Francesco Palluda.

This project was conducted as part of our Econometrics course at Bocconi Univerisity.

We began with an exploratory data analysis and constructed several models to forecast GDP growth. Our process included:

## Methodology 
Data preprocessing: Handling missing data and ensuring stationarity of the GDP growth variable.
Model Selection:
LASSO Regression: Starting with seven regressors, including central bank policy rate, CPI, industrial production index, net exports, unemployment rate, population, and international liquidity. LASSO helped shrink the less significant variables, eventually removing net exports.
Static Model: Reduced the number of regressors to CPI, unemployment, population, and economic activity based on model selection criteria.
Dynamic Model: An ARDL (Auto Regressive Distributed Lag) model with lags selected using the Akaike Information Criterion (AIC).
Model Evaluation: We used R-squared, Adjusted R-squared, AIC, and various forecast accuracy measures (such as Root Mean Squared Error) to compare model performance.
