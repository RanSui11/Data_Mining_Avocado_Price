# Predict Avocado Price 


This project is aiming to guide the wholesale and retail of avocado and help customer purchase the cheapest fruit at specific time and place by predicting the price of avocado. Data comes from Kaggle(https://www.kaggle.com/neuromusic/avocado-prices).

### Data Description

There are 12 features in the original dataset, which includes the date of observation, the average price of a single avocado, the numbers of avocados with PLU 4046,4225,4770 sold, the numbers of bags with small, large or xlarge avocado, the type of fruit (coventional or organic) and the observed place.


### Code Description

1. Data Visulization 

Before processing, generated picutres to show the relationship between some features and price. 

2. Data preprocessing and Model Building 

- Extracted the information of year,month and day from the observation date. 

- Filled in NaN’s with mean values obtained from the training data.

- Used one hot encoding, converting categorical features into numerical.

- Standardization: de-mean and divided by the standard derivation

- Applied different models (Linear model, KNN, SVR,XGBoost and etc) and compared performance by R squared.

3. Model Optimization 

Implemented Hyperparameter tuning method. Top 3 models with highest R squared after tuning parameters were Random Forests, Bagging regressor and KNN.
R


### Disclaimer

This is the final project of Data Mining course at JHU. 


