Flood Prediction for Lagos
By Oluwatomisin Bakare

Overview
This project uses historical weather data to predict potential flood days in Lagos, Nigeria. The ARIMA model was applied to forecast precipitation over the next 30 days, focusing on identifying any days with rainfall exceeding 50 mm, a threshold indicative of flooding.

Dataset
The dataset consists of 8,676 entries, covering various weather parameters like temperature, humidity, precipitation, wind, and cloud cover.

Data Preparation
Parsed inconsistent date formats.
Filled missing precipitation values with column mean.
Set datetime as the index with daily frequency.
Model
Used ARIMA model (5, 1, 0) for time series forecasting of precipitation.
Results
No predicted flood days in the next 30 days (threshold: 50 mm).
Top 5 days with the highest predicted precipitation are listed below.
Conclusion
No major flooding is expected based on the current forecast. Continuous monitoring is recommended for long-term predictions.

[Link to notebook]
