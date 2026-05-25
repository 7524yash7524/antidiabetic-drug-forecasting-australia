## Forecasting Antidiabetic Drug Prescriptions in Australia

This project applies a SARIMA model to forecast the monthly number 
of antidiabetic drug prescriptions in Australia from 1991 to 2008.

### Steps covered:
- EDA and STL decomposition
- Stationarity testing (ADF test)
- Grid search for optimal SARIMA parameters using AIC
- Residual analysis (Ljung-Box test)
- Rolling forecast evaluation using MAPE

### Result:
SARIMA(2,1,3)(1,1,3,12) achieved a MAPE of 7.90% vs 12.69% for the naive seasonal baseline.

### Libraries used:
statsmodels, pandas, numpy, matplotlib, sklearn
