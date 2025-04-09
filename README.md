# deep-learning-challenge

## Overview
- The project is about creating a deep learning model that can predict whether applicants will be successful if funded by Alphabet Soup.

## Data Processing
- Among the features in the provided dataset, `IS_SUCCESSFUL` is the target variable, and the output value is used to predict whether the funding was successful.

- `APPLICATION_TYPE`, `AFFILIATION`, `CLASSIFICATION`, `USE_CASE`, `ORGANIZATION`, `STATUS` `INCOME_AMT`, `SPECIAL_CONSIDERATIONS`, `ASK_AMT` are the features variable used for the prediction in the model.

- `IN` and `NAME` is the variable that should be removed because they are irrelevant in prediction.

## Compiling, Training, and Evaluating
- In the neural network created, there are three layers first, second and the output layer with neurons double the input features in the first, neurons equal to the input features in the second layer and one neuron in the output layer. The reason behind having these layers with those number of neurons is to have well balanced learning capability and to understand the complex features and identify a pattern for the prediction with in the neural network created.

- The neural network created couldn't achieve the target model performance.

- Since the target model performance was not achieved, certain changes were made in order to increase model performance. THe changes are, multiple layers were added, with increased number of neurons within the updated layers and trained the data for more epochs in order to let the model have more detailed learning.

## Summary 
- The model created was able to achieve an accuracy of 72.96% whereas after the optimization the model was able to achieve an accuracy of 73.10%. Although the model was not able to achieve the target model performance it did a decent performace. 

- For better performance, other models that work well with datasets containing both categorical and numerical features and offer better readability with minimal processing would be a better recommendation.