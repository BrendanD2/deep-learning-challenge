# deep-learning-challenge
# Alphabet Soup Charity Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis is to find if an applicant will find success based on their organization type, classification type, funding, and other classifications.
* This can be beneficial for organizations on if they need to improve in certain areas or expand to ensure that they are successful.
* This challenge utilizes using dummy variables for categorical values and using a keras neural network model to produce on accuracy on if the organization will be successful. 
* First I cleaned the data so that there is not too many obscure categorical variables so that there is not overfitting for the neural network. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
    * Through the first model we recieved an accuracy around 72% using sigmoid and relu as hidden layers for the neural network after processing the data.
    * Then, I attempted to optimize the model by using more hidden layers, leaving out the STATUS and ASK_AMT variables, and using higher and lower units (tested up to 1000 units and 300 epochs).
    * Unfortunately, the model was not able to improve and would need more intensive research towards which variables would be essential to improve the model. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Neither of the models were able to produce accuracies over 75% and would require more extensice research towards the hidden layers, input variables, epochs, and more. 
