# Titanic Survival Prediction 
### Goal
The job is to predict if a passenger on a Titanic Ship survived the sinking of the Titanic or not. 

### Input Data
##### train.csv:
The training set will be used to build machine learning models. For the training set, the outcome (also known as the “ground truth”) for each passenger is being provided. The file contains features like - </br>
</br>
PassengerId: Unique ID of the passenger</br>
Survived: Survived (1) or died (0)</br>
Pclass: Passenger's class (1st, 2nd, or 3rd)</br>
Name: Passenger's name</br>
Sex:Passenger's sex</br>
Age: Passenger's age</br>
SibSp: Number of siblings/spouses aboard the Titanic</br>
Parch: Number of parents/children aboard the Titanic</br>
Ticket: Ticket number</br>
Fare: Fare paid for ticket</br>
Cabin: Cabin number</br>
Embarked: Where the passenger got on the ship (C - Cherbourg, S - Southampton, Q = Queenstown)</br>

##### test.csv:
The test set is used to see how well our model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. The outcome for each passenger in the test set is predicted using the model we have trained, whether or not they survived the sinking of the Titanic.</br>

### Output Data
##### submission.csv:
This file contains only two coulmns - PassengerId and Survived (1 or 0)</br>
We just need to predict values of Survived as Survived (1) or died (0)</br>