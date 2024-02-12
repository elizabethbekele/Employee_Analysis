# Employee_Analysis
Create linear regression models to see if the hourly wage can be explained by certain predictors listed in the data set.

Five linear regression models will be adjusted to increase $R^2$.
- Model 1: Includes all predictors except those calculated from other predictors. For instance, the predictor 'exper' is included but 'expersq' is removed.

Perform residual analysis by checking the normality, zero mean & constant variance, and independece. Removed outliers after plotting cooks distance and looking at data below the 3rd quartile. Conduct the linear regression model again.

- Model 2: Linear regression model with significant predictors mentioned after performing residual analysis.

Perform Box Cox Transoformation 

- Model 3: Linear regression model with the response 'wage' adjusted based on findings from the Box Cox Transformation

Reduce the model by utilizing the 'step( )' function 

- Model 4: Linear regression model using predictors in the reduced model

- Model 5: Include an interaction term



