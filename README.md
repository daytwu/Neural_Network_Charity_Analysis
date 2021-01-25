# Neural_Network_Charity_Analysis

## Overview
Alphabet Soup has tasked us to create a binary classifier to predict if an organization will be successful or not if funded by the charity foundation. The amount of 

## Results
- Data Preprocessing

-- What variable(s) are considered the target(s) for your model?
 
 The target variable is most definitely the 'IS_SUCCESSFUL' column here in the datasets. This is the case because the data here directly indicates if the organization has been successful or not, which is what we are trying to classify.
 
-- What variable(s) are considered to be the features for your model?

All other variables was considered to be features except for EIN and NAME, which was the first initial dropped columns. Through optimization testing, AFFILIATION and USE_CASE has also been dropped for testing.

-- What variable(s) are neither targets nor features, and should be removed from the input data?

EIN and NAME was the first removed variable as they are for indexing and does not contribute to how organizations will succeed or fail.

- Compiling, Training, and Evaluating the Model

-- How many neurons, layers, and activation functions did you select for your neural network model, and why?

