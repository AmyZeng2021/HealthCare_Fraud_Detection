# Health Care Fraud Detection
## Problem Statement :

Health care fraud is a crime that involves misrepresenting information,  concealing information, or deceiving a person or entity in order to  receive benefits, or to make a financial profit. Both individuals and  healthcare providers commit health care fraud, in a number of different  ways.

## Goal : 

The Goal in this project is to **understand the behavior of potential fraud providers**, and **discover** the **important parameters** that can help us to to that, and finnally to **build a predictive model** that can  **flag the potential fraud providers** based on the **claims fields**

## Data Source : 

The data was downloaded from: https://www.kaggle.com/rohitrox/healthcare-provider-fraud-detection-analysis

## Exploratory Data Analysis

All other parameters and their relationships with the fraud providers were examined in detail to determine which data, as well as the extended statistics derived from them, would be used in the final model.

## Modelling strategy

A large range of commonly used machine learning models were employed, including: Linear Regression, Logistic Regression, Ridge Regression, Lasso Regression, Elastic Net, Random Forest, Gradient Boosting Machine (GBM), AdaBoost, XGBoost, LightGBM, CatBoost, k-Nearest Neighbors (k-NN), Feedforward Neural Networks (FNN / MLP) etc.

### Table of Contents

The analyses are presented in four notebooks:
- *[Exploratory Data Analysis (Part I)](https://github.com/AmyZeng2021/HealthCare_Fraud_Detection/blob/main/HFD_EDA-Part_1.ipynb)*
- *[Exploratory Data Analysis (Part II)](https://github.com/AmyZeng2021/HealthCare_Fraud_Detection/blob/main/HFD_EDA-Part_2.ipynb)*
- *[Exploratory Data Analysis (Part III)](https://github.com/AmyZeng2021/HealthCare_Fraud_Detection/blob/main/HFD_EDA-Part_3.ipynb)*
- *[Feature Engineering and Modelling](https://github.com/AmyZeng2021/HealthCare_Fraud_Detection/blob/main/HFD_Modeling_with_Test_Data.ipynb)*
  
## Model Evaluation 

```
                      Accuracy --     F1      --  Precision --  Recall
XGBoost:             1.000000  --  1.000000   --  1.000000  --  1.000000
Cat Boost:           0.999991  --  0.999988   --  1.000000  --  0.999976
Blended Model:       0.999991  --  0.999988   --  1.000000  --  0.999976
Random Forest:       0.999946  --  0.999929   --  1.000000  --  0.999859
GBM:                 0.999937  --  0.999918   --  0.999953  --  0.999882, 
Neural Network:      0.999364  --  0.999163   --  0.999670  --  0.998657
LightGBM:            0.998647  --  0.998218   --  1.000000  --  0.996442
KNN:                 0.969788  --  0.959888   --  0.968956  --  0.950987
Lasso:               0.952429  --  0.936016   --  0.957601  --  0.915382
Ridge:               0.951730  --  0.935039   --  0.957181  --  0.913898
Logistic Regression: 0.947637  --  0.929239   --  0.955374  --  0.904496
ElasticNet:          0.946239  --  0.927066   --  0.957096  --  0.898864
ADA:                 0.924948  --  0.897513   --  0.933111  --  0.864532
```

## Conclusion

By improving this model, It will help in predicting Provider fraud, to help Insurance companies and Government to take decision against fraudulent health provider and also to improve health of economy.


