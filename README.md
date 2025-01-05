# House Price Prediction using Machine Learning in Python 🏠 

This project uses machine learning to predict house prices based on a variety of features. 

## Description 

This project aims to build a model that can accurately predict the sale price of a house based on features such as:

*  Size of the property
*  Location
*  Age of the house
*  Number of rooms
*  And more!

The model was trained using a dataset of house prices and corresponding features. Several regression models were evaluated to find the most accurate predictor.

## Dataset 

The dataset used for this project can be found [here](link to your dataset). It contains 13 features, including:

* `Id`
* `MSSubClass`
* `MSZoning`
* `LotArea` 
* `LotConfig`
* `BldgType`
* `OverallCond`
* `YearBuilt`
* `YearRemodAdd`
* `Exterior1st`
* `BsmtFinSF2`
* `TotalBsmtSF`
* `SalePrice`

## Technologies Used 

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn (for machine learning models)

## Models Evaluated 

* SVM (Support Vector Machine)
* Random Forest Regressor
* Linear Regressor
* CatBoost Regressor

## Results 

The models were evaluated using Mean Absolute Percentage Error (MAPE).  Here's a summary of the results:

| Model                     | MAPE     |
|--------------------------|----------|
| SVM                       | 0.187    | 
| Random Forest Regressor  | 0.193    |
| Linear Regression         | 0.187    |
| CatBoost Regressor        | 0.383 | 

As you can see, Catboost with the highest MAPE scores. 

*It's important to note that these results may vary slightly depending on the specific training and testing splits of the data.*


