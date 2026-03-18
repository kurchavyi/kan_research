# kan_research
KAN Research: Financial Time Series Forecasting

In this project, I investigated whether Kolmogorov-Arnold Networks (KAN) can be used for time series forecasting of client financial behavior and how they compare to traditional models like XGBoost and LSTM. My main goal was to evaluate whether KAN could deliver competitive predictive accuracy while offering better interpretability.

I used daily client transaction data and applied standard time series feature engineering techniques, including lag features, calendar variables, and seasonality indicators. After training and evaluating the models, XGBoost performed the best overall. LSTM came in slightly behind it, while KAN showed lower predictive accuracy, with error rates roughly 2–5 times higher. However, KAN stood out in terms of interpretability.

One of the key advantages of KAN is that it produces transparent, formula-based representations that capture seasonality, weekday effects, and behavioral patterns. This makes the model easier to understand and explain compared to more complex black-box approaches.

In conclusion, KAN shows strong potential for explainable time series forecasting in financial applications, but it still requires further optimization to reach the predictive performance of more established methods.