**Crash Descriptor**
**Introduction**
This project focuses on building a predictive model for crash descriptors using a dataset containing various attributes of traffic accidents. The goal is to classify the type of crash based on features like weather conditions, lighting, road surface, and municipality, among others.

The dataset includes both numerical and categorical data, which required a careful selection of preprocessing techniques and an appropriate machine learning model. To achieve high accuracy in prediction and handle the complexity of categorical variables, we chose CatBoost, a gradient boosting algorithm that natively supports categorical data and provides excellent performance on tabular datasets.

In addition to classification, this project emphasizes data exploration, cleaning, and transformation to ensure the best results from model training. The project aims to contribute to better understanding and prevention of traffic accidents by providing insights into the factors that contribute to various types of crashes.

**Time Series Analysis**
**Introduction**
This project focuses on time series forecasting, where the objective is to model and predict future trends based on historical data. The dataset contains time-ordered observations, and the goal is to accurately forecast future values, such as traffic accident rates or other temporal patterns, by capturing the underlying trends, seasonality, and autocorrelations present in the data.

For this task, we applied the ARIMA (AutoRegressive Integrated Moving Average) model, a powerful statistical method widely used for univariate time series forecasting. ARIMA effectively handles non-stationary data by differencing, while also leveraging past observations and residual errors to improve the prediction accuracy.

This project explores data preprocessing techniques, model selection (based on auto-correlation and stationarity tests), and model evaluation to ensure optimal performance. By using ARIMA, the project aims to demonstrate how time series forecasting can provide valuable insights for predicting future outcomes and trends, supporting better decision-making and planning.
