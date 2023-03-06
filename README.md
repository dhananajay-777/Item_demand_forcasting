# Item_demand_forcasting

Problem Statement
Demand forecasts are fundamental to plan and deliver products
and services. Accurate forecasting of demand can help the
manufacturers to maintain appropriate stock which results in
reduction in loss due to product not being sold and also
reduces the opportunity cost (i.e. higher demand but less
availability => opportunity lost). Despite such relevance,
manufacturers have difficulty choosing which forecast model is
the best for their use case. In this project, historical sales data
corresponding to multiple(25) items sold in 10 stores are
provided and participants are expected to come up with a best
model to predict the future demand for products which results in
maximum profit for the manufacturer. Predict the demand for
the next 3 months at the item level (i.e. all the stores
combined).

The dataset is attached in the same file.

While running the Ipynb file and csv file must be in the same folder. 

while running the files make sure all necessary packages are installed.

For this problem i have used 2 approaches

The first method is using all items sold between 2013 till 2016 as theTRain Dataset and items sold in 2017 as Test dataset.
In this method i got an R score of 0.96 in XGBoost

In the second method i used the normal train and test split 
