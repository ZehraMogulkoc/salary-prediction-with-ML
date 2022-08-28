# salary-prediction-with-ML

Business Problem:
Can a machine learning project be implemented to estimate the salaries of baseball players whose salary information and career statistics for 1986 are shared?


#############################################
<br/>
Target variable analysis with boxplot method.
<br/>
#############################################
<br/>
<p align = "center">
<img src="https://user-images.githubusercontent.com/87859856/186888006-13296f74-63b7-4d3a-b5b0-317de5d67043.png" alt="feed example" width="400"> 
</p>
Correlation analysis
<p align = "center">
<img src="https://user-images.githubusercontent.com/87859856/186888058-43eee19f-b307-4264-aed7-4f8b7c52e916.png" alt="feed example" width="400">
</p>
<br/>
##############################################
<br/>
HOLD OUT - MODEL VALIDATION - BASE MODELS
<br/>
##############################################
<br/>
          name  RMSE_TRAIN  RMSE_TEST
          <br/>
11    CatBoost       4.970    237.712
9      XGBoost       0.001    256.239
10    LightGBM      51.394    259.164
6           RF      62.387    260.609
8          GBM      30.648    262.679
4          KNN     167.550    268.997
5         CART       0.000    314.222
3   ElasticNet     202.308    328.042
2        Lasso     200.520    332.650
1        Ridge     199.917    333.875
7          SVR     315.167    336.098
0           LR     198.591    336.352
<br/>
##########################
# RANDOM FORESTS MODEL TUNING
##########################
<br/>
RF Tuned Model Train RMSE: 99.69754579820678
<br/>
RF Tuned Model Test RMSE: 155.72263111886258
<br/>

#######################################
<br/>
FEATURE IMPORTANCE
<br/>
#######################################
<br/>
<p align = "center">
<img src="https://user-images.githubusercontent.com/87859856/186888082-fb48bd61-3b80-4e37-aeb9-5a9354af8c2e.png" width="400">
</p>
