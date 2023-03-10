# Bike-Sharing-Demand-Prediction---Regression
Seoul Bike Sharing Demand Prediction
![1593765632600](https://user-images.githubusercontent.com/120353105/215309876-daecd4b9-af5d-451f-8f9d-e80b65ff6fbc.jpeg)

AlmaBetter Verfied Project seoul

📋 Problem Statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.

Data Description
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Data Pipeline
● Exploratory Data Analysis (EDA): In this part we have done some EDA on the features to see the trend.

● Data Processing: In this part we went through each attributes and encoded the categorical features.

● Model Creation: Finally in this part we created the various models. These various models are being analysed and we tried to study various models so as to get the best performing model for our project.

💾 Project Files Description
This Project includes 1 colab notebook and 1 Pdf of presentation.

Executable Files:
Bike Sharing Demand Prediction - Includes Exploratory Data Analysis and all algorithms which are used in this project.

Bike Sharing Demand prediction.pdf - Includes pdf of the presentation of the project.

Output:
Google Colab - All the outputs are visible in the provided colab notebook.

📋 Execution Instruction
The order of execution of the colab notebook is as follows:

1) Bike_Sharing_Demand_Prediction_Capstone_Project.ipynb

First, click on the open in colab button present on the top centre of the notebook.

In this .ipynb file, we have -

* EDA on Bike sharing demand prediction.

* Hypothesis.

* Fitting different models and cross validate them.

* Evaluating result by Evaluation metrics.

📘 Algorithms Used
Linear Regression
Lasso, Ridge and Elastic net Regression
Decision tree
Random Forest
Gradient Boosting
XGBRegression
Conclusions
● The result shows the evaluation metrics- R-squared, Adjusted R2 showed highest value and MSE, RMSE showed lowest value for XGBoost model. Gradient Boosting and XGBoost models are found to be the best models. Therefore, either Gradient Boosting or XGBoost model can be used to predict the number of bikes required at each hour. So, finally this model is best for predicting the bike rental count on daily basis.

● For all the models, temperature or hour was ranked as the most influential variable to predict the rental bike demand at each hour.
