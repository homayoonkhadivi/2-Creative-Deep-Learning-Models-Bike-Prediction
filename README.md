# 2-Creative-Deep-Learning-Models-Bike-Prediction
I am supper excited to share with you guys the results of new insights for the data preparation and building two models such as: Regression using SKLearn's Neural Network (NN) Train unisng Keras API with Tensorflow as Backend

# Kaggle Bike Sharing Demand Dataset
Modified 'count' to log1p(count) for training

Log can be used when target represents a count (that is non-negative values)

Model now predicts as log1p(count). We need to convert it back to actual count using expm1(predicted_target)

Input Features: ['season', 'holiday', 'workingday', 'weather', 'temp', 'atemp', 'humidity', 'windspeed', 'year', 'month', 'day', 'dayofweek','hour'] Target Feature: [log1p('count')]

Objective: We are provided hourly rental data spanning two years. For this competition, the training set is comprised of the first 19 days of each month, while the test set is the 20th to the end of the month. You must predict the total count of bikes rented during each hour covered by the test set, using only information available prior to the rental period (Ref: Kaggle.com)

### In this Notebook, we will go through some steps and different insights such as:
# Contains
**Regression using SKLearn's Neural Network (NN)**

**Data Underestanding**

**Data Visualization**

**Data Preparation:**

  **One Hot Encode all the Categorical Features**
  
  **Standardize or Normalize all the Numeric Features**
  
**Train using SKLearn's MLPRegressor (Multi-Layer Perceptron)/Regression using SKLearn's Neural Network (NN)**

**Prediction**

**Evaluating the Results**

Submission # New Insight for Modeling # Train unisng Keras API with Tensorflow as Backend
Data Underestanding
Data Visualization
Data Preparation:
One Hot Encode all the Categorical Features
Standardize or Normalize all the Numeric Features
Train unisng Keras API with Tensorflow as Backend
Prediction
Evaluating the Results
Submission




If you like it, Please upvote my notebook here https://www.kaggle.com/homayoonkhadivi/2-creative-deep-learning-models-bike-prediction

