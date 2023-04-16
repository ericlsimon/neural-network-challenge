# deep-learning-challenge

1. Overview of the analysis: Explain the purpose of this analysis.

The purpose  is to create a classifier using tensorflow to predict if organizations funded by Alphabet Soup are succesful based on previous data of success rate

2. Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

2a. What variable(s) are the target(s) for your model?

IS_SUCCESSFUL

2b. What variable(s) are the features for your model?

All variables minus the identification columns (EIN and NAME)

2c. What variable(s) should be removed from the input data because they are neither targets nor features?

EIN and NAME


Compiling, Training, and Evaluating the Model

2d. How many neurons, layers, and activation functions did you select for your neural network model, and why?

3 hidden layers
100 neurons for hidden layer 1 20 for hidden layer 2 and 10 neurons for hidden layer 3

2e. Were you able to achieve the target model performance?

We acheived an accuracy rate of ~72.5% for the model which was slightly under the target, but satisfactory

3. Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem?

The model that was created used a neural network that can predict whether an organization funded by Alphabet Soup will be succesful based off features. We acheived a test accuracy of ~72.5% using a 3 layer neural network. Another model that could solve this type of classification problem would be anything that uses a decision tree. Decisions trees can better utilize outliers
