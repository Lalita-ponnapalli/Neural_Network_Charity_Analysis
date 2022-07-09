# Neural_Network_Charity_Analysis

### Overview of the analysis
With using Machine learn skills I created a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

### Results:
Data Preprocessing
##### Variable that was considered as the target for my model: IS_SUCCESSFUL Column
###### Variables that were considered features for my model: Every Column except for IS_SUCCESSFUL which is our target and the ones we will drop
###### Variable that were neither targets or features for the dataset: Columns that I dropeed are EIN, NAME because they will have little to no impact om our outcome

### Compiling, Training, and Evaluating the Model
 ##### neural network model has I had 2 hidden layers. First layer had 80 neurons, the second has 30 there is also an output layer. The first and second hidden layer have the "relu" activation function and the activation function for the output layer is "sigmoid."
 ##### The model was not able to reach the target 75%. The accuracy for my model was 73%.
 ##### I have taken 3 attempts to reach 75% accuracy
 ##### Attempt1 : Dropping more columns
 ##### Dropped USE_CASEcolumn and got result of  0.7338 accuracy.
 ##### Attempt2 : Adding more hidden layers
 ##### Added one more hidden layer to the model and got result of  0.7350 accuracy.
 ##### Attempt 3 :Added more epochs to the training regimen.
 ##### Added more epochs to the training and got result of 0.7347 accuracy.
##### Summary:
#### The model ended up with the accuracy score of 73% after optimization. The initial neural network had a accuracy score of 72%. The result is more or less same. We could further also optimize our neural network by removing more features or simply adding more data to the dataset to increase accuracy. Since our accuracy score was not particularly up to the standard with neural networks, we could have used the Random Forest classifiers. This is because random forest is a robust and accurate model due to their sufficient number of estimators and tree depth. Also the random forest models have a faster performance than neural networks and could have avoided the data from being overfitted.
 
