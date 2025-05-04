# Call-Centre-Performance-Analysis-Forecasting-Using-Queueing-Theory-and-ARIMA
Time series forecasting and queueing theory analysis (M/M/1) on a call centre dataset (0000–0300hrs) to evaluate performance metrics, visualise KPIs, and predict 48-hour call volumes using ARIMA.

# 📞 Call Centre Forecasting Using Queueing Theory & ARIMA

This project applies time series forecasting and queueing theory to analyse and predict call centre performance between 12AM–3AM. Using real call log data, we:

- **Model call arrivals** with an M/M/1 queue (Poisson arrivals, exponential service times)
- **Estimate key KPIs**: traffic intensity, average wait time, system time, queue length
- **Forecast future call volumes** using ARIMA for a 48-hour window
- **Visualise insights** to guide staffing and operational decisions

## 📊 Dataset
Hourly call data (0000–0300) over several days. Preprocessed for trend and stationarity.

## 🔧 Tools & Methods
- Python (pandas, numpy, statsmodels, matplotlib)
- ARIMA modelling (stationarity, differencing, AIC selection)
- Queueing theory formulas (Little’s Law, Kendall notation)

## 📈 Key Results
- Forecasts aligned closely with actual call volumes (low RMSE)
- Identified optimal utilisation range to prevent overload
- Visuals highlight patterns and bottlenecks during peak hours

## 🚀 Future Work
- Extend analysis to full-day data
- Test multi-server models (e.g., M/M/c)
- Automate staffing recommendations based on forecasts

## 📁 Structure
