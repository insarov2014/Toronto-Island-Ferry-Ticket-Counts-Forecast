# Toronto-Island-Ferry-Ticket-Counts-Forecast
This project is to forecast Toronto Island ferry ticket counts.

The data part: Toronto Island Ferry Ticket Counts.csv is downloaded from https://open.toronto.ca/dataset/toronto-island-ferry-ticket-counts/.

I detected anomalies using Isolation Forest.

I used statistical methods, machine learning methods and the methods from NIXTLA to forecast the sales counts. 
     
The chosen model is sklearn.tree.ExtraTreesRegressor(

n_estimators = 128,

max_depth = 19,

min_samples_split = 13,

min_samples_leaf = 9,

max_leaf_nodes = 72,

random_state = 42

)
