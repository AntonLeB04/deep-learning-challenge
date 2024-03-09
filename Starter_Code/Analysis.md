1. Overview:  The purpose of this analysis is to aid Alphabet Soup in finding applicants for funding business ventures that have a higher chance of being successful. 
Results: 
2. Data Preprocessing
What variable(s) are the target(s) for your model?
* The variable that was targeted is the ‘IS_SUCESSFUL’
What variable(s) are the features for your model?
* The variables that were featured are the ‘IS_SUCESSFUL’, ‘APPLICATION_TYPE’, AND ‘CLASSIFICATION’
What variable(s) should be removed from the input data because they are neither targets nor features?
* The variables that should be removed are the ‘EIN’ and ‘NAME’
3. Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
* I used 80 neurons for the first hidden layer with an activation function of relu, a second hidden layer of 30 neurons and an activation function of relu, and finally an output layer of 1 with an activation function of sigmoid. This was done to get a solid base layer and to see what I could improve upon in the optimization models.
Were you able to achieve the target model performance?
* I was not able to achieve the target model performance
What steps did you take in your attempts to increase model performance?
* I increased and decreased the number of values for each bin, added more neurons to a hidden layer, added more hidden layers, used different activation functions for the hidden layers, and added and reduced the number of epochs to the training regimen. 
4. Summary: The best model that was created had an accuracy of 74.24% which is higher than the baseline model that had an accuracy of 73.04%. This highlights that having a more built out model is important when creating one. There is a possibility of reaching the desired 75% or above accuracy with more fine tuning. This would be beneficial for funding projects that are more likely going to be successful.