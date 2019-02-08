# S&P 500 Volatility Forecasting
The project mainly use ARMAX Model to forecast the realized volatilty of S&P 500.
The project improves the normal GARCH model in 2 ways:
1. The volatility dataset is no longer latent data, as the realized volatility converting interday price movement into normal financial time series.
2. The leverage effect, negative relations between price movement directions and price volatility , is included into the model. 
