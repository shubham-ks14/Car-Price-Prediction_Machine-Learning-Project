## 1. Problem Statement
### 1.1 Context
This dataset contains information about used cars listed on www.cardekho.com.

### 1.2 Content
So the dataset will be used to build a predictive model to predict the price of a used car based on its input features.

The features(columns) in the given dataset are as follows:

* Car_Name
* Year
* Selling_Price
* Present_Price
* Kms_Driven
* Fuel_Type
* Seller_Type
* Transmission
* Owner

## 2. Machine Learning problem
### 2.1 Data Overview
For this project:

The dataset has 301 records about the used cars sold.
Each record is for the transaction of one car.

Target Variable
'Selling_Price' - Price at which the car is being sold

Features of the data:
- 'Car_Name' - Name of the cars
- 'Year' - Year of the car when it was bought
- 'Present_Price - Price when car was purchased for first time
- 'Kms_Driven' - Number of Kilometres the car is driven
- 'Fuel_Type' - Fuel type of car (petrol / diesel / CNG / LPG / electric)
- 'Seller_Type' - Tells if a Seller is Individual or a Dealer
- 'Transmission' - Gear transmission of the car (Automatic/Manual)
- 'Owner' - Number of previous owners of the car.

### 2.2 Mapping ML problem
This is a regression problem, where given the above set of features, we need to predict the selling price of the used car. Following machine learning algorithms were used:

- 1) LinearRegression
- 2) Ridge Regression
- 3) Lasso Regression
- 4) RandomForestRegressor
- 5) XGBoostRegressor
- 6) DecisionTreeRegressor
- 7) KNeighborsRegressor
- 8) Support Vector Regressor
- 9) ExtraTreeRegressor

Finally create a stable and best performing model using voting method

### 2.3 Performance Metric (KPI)

Since it is a regression problem, we will use the following regression metrics:
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
