# Supply Chain --- Predictive-Planning---Demand-Forecasting

The project aims to build the fundamental framework for an ensemble predictive analysis in demand forecasting (or any other numeric target values).

1.	Data wrangling : This step was skipped since each unstructured dataset requires various methods to transform into a cleaned one.
2.	Exploratory analysis : visualize the distribution of key variables
3.	Feature selection / engineering : create the coefficient matrix to evaluate the relationship of each variable. If necessary, reduce the skewness of certain variables, as well as creating additional variables using existing data
4.	Develop pipelines : develop pipelines for regression models, in this case, I build lasso, elastics net, gradient boosting and RGBoost regression. 
5.	Hybrid models : combine all models to reduce the risk of overfitting, I averaged the contribution of each single regression to the final ensemble model. However, users are encouraged to assign weight to each regression so that the ensemble model deliver the optimal performance
