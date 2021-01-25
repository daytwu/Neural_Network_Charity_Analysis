# Neural_Network_Charity_Analysis

## Overview
Alphabet Soup has tasked us to create a binary classifier to predict if an organization will be successful or not if funded by the charity foundation. The amount of 

## Results

### Data Preprocessing

- What variable(s) are considered the target(s) for your model?
 
 The target variable is most definitely the 'IS_SUCCESSFUL' column here in the datasets. This is the case because the data here directly indicates if the organization has been successful or not, which is what we are trying to classify.
 
- What variable(s) are considered to be the features for your model?

All other variables was considered to be features except for EIN and NAME, which was the first initial dropped columns. Through optimization testing, AFFILIATION and USE_CASE has also been dropped for testing.

- What variable(s) are neither targets nor features, and should be removed from the input data?

EIN and NAME was the first removed variable as they are for indexing and does not contribute to how organizations will succeed or fail.

### Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why? 

In total, 170 nodes were used in the layers, 2 different activation functions were used through 3 layers. These are all done to test the optimization process to see if the target performance can be achieved.

- Were you able to achieve the target model performance?

Initial Attempt
<img width="565" alt="Initial Attempt" src="https://user-images.githubusercontent.com/68725398/105669808-f94f2980-5ead-11eb-8e33-a5968244ff2a.png">

Final Optimization Attempt
<img width="567" alt="Final Optimization attempt" src="https://user-images.githubusercontent.com/68725398/105669813-fc4a1a00-5ead-11eb-9790-331de407f65c.png">

Unfortunately no. As shown above, target model performance was not achieved. The final optimization ended up at 65%, which was a drop from from the original.

- What steps did you take to try and increase model performance?

Steps were taken to as attempts to increase performance by removing additional variables in AFFILIATION and USE_CASE, adding more neurons to layers, adding an additional hidden layer and changing the activation function for the hidden layer.

## Summary

The deep learning model was only able to achieve 65% in total after 3 optimization attempts, which was a drop in performance from the initial 72% prior to making the changes. With that said, Random forest or logistic regression models should also be considered for similar and perhaps faster results.
