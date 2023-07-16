# Used Device Price Prediction
## Supervised Learning Project
### Context

The used and refurbished device market has grown considerably over the past decade as it provide cost-effective alternatives to both consumers and businesses that are looking to save money when purchasing one. Maximizing the longevity of devices through second-hand trade also reduces their environmental impact and helps in recycling and reducing waste. Here is a sample dataset of normalized used and new pricing data of refurbished / used devices.
 
### Objective

The objective is to do Exploratory Data Analytics and apply Linear Regression to create a model which can help in pricing of such devices.

### Dataset
1. Dataset contains 3454 records with 15 attributes
2. There are 11 numeric (float and int type) and 4 string (object type) columns in the dataset
3. Our target variable is the normalized_used_price, which is of float type

### Model Performance Summary
#### Overview of ML model and its parameters
1.  We split the data in 70:30 ratio for train to test data
2/ We built a linear regression model using statsmodels (OLS)
#### Summary of most important factors used by the ML model for prediction
1. Number of rows in train data = 2417
2. Number of rows in test data = 1037
3. random_state=1

### Summary of key performance metrics for training and test data in tabular format for comparison
1. The training 𝑅 is 0.84, indicating that the model explains approx. 84% of the variation in the train data. So, the model is not underfitting
2. MAE (0.182, 0.186) and RMSE (0.234, 0.241) on the train and test sets are comparable, which shows that the model is not overfitting
3. MAE indicates that our current model is able to predict normalized_used_price within a mean error of 0.186 on the test data
4. MAPE on the test set suggests we can predict within 4.55% of normalized_used_price


