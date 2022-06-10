# Loan-prediction-using-Machine-Learning-and-Python
Aim:
 
 The main aim of this project is to predict the loan eligibility of a person.
 
 To predict the loan data by using some machine learning algorithms they are logistic regression,Decision Tree,RandomForest.
 
 

Attributes in the dataset:


Loan id, Gender, Married, Dependents, Education, Self Employed, Applicant income, Coapplicant income, Loan Amount,Credit History, Property_Area, Loan_Status.

Methodology:


Data requirements: It is a very vital role of a data analyst to check for the requirements of the data. What actually they need and what not?

Data collection: Collecting data is also a important part of the same as we need structred data and with minimal amount of anomolies.

Data understanding: Exploratory Data Analysis (EDA) is done on the given data to see for the features that are most important and also check for errors.

Data preparation: After cleaning process we prepare the data for model development.

Model Development: In this vary stage we undergo the use of different machine learning algorithm to check which algorithm best fits the model and which does not.

Evaluation: After model development we check the performance metrics and do validation and also checks for the accuracy which produces more accurate results.


Tools & Technology used:

Python

Jupyter Notebook

Python libraries: pandas,matplotlib,seaborn&scikit-learn

Major observation from the data

Applicants who are male and married tends to have more applicant income whereas applicant who are female and married have least applicant income.

Applicants who are male and are graduated have more applicant income over the applicants who have not graduated.

Again the applicants who are married and graduated have the more applicant income.

Applicants who are not self employed have more applicant income than the applicants who are self employed.

Applicants who have more dependents have least applicant income whereas applicants which have no dependents have maximum applicant income.

Applicants who are graduate and have credit history have more applicant income.

Loan Amount is linearly dependent on Applicant income

From heatmaps,The most correlated variables are (ApplicantIncome - LoanAmount) and (Credit_History - Loan_Status).

LoanAmount is also correlated with CoapplicantIncome.

Male applicants are more than female applicants.

No of applicants who are married are more than no of applicants who are not married.

Applicants with graduation are more than applicants whith no graduation.


Conclusion:

    
Exploratory data Analysis on the features of this dataset and saw how each feature is distributed.

Bivariate and multivariate analysis to see imapct of one another on their features using charts.

Each variable to check if data is cleaned and normally distributed.

The data Cleaned and removed NA values.

Correaltion between independent variables and found that applicant income and loan amount have significant relation.

Loan prediction for customers using  logistic Regression,decision tree model and random forest model.

To Predict Loan data

The  Decision Tree model  accuracy score 81%.

The logistic regression model accuracy score 84%.

The Random Forestmodel accuracy score 85%.

The random forest model performed much better than the decision tree and logistic regression.


   
