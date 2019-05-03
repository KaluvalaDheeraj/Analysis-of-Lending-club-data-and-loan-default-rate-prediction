## Analysis-of-Lending-club-data-and-loan-default-rate-prediction
Aim :
Our Goal, in this Project to predict whether a person can grant a loan or not and if any person already borrowed loan, will repay or not. As if, (1 = Fully Paid) or default (0 = Charged Off) to generate a prediction for each and every id. 
And to classify if the borrower will default the loan using borrower’s finance history. That means, given a set of new predictor variables, that we need to predict the target variable as 1 as Defaulter or 
0 as Non-Defaulter. The metric we use to choose the best model for predictor and target variables 

Existing Solution :
In Existing System, there is no similar theory to work on Lending Club investors and borrowers data whether a person can grant a loan or not and if any person already borrowed loan, will repay or not. There is an Existing Scenario with approach is that the data set was modified to balance the number of “good” and “bad” cases on Loan defaults data set.

Project Idea 
To overcome the above difficulties we here construct a model based on supervised learning of the data points using an algorithm which best suits the data and provides high accuracy on the classification of the test data with a minimal time and space complexity. 
We initially read the data from the database, and then perform exploratory data analysis (EDA) for better understanding the data and attributes. Then we perform data cleaning and data pre- processing over the entire data set to remove tags, missing values, noisy data and outliers. Later we split the data randomly into train and test data set in certain ratio and use an algorithm over the train data set to construct the model and try to predict the class label for test data and determine the accuracy. 

## Comparision of Alogirthm Results : 
 
## s.no 	Models 	Accuracy 	Precision 	F1 Score 
1 	Random Forest 	0.80 	0.81 	0.81 
2 	Logistic Regression 	0.814 	0.83 	0.81 
3 	K-Nearest neighbours 	0.77 	0.79 	0.77 
4 	Support vector machine 	0.80 	0.83 	0.80 
5 	Bagging using RF 	0.82 	- 	- 
6 	Bagging using Logistic Regression	0.817 	- 	- 
7 	Ada Boosting 	0.819 	- 	- 
8 	Multi layer Perceptron (MLP) 	0.818 	0.83 	0.82 
