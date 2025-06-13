# Toronto-Island-Ferry-Ticket-Counts-Forecast
This project is to forecast Toronto Island ferry ticket counts.

The data part: Toronto Island Ferry Ticket Counts.csv is downloaded from https://open.toronto.ca/dataset/toronto-island-ferry-ticket-counts/.

The code part includes three .ipynb files, and three .py files and one .pkl file.

1) redemption count forecast
   
   a) Modelling.ipynb (an improved model is HW = statsforecast.models.HoltWinters(error_type='A', season_length = 365))
   
   b) model_metric_mae.py
   
   c) model_metric_rmse.py
   
   d) model_metric_mape.py

   e) my_model.pkl
   
   
3) sales count forecast
   
   a) SalesCount_Forecasting.ipynb (chosen model is ExtraTreesRegressor(n_estimators = 121,
max_depth = 16,
min_samples_split = 12,
min_samples_leaf = 9,
max_leaf_nodes = 69,
random_state = 42
))
   
   b) SalesCount_Forecast_Appendix.ipynb

The document part contains two pdf: Brief Description and Technical Description
