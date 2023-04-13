# forecasting-with-prophet

Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data. Prophet is robust to missing data and shifts in the trend, and typically handles outliers well.
Prophet is open source software released by Facebook’s Core Data Science team.

Source: https://facebook.github.io/prophet/ \
Official Blog: https://research.facebook.com/blog/2017/2/prophet-forecasting-at-scale/ 

Here, I am working with the hourly power consumption data from PJM. PJM Interconnection LLC (PJM) is a regional transmission organization (RTO) in the United States. It is part of the Eastern Interconnection grid operating an electric transmission system serving all or parts of Delaware, Illinois, Indiana, Kentucky, Maryland, Michigan, New Jersey, North Carolina, Ohio, Pennsylvania, Tennessee, Virginia, West Virginia, and the District of Columbia. The hourly power consumption data comes from PJM's website and are in megawatts (MW).

Reference: https://otexts.com/fpp3/prophet.html

Quick thought: Although Prophet doesn't neccessarily perform better than our traditional models, it could be seen a baseline to compare other model performance. Since it is an automated model, one doesn't have to go through a ton of effort to generate forecasts with it which makes is an easy choice to use for generating a baseline metric. 
