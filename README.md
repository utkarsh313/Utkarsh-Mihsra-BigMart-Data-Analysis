# Utkarsh-Mihsra-BigMart-Data-Analysis
The data of BigMart have collected from 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim of this data science project is to build a predictive model and find out the sales of each product at a particular store. Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.
Summary
Compairing all the model
 LinearRegression : LinearRegression Model accuracy: 58.13%
     > Single score 0.5813205293585394
     > Cross score 0.5615012242066324
     > Regressioin metrics on the test set
     > MEAN SQUARED ERROR(MSE) 1137958.0787850397
     > MEAN ABSOLUTE ERROR(MAE) 790.3286988964805
     > ROOT MEAN SQUARED ERROR(RMSE) 1066.7511794158186
     > SCORE 0.5813205293585394
     
     
 Random Forest Regressor : RandomForstRegressor Model accuracy: 50.36%
     > Single score 0.503628724218331
     > Cross score 0.49845328691278307
     > Regressioin metrics on the test set
     > R2 Score : 0.50362872421833
     > Mean_Absolute_Error : 809.4441695398198
     > Mean_Square_Error : 1349122.0443342458
     > ROOT MEAN SQUARED ERROR(RMSE) 1066.7511794158186
     > SCORE 0.5813205293585394
     
     
 XGBoost : XGBoost Model accuracy: 50.36%
     > Single score 0.5186832630696916
     > Cross score 0.5120293402057186
     > XGBoost Regressioin metrics on the test set
     > R2 Score : 0.5186832630696916
     > Mean_Absolute_Error : 791.0571315709446
     > Mean_Square_Error : 1308204.2651987132
     > ROOT MEAN SQUARED ERROR(RMSE) 1066.7511794158186
     > SCORE 0.5813205293585394
We discovered that the Linear Regression model gave us the most incredible score, 58.13%, out of all the tested models we tested. As a result, we conclude that linear regression is our predictive model and complete our investigation.
