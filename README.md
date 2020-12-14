# Neural_Netowrk_Charity_Analysis

## Overview of the Analysis
Using machine learning and neural networks, I used features in the dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by alphabet soup. 

## Results
*IS_SUCCESSFUL is considered the target(s) for this model.
*APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, ASK_AM, INCOME_AMT, STATUS and SPECIAL CONSIDERATIONS are the features for this model.
*EIN and NAME are neither targets or features and should be removed from the input data
*The number of layers and neurons were chosen based on general guideline that states, "a basic neural netowrk is to have two to three times the amount of neurons in the hidden layer as the number of inputs. The optimizer, epochs and activation functions were chosen based on the courses guidelines. 
*I was not able to achieve the target performance of 75%. 
*I tired to increase the model's accuracy by changing the number of layers, neurons, and activation functions. 

## Summary
A deep learning neural network module was created, trained and defined with a dataset on charitable donations of various groups. The end goal was to create a model to predict the success of companies recieving donations with certain datasources. The target goal was an accuracy score of 75% or greater. To imporve the model accuracy, the parameters were modified after training for parameters. The base dataset was modified to remove noisy outliers and drop other features that would not be significant in explaining the results. 

For a potneital solution to the classification problem, I reccomend using the sigmoid function. The values will be normalized to a probablity between 0 and 1 which is great for binary classifiction.  
