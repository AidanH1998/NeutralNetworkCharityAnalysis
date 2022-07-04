# NeutralNetworkCharityAnalysis


## Overview ##

Using Machine Learning and Neural Networks we are able to predict if the aplication will be able to fund the charity.


## Results ##

### Data Preprocessing ### 

What variable(s) are considered the target(s) for your model?
It is targeting the successful colums, means that the money is being use by the charities.

What variable(s) are considered to be the features for your model?
NAME, APPLICATION, TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT,SPECIAL_CONSIDERATIONS, STATUS, and ASK_AMT

What variable(s) are neither targets nor features, and should be removed from the input data?
EIN (Employer identificaiton) data misleading. STATUS beacuse they were all the same. Can drop any variable that are the same.


### Compiling, Training, and Evaluating the Model ###

How many neurons, layers, and activation functions did you select for your neural network model, and why?
Three hidden layers each with many neurons. Changing the 2nd and 3rd activation to sigmoid helps increase the accuracy.

Were you able to achieve the target model performance?
Yes

What steps did you take to try and increase model performance?
Using sigmoid in activation 2 and 3 and also changing NAME for data points


## Summary ## 
