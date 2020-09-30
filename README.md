Air-passengers-time-series-forecasting

Forecasting is a method or a technique for estimating future aspects of a business or the operation. 
It is a method for translating past data or experience into estimates of the future. Forecasting done over time is time series forecasting.

The dataset:
    The available dataset is of the number of air passengers from 1949 to 1960 for every month.

Steps:
      Reading time series data,
      Plotting time series,
      Decomposing Time series,
      Forecast,
      ARIMA Models.
      
Methods and Tools:
      Python,
      Excel,
      ARIMA,
      Augmented Dickey-Fuller Test,
      ACF and PACF,
      Statsmodels.
      
Trend:
  Long-run increase or decrease over time (overall upward or downward movement) Trend can be linear or nonlinear such as exponential growth
  
Seasonality:
    A seasonal pattern exists when a series is influenced by seasonal factors (e.g., the quarter of the year, the month, or day of the week). 
    Seasonality is always of a fixed and known period.
    
Stationary Series:
    1.The mean of the series should not be a function of time rather should be a constant.
    2.The variance of the series should not a be a function of time. 
    3. The covariance should not be a function of time.
    
Autoregressive Integrated Moving Average Model(ARIMA):
      An ARIMA model is a class of statistical models for analyzing and forecasting time series data.
      
      AR: Autoregression. A model that uses the dependent relationship between an observation and some number of lagged observations.
      I: Integrated. The use of differencing of raw observations (e.g. subtracting an observation from an observation at the previous time step) in order to make the time series stationary.
      MA: Moving Average. A model that uses the dependency between an observation and a residual error from a moving average model applied to lagged observations.
