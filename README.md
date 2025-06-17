# Citibike_NYC
The aim of the project is to perform demand forecasting at station level for Citibike, operating in New York City. Short term demand prediction (15 minutes – few hours ahead) typically requires more data for capturing rapid demand fluctuations and complex non-linear relationships. On the other hand, long term demand prediction (weekly or monthly patterns) typically require less data for capturing broader trends and simpler linear relationships. This project aims to bridge the gap between short-term and long-term demand prediction so that both immediate operational challenges, as well as planning issues for the purpose of strategy can both be addressed.

In the attempt to capture demand fluctuations effectively, feature engineering is performed that makes use of both spatial and temporal information alongside other information such as weather. Different models based on ensembles of decision trees are benchmarked to recognise the one with the best forecasting performance. Tuning is performed using Random Search, keeping the temporal nature of data in mind.

## Ensembles of decision trees used:
- Random Forest
- Histogram Based Gradient Boosted Trees
- Light GBM (yielded best performance)
- XGBoost

Result: MSE on average, reduced by more than 57% with tuned LGBM.

Note: This repository provides the project report as well as the code used for the analysis. The entire project is performed using Python (Jupyter Notebooks).
