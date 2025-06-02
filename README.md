# Used Car Price EDA and Prediction Model
----------

In this project, we will perform the Exploratory Data Analysis(EDA) to understand *what factors drives the used car price* and build predictive model to understand the weight of each variable. 

Finally we will provide the summary of our EDA findings and provide recommendations to Used Car Dealer business client team regarding what consumers value in a used car

**Note :** This is a UC Berkeley Haas AI/ML Certification Course Assignment

## Approach
----------

In order to achieve objective, I will follow below **CRISP-DM** framework steps

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Exploratory Data Analysis(EDA) 
5. Modeling
6. Evaluation
7. Results
8. Conclusion


## Business Problem Statement
--------

Used cars market is a large market and the car prices are often depends on multiple factors.

Goal is to understand what factors make a car more or less expensive. As a result of this analysis, we should provide clear recommendations to your client(a used car dealership) as to what consumers value in a used car?

## Objective
--------
Objectives of these projects are
- Peform thorough Exploratory Data Analysis(EDA) and summarize the business insights to `used car dealership business team`
- Apply multiple predictive ML models and choose the best performing predictive model
- Provide recommendations to client regarding what features consumers values most

## Data Set
--------
The original dataset contained information on *3 million* used cars. The provided dataset contains information on *426K* cars to ensure the speed of processing

- Number of input samples : 426,880
- Number of features : 17
- Target or dependent variable : price

Original Dataset : [Kaggle Used Car Dataset](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data)


## Exploratory Data Analysis(EDA)
--------

Please refer EDA section of [prediction_model_notebook](./notebooks/Used_car_price_EDA_and_prediction_model.ipynb)


## Results
--------
Across Liniear Regression/Decision Tree/Gradient Boosting/Random Forest models, Radom Forest beats remaining all the models

For mode details on modeling results, please refer [prediction_model_notebook](./notebooks/Used_car_price_EDA_and_prediction_model.ipynb)

## Conclusion
--------
Below are the features, consumer values most
- Car's model year : Values latest year
- Odometer : The lesser odometer, pays more
- Car manufacturer : Type of manufacturer matters
- Car condition : new condition is valued more
- car title : Values clear title

Also as provided in results section of [prediction_model_notebook](./notebooks/Used_car_price_EDA_and_prediction_model.ipynb)  used car price can be calculated using predictive model
