# Machine-Learning-Classification-Problem-on-Loan-Prediction
The Machine Learning Classification algorithms are performed on a small records of Loan Prediction data to fetch the highest possible Accuracy and AUC Score


# Problem Statement:

A study of Clustering problem on a small dataset based on Loan Prediction. Using this, we are predicting the highest Accuracy and AUC Score on a small set of Records.


# About this Dataset:

The Loan Prediction Dataset consists of 615 records and 13 columns. This dataset was taken from Kaggle.


# Column Description:

Loan_ID            -        Unique Loan ID

Gender             -        MALE or FEMALE 

Married            -        Whether the Applicant is Married or Not

Dependents         -        Number of Dependents the Applicant shares with

Education          -        Whether the Applicant is Graduate or Not Graduate

Self_Employed      -        The Applicant is Self Employed or Not

ApplicantIncome    -        Income of an Applicant  

CoapplicantIncome  -        Income of the Dependent

LoanAmount         -        Loan amount in thousands of dollars

Loan_Amount_Term   -        Term of loan in months

Credit_History     -        credit history meets guidelines yes or no

Property_Area      -        Urban/ Semi Urban/ Rural 

Loan_Status        -        Loan approved (Y/N) this is the target variable


# Algorithms Handled

Logistic Regression Before and After SMOTE

Naive Bayes Before and After SMOTE

K-Nearest Neigbour Before and After SMOTE

Decision Tree  Before and After SMOTE

Random Forest Before and After SMOTE

ADA-BOOST Before and After SMOTE

Gradient Boosting Before and After SMOTE

XGBoost with Before and After SMOTE

stacking Classifier


# Conclusion :

1) There has been a considerable increase in the overall accuracy of classification which is 78% with AUC Score of 79.7%, after handling the imbalance in the data using SMOTE and Stacking multiple individual  classifiers as well as tuning the hyper parameters of the models.

2) For a small training dataset, the ensemble method of stacking can provide better classification performance than the original algorithms.

3) Various applications in real world can benefit from this method as it can effectively reduce the demands of labelled samples while maintaining a satisfactory classification performance.


<h4>Notebook Link : <a href='https://github.com/abhisheknagarajan/Machine-Learning-Classification-Problem-on-Loan-Prediction/blob/main/Machine%20Learning%20Classification%20Problem%20on%20Loan%20Prediction.ipynb'>Machine_Learning_Classification_Problem_on_Loan_Prediction.ipynb</a></h4>

<h4>Dataset Link : <a href='https://www.kaggle.com/altruistdelhite04/loan-prediction-problem-dataset'>Loan _Prediction.csv</a></h4>
