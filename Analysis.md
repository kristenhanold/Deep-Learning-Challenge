# Report on the Neural Network Model

## Overview
The non-profit foundation Alphabet Soup wants to create an algorithm to predict whether or not applicants for funding will be successful. We'll be using the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

## Results

### Data Preprocessing
   * What variable(s) are considered the target(s) for your model?
          
        * The target variable for our model is "IS_SUCCESSFUL", which declares if the money was used effectively or not.
   * What variable(s) are considered to be the features for your model?
          
        * The variables considered as features for my model are "APPLICATION_TYPE" and "CLASSIFICATION". 
   * What variable(s) are neither targets nor features, and should be removed from the input data?
    
        * The variables that are neither targets nor features, and were removed from my model were "EIN" and "NAME". 
### Compiling, Training, and Evaluating the Model
   * How many neurons, layers, and activation functions did you select for your neural network model, and why?
    
        * I chose to use 90 neurons with a ReLU function for my first layer, 45 nuerons with a ReLU function for the second, and 15 neurons with a ReLU function for the third, and a sigmoid function for the outer layer. 
   * Were you able to achieve the target model performance?
    
        * I was not able to achieve the target model performance. 
   * What steps did you take to try and increase model performance?
    
        * Steps Taken to Optimize the Model: Increasing the number of values for each bin, adding more neurons to a hidden layer, adding more hidden layers, and adding number of epochs to the training regimen.

## Summary
Even after increasing the number of values for each bin, adding more neurons to a hidden layer, adding more hidden layers, and adding number of epochs to the training regimen, my model still did not achieve the target model performance and resulted in an accuracy score of 73%. 

I would recommend a classification model such as Logistic Regression due to the fact that we are trying to predict a discrete output of "whether applicants will be successful if funded by Alphabet Soup" (Yes/No). 
