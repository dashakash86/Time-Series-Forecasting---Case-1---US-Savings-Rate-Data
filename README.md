# Time-Series-Forecasting---Case-1---US-Savings-Rate-Data
An analysis on US savings rate data (published by the U.S Dept. of Commerce) to identify the adequate time series model, estimate the parameters, and forecast two years into the future. Tool used: SAS


**How to initiate**: 
<br>
The data is available in the first SAS command, in the SAS Command folder. This can be replicated if the user has SAS installed.


**Summary of the study**:
<br>
Saving rate is defined as personal saving as a percentage of total disposable personal income. Economists believe that shifts in this rate contribute to business fluctuations. When people save more of their income they spend less for goods and services which could reduce gross and net national product.

In this case study we analyze 100 quarterly observations of the U.S. saving rate for the years 1955~1979. The data has been seasonally adjusted prior to publication by the U.S. Department of Commerce, which means we do not need to separately identify any non-stationary property in the time series. The tool used is SAS.

In this study we,
* Identify the right model (AR / MA / ARMA) based on correlations from the data,
* Estimate the parameters (p, q) so that we have the right residual diagnostics and the simplest possible model, and
* Forecast the savings rate for the next two years, conditional on the past observed data.
