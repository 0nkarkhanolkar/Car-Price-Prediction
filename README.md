# Car-Price-Prediction
As someone who has always been a "car guy," it would only have been fitting that my first ML project was related to what I most love - cars! 
Thus, I took it upon myself to look at a Car Prices dataset and predict the prices of new cars from a car enthusiast's perspective. 
It would also be an excellent way to understand better the features and characteristics that most affect a car's prices. 
I must say, though, the source of my motivation was to predict the price of the "2024 Dodge Charger Daytona SRT Concept" once deployed.


For my readers, assume you are a Data scientist who is required to predict the price of cars with the available independent variables.
The business objective, and your task, is to help the management understand how the prices vary with the independent variables.
Our analysis will allow them to manipulate the design of the cars, the business strategy, etc., to meet the required price levels.


Our aim is to understand the factors affecting the pricing of cars & essentially, to answer these questions:
1. 	Which variables are significant in predicting the price of a car?
2.	How well do those variables describe the price of a car?


My approach is divided into the following sections:
1.	Data cleaning - drop unnecessary columns, fill in missing values, rename columns, make our data more "sensible"
2.	Exploratory data analysis - look at the organized data, map the relationship between price and other variables to draw insights
3.	Outlier detection & removal - identify extreme outliers and remove them
4.	Data visualization - display visually appealing plots and histograms
5.	Data preprocessing - implement feature engineering, train test splitting, encoding, scaling
6.	Model building & evaluation - build multiple models (linear regression, decision trees, etc.)


My conclusion was this:

Mean Squared Error (MSE) showed that K-Nearest Regressor is performing well. But we will use Mean Absolute Error (MAE) as a metric for our deployment 
as it is more easily interpretable. Also, I'd like to point out that MSE is more sensitive to outliers than MAE. Although we have removed outliers, 
using MAE would make our analysis more reliable if we encounter any new outliers. Thus, we would use the Decision Tree Regressor for deploying
our Machine Learning model in real-time to accurately predict the future prices of various cars based on their features.
