# Bigmart-sales-prediction Analysis

Bigmart Sales Prediction is a regression problem where we have to analyze and predict the sales of Bigmart based on various aspects of the dataset. The objective is to build a predictive model and discover the sales of each product at their respective store.

Dataset Information
The data scientists at BigMart have collected 2013 sales data for 1559 products across 10 stores in different cities. Also, certain attributes of each product and store have been defined. The aim is to build a predictive model and find out the sales of each product at a particular store.

Using this model, BigMart will try to understand the properties of products and stores which play a key role in increasing sales.

Variable	Description
Item_Identifier	Unique product ID
Item_Weight	Weight of product
Item_Fat_Content	Whether the product is low fat or not
Item_Visibility	The % of total display area of all products in a store allocated to the particular product
Item_Type	The category to which the product belongs
Item_MRP	Maximum Retail Price (list price) of the product
Outlet_Identifier	Unique store ID
Outlet_Establishment_Year	The year in which store was established
Outlet_Size	The size of the store in terms of ground area covered
Outlet_Location_Type	The type of city in which the store is located
Outlet_Type	Whether the outlet is just a grocery store or some sort of supermarket
Item_Outlet_Sales	Sales of the product in the particulat store. This is the outcome variable to be predicted.

Dataset link : https://www.kaggle.com/datasets/aakash2016/big-mart-sales-dataset

#Libraries:
pandas
matplotlib
seaborn
scikit-learn

#Algorithms:
Linear Regression
Ridge
Lasso
Decision Tree
Random Forest
Extra Tress

Mean Squared Error: 0.28

Note: The Error metric is in log values. To convert to original values, use exponentiation.

#Final Thoughts:

Out of the 6 models, linear regression is the top performer with the least cv score.

You can also use hyperparameter tuning to improve the model performance.

You can further try other models like XGBoost, CatBoost etc.


In this project tutorial, we have explored the Bigmart Sales dataset. We learned the uses of one hot encoding in the dataset. We also compared different models to train the data starting from basic to advanced models.

