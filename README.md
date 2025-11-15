# Cosmetic Product Demand Forecast for Tehran Neighborhoods

This project analyzes cosmetic product request trends in Tehran neighborhoods and forecasts high demand areas using **Prophet** and **clustering**.

## 1. Spatial Analysis
Neighborhoods are analyzed using:

- Mean daily requests
- Growth rate
- Volatility

Neighborhoods are then **clustered on a map** to reveal spatial demand patterns.

## 2. Forecasting
Top five high demand neighborhoods are forecasted for 6 months.  
Metrics include **trend, seasonality, prediction intervals**, evaluated by **MAE, MAPE, RMSE, coverage**.

## Tech & Tools
Python, Pandas/NumPy, GeoPandas, Matplotlib/Seaborn, Scikit-learn, Prophet, Folium

## Maps
Interactive maps are saved in `results/`.  
[View clustering map](https://arezoozarea.github.io/TehranCosmeticDemandForecast/tehran_neighborhoods.html)

## Author
**Arezoo** — Data Analyst & GIS Specialist