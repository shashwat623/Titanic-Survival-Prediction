# Titanic_Survival_Prediction
A high accuracy Machine Learning project, implementing various models to accurately predict the survival of the on board passengers in Titanic.
This project is binary classification problem, where the passenger either survived (1) or died (0). Here is a list of the columns of the dataset:
 PassengerID - Unique ID for each column
 Survived - Whether the passenger survived (1) or not (0)
 Pclass - Class of the passenger's ticket. Either 1, 2 or 3.
 Sex - Passenger's sex (male or female)
 Age - Passenger's age
 Sibsp - Number of sibling or spouses aboard the Titanic
 Parch - Number of parents or children aboard the Titanic
 Ticket - Passenger's ticket number
 Fare - The price paid for the passenger's ticket
 Cabin - Passenger's cabin number
 Embarked - Port where the passenger embarked. Can be:
      C - Cherbourg
      Q - Queenstown
      S - Southampton

Different models were used to compare and contrast their respective results and accuracy after having performed feature engineering on the data. The different models used were:
1. Logistic Regression
2. KNN
3. Support Vector Machines
4. Naive Bayes classifier
5. Decision Tree
6. Random Forrest
7. Linear Discriminant Analysis
8. Ada Boost Classifier
9. Gradient Boosting Classifier

The technique of Hyper-Parameters Tuning was also applied to a few of the above models to further enhance the accuracy.
The highest accuracy obtained was around 90% with the Random Forest classifier after appying the estimator obtained from parameter tuning of Random Forest.

The data set is available at kaggle.
Link: https://www.kaggle.com/c/titanic/data
