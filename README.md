# Neural_Network_Charity_Analysis

## Overview of Analysis
Created a binary classifier for a client at Alphabet Soup to predict if applicants will be sucessful if funded by the company by using a dataset of previous organizations funded over the years. 

## Results
### Data Preprocessing
- Variable considered the target for model: IS_SUCCESFUL column
- Variable considered the feature for model: IS_SUCCESSFUL which is our target and the ones dropped.
- Variables that were neither of a target or feature: EIN, NAME which were dropped because they have little impact on the outcome. 

### Compiling, Training, and Evaluating the model
#### The number of neurons, layers, and activation functions selected for the neural network model:
-Neural network model had 2 hidden layers. First layer had 80 neurons, the second had 30 and output layer. The first and second hidden layer had the relu activation function and activation function for the putput layer as sigmoid. 
#### Does the model achieve the target preformance:
- The first model was not able to reach the target accuracy of 75%. The accuracy was 61%.
Steps taken to increase the preformance:
- First removed the USE_CASE column
      - However the accuracy dropped to 53%
- Second attempt added additional neurons to hidden layers and additional hidden layers were added. The accuracy went down again to 49%

## Summary
The model ended up with decreased accuracy with more optimization. Further optimization to increase accuracy could be by removing more features, adding random forest classifers. 
