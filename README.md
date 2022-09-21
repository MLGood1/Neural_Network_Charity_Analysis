# Neural_Network_Charity_Analysis

## Overview

The objective of this analysis is to apply machine learning and neural network processes to a dataset supplied by Alphabet Soup to create a binary classifier that will predict whether an applicant will be successful if funded by Alphabet Soup.

## Results

### Data Preprocessing

![image](https://user-images.githubusercontent.com/104471775/191396497-4ed31566-9197-4db1-a4db-abb3e4af43a8.png)

* The target (y) of this model was whether the applicant was successful after being funded by Alphabet Soup, variable: IS_SUCCESSFUL. 
* The features (X) of this model were APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.

![image](https://user-images.githubusercontent.com/104471775/191397485-b8e8a133-57a1-4a5d-b806-d65dc748ad59.png)

* The variables that were dropped from the dataset are EIN and NAME.

### Compiling, Training, and Evaluating the Model

![image](https://user-images.githubusercontent.com/104471775/191397916-20dfecfb-be91-49b0-9980-f8ae9f87907e.png)

* I designed the model with two hidden layers, with 10 neurons for the first layer and 5 neurons for the second layer.  In the first and second layers, I used a relu activation to identify nonlinear characteristics of the data.  In the output layer, I selected a sigmoid activation because it is a predicition funcition.

![image](https://user-images.githubusercontent.com/104471775/191399358-68689a47-595f-41af-a2d7-b6fc18217648.png)

* This model design had a 53% predictive accuracy rate.  

#### Optimization

I tried to optimize the model to get an predictive accuracy rate higher than 75%.  

![image](https://user-images.githubusercontent.com/104471775/191399877-a32a0611-4d73-4f36-9e6c-951d4d6baf7c.png)
![image](https://user-images.githubusercontent.com/104471775/191400117-2c338f41-e990-4233-bed4-c717986b5599.png)

* I dropped two more columns from the dataset.
* I added a third hidden layer.
* In the first hidden layer I increased the number of neurons to 12.

## Summary
This model had a predictive accuracy of 53% before and after the steps taken to optimize the model. Instead of creating a neural network model, I would suggest using a SVM model that is similar to a neural network model, but is not prone to ovefitting the data. 
