# Neural_Network_Charity_Analysis

### Overview of the analysis
With using Machine learn skills I created a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

### Results:
Data Preprocessing
##### Variable that was considered as the target for my model: IS_SUCCESSFUL Column
![image](https://user-images.githubusercontent.com/100485119/178125438-88988e07-7245-4570-afe3-89c36f6f02c4.png)

###### Variables that were considered features for the model: Every Column except for IS_SUCCESSFUL which is our target and the ones we will drop
###### Variable that were neither targets or features for the dataset: Columns that I dropeed are EIN, NAME because they will have little to no impact om our outcome
![image](https://user-images.githubusercontent.com/100485119/178125445-f73f3aba-1ad9-48b9-8f7d-390f90e380f2.png)

### Compiling, Training, and Evaluating the Model
 ##### neural network model has I had 2 hidden layers. First layer had 80 neurons, the second has 30 there is also an output layer. The first and second hidden layer have the "relu" activation function and the activation function for the output layer is "sigmoid."
 ##### The model was not able to reach the target 75%. The accuracy for my model was 73%.
 ![image](https://user-images.githubusercontent.com/100485119/178125463-b52b4397-ad4f-487b-a034-53dd9d79fe0c.png)

 ##### I have taken 3 attempts to reach 75% accuracy
 ##### Attempt1 : Dropping more columns
 ![image](https://user-images.githubusercontent.com/100485119/178125517-1529e323-dc8c-427a-97d4-39d10e60a07f.png)

 ##### Dropped USE_CASEcolumn and got result of  0.7338 accuracy. Checked if we delete additional columns that can increase the accuracy.But result was similar to original model.
 ##### Attempt2 : Adding more hidden layers
![image](https://user-images.githubusercontent.com/100485119/178125547-3414c61a-f37d-4536-b681-f993f2056455.png)

 ##### Added one more hidden layer to the model and got result of  0.7350 accuracy. Used 3 hidden layers to get the expected 75% accuracy, but result was similar to original model.
 ##### Attempt 3 :Added 130 epochs to the training regimen.
 ![image](https://user-images.githubusercontent.com/100485119/178125551-1831f2ee-ac6a-40be-88f0-91c542183d0b.png)

 ##### Added more epochs to the training and got result of 0.7347 accuracy. Used 130 epochs to get the expected result of 75%,t result was similar to original model.
### Summary:
#### The model ended up with the accuracy score of 73% after optimization. The initial neural network had a accuracy score of 72%. The result is more or less same. We could further also optimize our neural network by removing more features or simply adding more data to the dataset to increase accuracy. Since our accuracy score was not particularly up to the standard with neural networks, we could have used the Random Forest classifiers. This is because random forest is a robust and accurate model due to their sufficient number of estimators and tree depth. 
 
