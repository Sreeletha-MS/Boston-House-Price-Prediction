# Boston-House-Price-Prediction
## Introduction
The Boston housing prediction project aims to build machine learning models to accurately estimate house prices in the Boston area, utilizing the Boston Housing dataset and various regression techniques.Each record in the database describes a Boston suburb or town. The data was drawn from the Boston Standard Metropolitan Statistical Area (SMSA) in 1970. 
## Data Collection and Preprocessing
The dataset for the project is collected online.Pre processing involves null or missing value checks, data statistics, splitting target and independent variables and standardization.
## Model Training
For choosing the best model, try out each regression models one by one. Which include  LinearRegression(), KNeighborsRegressor(), SVR(), DecisionTreeRegressor() and RandomForestRegressor(). Evaluate their performance with R2_score and select the best fitted model for training.
## Model Evaluation
Make the predictions with the trained model,compare with actual values and visualize the difference. Compute R2 score,Mean Absolute Error,Mean Squared Error for evaluating the model.
## Result
As per the evaluation of multiple regression models RandomForestRegressor() seem to be best fitted model and achieved 87% of accuracy on prediction.
