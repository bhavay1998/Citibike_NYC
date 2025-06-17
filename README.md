# Citibike_NYC
The aim of the project is to perform demand forecasting at station level for Citibike, operating in New York City. Short term demand prediction (15 minutes – few hours ahead) typically requires more data for capturing rapid demand fluctuations and complex non-linear relationships. On the other hand, long term demand prediction (weekly or monthly patterns) typically require less data for capturing broader trends and simpler linear relationships. This project aims to bridge the gap between short-term and long-term demand prediction so that both immediate operational challenges, as well as planning issues for the purpose of strategy can both be addressed.

For the purpose of model development, ensembles of decision trees along with ensemble methods such as bagging and random forests are used.

Result: GWR has superior prediction performance compared to pruned decision trees, but has remarkably similar performance to ensemble methods such as bagging and random forest. Coefficients determined by GWR model are more interpretable since the relationships captured are not over-generalised. This is because they are captured at a local level.

Note: This repository provides the project report as well as the code used for the analysis. The entire project is performed using Python (Jupyter Notebooks).
