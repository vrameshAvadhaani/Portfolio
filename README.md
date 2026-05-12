# SARIMAX Forecasting for Transportation CPI
I built a time-series forecasting project to predict CPIETRANS using a SARIMAX model with three exogenous variables: consumer confidence, average car loan rate, and crude oil price.<br/>

The goal was to move beyond a simple univariate forecast and test whether macroeconomic indicators could improve transportation cost forecasting. This made the project more realistic for business use, especially for supply chain and budgeting decisions. <br/>

<img width="100%" height="auto" alt="image" src="https://github.com/user-attachments/assets/ca64375d-67d0-4ceb-9f90-6cc4e90dc589" />

## Project Highlights
<li>Cleaned and aligned multiple monthly economic time series.
<li>Built a SARIMAX model for CPIETRANS with exogenous regressors.
<li>Evaluated the model using AIC, MAE, RMSE, and MAPE.
<li>Visualized both the forecast output and the exogenous variables.
<li>Compared model performance against a prior baseline to show improvement.

## Why this matters
Transportation costs affect freight planning, procurement, and margin management. By forecasting CPIETRANS with external drivers, this project provides a more business-relevant view of future cost pressure than a standalone time-series model.

## Key result
The final model produced a strong forecast baseline with an average error of about 1.8% MAPE in the earlier version of the analysis, and it showed that macro variables can add useful signal to transportation inflation forecasting.

## What I learned
This project helped me practice:

<li>Time-series preprocessing and alignment.
<li>Feature engineering with exogenous variables.
<li>SARIMAX modeling and forecast evaluation.
<li>Translating technical results into business recommendations.

## Business takeaways 
<li>The forecast can help supply chain teams:
<li>Set freight budgets more conservatively.
<li>Time carrier negotiations better
<li>Plan for transportation cost volatility.
<li>Build scenario-based planning around fuel and demand changes.

### Tech Stack & [Working Code](Resources/CPIETRANSvsExogenous.ipynb)
Python: Pandas, NumPy, Statsmodels, Matplotlib

### [Data Used](Data)
CPIETRANS.csv, POILWTIUSDM-CrudeOilPrice.csv, USACSCICP02STSAM-ConsumerConfidence.csv, RIELPCFANNM-AvgCarLoanPrice.csv
