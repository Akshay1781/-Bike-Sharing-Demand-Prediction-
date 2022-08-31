# -Bike-Sharing-Demand-Prediction-

![image](https://user-images.githubusercontent.com/101791277/187671827-f3f82bad-80f3-4300-b105-6fe9b0872bd8.png)


## 1. Business Problem

Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

## 2. Solution Strategy

Step 01: Data Description: Use statistics metrics to identify data distributions.

Step 02: Feature Engineering: Derive new attributes based on the original variables to better describe the phenomenon that will be modeled.

Step 03: Exploratory Data Analysis: Explore the data to find insights and better understand the impact of variables on model learning.

Step 04: Feature Selection: Selection of the most significant attributes for training the model.

Step 05: Machine Learning Modelling: Machine Learning model training.

Step 06: Hyperparameter Fine Tunning: hoose the best values for each of the parameters of the model selected from the previous step.

Step 07: Convert Model Performance to Business Values: Convert the performance of the Machine Learning model into a business result.

## 3. Top 3 Data insights

The demand for rental bikes is highest in the month of June and decreases gradually till December.

Temperature is positively correlated with the people using bikes. The maximum is between 20 °C and 30 °C.

The demand for bike increases throughout the day, maximum at around 6 pm.

## 4. Machine learning models implemented

Linear Regression, Elastic Net Regression, Decision Tree, Random Forest.

## 5. Model performance comparision

![image](https://user-images.githubusercontent.com/101791277/187672547-1eb35c38-04b9-4343-b53f-febd4fea4877.png)

## 6. Conclusion

Random Forest Regressor gives highest R2 Score of 98% for training set and 89% for testing set

Performance on "Decision Tree" algorithm and "Elastic Net regression test " are comparitively less.
