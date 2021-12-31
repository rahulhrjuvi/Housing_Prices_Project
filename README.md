# Housing Prices ML Project

## Business:

EdLoan is a financial services company in Ames, Iowa. They specialize in providing education loans to students in the community. The loans are usually collateralized by assets such as residentials properties. They have a data science team which is asked to come up with the prices of houses in Ames, Iowa in order to validate loan amounts requested. The qualitative and quantitative features of the houses are collated, analyzed and modelled in order to predict the house prices.

## Predictive Models:

Five regressors are modeled on the train.csv dataset
- Linear Regressor
- Decision Tree Regressor
- Lasso Regressor
- Random Forest Regressor
- XGBoost Regressor

Best Performing Model: **XGBOOST REGRESSOR** with a test R-Squared of 0.933

## Results
<img width="503" alt="ML_Project_results_graph" src="https://user-images.githubusercontent.com/89796629/147840775-bb8cd253-d488-4efa-9e54-b310062775c8.png">

The XGBoost regressor is used to predict house prices for the houses data present in test.csv and the results are stored in submission.csv

