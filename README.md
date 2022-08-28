# salary-prediction-with-ML

Business Problem:
Can a machine learning project be implemented to estimate the salaries of baseball players whose salary information and career statistics for 1986 are shared?


<br/>
Target variable analysis with boxplot method.
<br/>
<br/>
<p align = "center">
<img src="https://user-images.githubusercontent.com/87859856/186888006-13296f74-63b7-4d3a-b5b0-317de5d67043.png" alt="feed example" width="400"> 
</p>
Correlation analysis
<p align = "center">
<img src="https://user-images.githubusercontent.com/87859856/186888058-43eee19f-b307-4264-aed7-4f8b7c52e916.png" alt="feed example" width="400">
</p>
<br/>

<br/>
HOLD OUT - MODEL VALIDATION - BASE MODELS
<br/>
| name          | RMSE_TRAIN    | RMSE_TEST  |
| ------------- |:-------------:| -----:     |
| CatBoost   |4.970   | 237.712   |
| XGBoost    |0.001   | 256.239   |
| LightGBM   |51.394  | 259.164   |
| RF   |62.387  | 260.609   |
| GBM   | 30.648  | 262.679  |
| KNN   |  167.550  | 268.997 |
| CART       |0.000    |314.222|
 | ElasticNet     |202.308    |328.042|
 |    Lasso     |200.520    332.650|
|   Ridge    | 199.917    |333.875|
  |   SVR     |315.167   | 336.098|
|   LR     |198.591   | 336.352|
<br/>
              
RANDOM FORESTS MODEL TUNING

<br/>
RF Tuned Model Train RMSE: 99.69754579820678
<br/>
RF Tuned Model Test RMSE: 155.72263111886258
<br/

FEATURE IMPORTANCE
<br/>
<p align = "center">
<img src="https://user-images.githubusercontent.com/87859856/186888082-fb48bd61-3b80-4e37-aeb9-5a9354af8c2e.png" width="400">
</p>
