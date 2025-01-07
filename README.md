# deep-learning-challenge

## Analysis

### Overview
The purpose of this analysis is to create tool that can help select applicants for funding with the best chance of success in their ventures. We used the is_successful column as our target feature. With our knowledge of machine learning and neural networks, we will use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

Results: Using bulleted lists and images to support your answers, address the following questions:

### Data Preprocessing

* What variable(s) are the target(s) for your model?
    Our target variable was the is_successful column. This column determined whether or not a venture was successful after alphabetsoup invested in it.
* What variable(s) are the features for your model?
    The features in our model were: APPLICATION TYPE, AFFILIATION, CLASSIFICATION, USE CASE, ORGANIZATION, STATUS, INCOME AMT, SPECIAL CONSIDERATIONS, ASK AMT.
* What variable(s) should be removed from the input data because they are neither targets nor features?
    The variables that should be removed are EIN and Name.

### Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why?
    The most successful model had 4 different neurons and 4 different nodes. The activations functions were a "relu" in the first layer and "sigmoid" for the rest of the layers. I chose to add more layers because they seemed to help increase the model's accuracy. I chose the "sigmoid" function because it seemed to best fit the data. When I tried the "relu" function on more of the layers the model's accuracy decreased.
* Were you able to achieve the target model performance?
    I was not able to acheive the target model performance. The highest accuracy I was able to acheive was .7289.
* What steps did you take in your attempts to increase model performance?
    Some of the steps I took to increase model performance were adding more layers, adjusting the nodes, and changing the activation functions.

### Summary

    The overall results of this model was a 72.89% accuracy. Meaning that the model could accurately perdict a venture's success almost 73% of the time. I think another model that could solve this problem would be a logistic regression model. This is because it would give us the ability to use classification reports and confusin matricies which could help better adjust the model to have a higher accuracy.