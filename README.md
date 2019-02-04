# Artificial-Neural-Network

* The Dataset consisted of 10,000 entries with different attributes of a customer like- ID, name, Credit Score, place from where they belong, Gender, Age, Tenure, Bank Balance, Estimated Salary and whether the person exited the bank or not.
* First the data is divided into the factors that helps in predicting the result and whether the person will leave bank or not. 
* The data is then converted into categorical data using LabelEncoder and is fit to 0 and 1's category using OneHotEncoder. 
* Data is split into training and test, 25 % being the test data. Then the data is scaled using StandardScalar .
* Using Keras, ANN model is initialized and the input, two hidden layers and an output layer is added. After compiling the training dataset, an accuracy of 86.35% and a loss of 0.3364 was obtained. 
* The accuracy predicted on the test data using a confusion matrix and a threshold of 5.2 was 86.36%. 
* Apart from predicted on the whole dataset, using the algorithm, it can be predicted whether a future customer will exit the bank or not.
* Predicted the accuracy using K-Fold Cross Validation Technique. 
* Found the best accuracy and the feature that helps in achieving the highest accuracy possible.
