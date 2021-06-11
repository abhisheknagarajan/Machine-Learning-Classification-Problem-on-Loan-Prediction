# Machine-Learning-Classification-Problem-on-Loan-Prediction
The Machine Learning Classification algorithms are performed on a small records of Loan Prediction data to fetch the highest possible Accuracy and AUC Score


# Problem Statement:

A study of Clustering problem on a small dataset based on Loan Prediction. Using this, we are predicting the highest Accuracy and AUC Score on a small set of Records.


# About this Dataset:

The Loan Prediction Dataset consists of 615 records and 13 columns. This dataset was taken from Kaggle.


# Column Description:

Loan_ID                Unique Loan ID

Gender                 MALE or FEMALE 

Married                Whether the Applicant is Married or Not

Dependents             Number of Dependents the Applicant shares with

Education              Whether the Applicant is Graduate or Not Graduate

Self_Employed          The Applicant is Self Employed or Not

ApplicantIncome        Income of an Applicant  

CoapplicantIncome      Income of the Dependent

LoanAmount             Loan amount in thousands of dollars

Loan_Amount_Term       Term of loan in months

Credit_History         credit history meets guidelines yes or no

Property_Area          Urban/ Semi Urban/ Rural 

Loan_Status           Loan approved (Y/N) this is the target variable


# Task Completed:

Import Libraries

Data Preparation

2.1 - Data Interpretation

2.2 - Missing Value Treatment

Exploratory Data Analysis

Data Cleaning

4.1 - Replacement

4.2 - Scale the Data

Clustering

5.1 - K Mean Clustering

5.1.1 - Optimal value of K using Elbow Plot

5.1.2 - Optimal value of K using Silhouette Score

5.1.3 - Visualizing the Silhouette Score

5.1.4 - Building the Cluster

5.1.5 - Analyzing the Cluster

5.2 - Hierarchical Clustering

5.2.1 - Model Building

5.2.2 - Dendrogram Plot

5.2.3 - Cutting the Trees

5.2.4 - Silhouette Score Method

5.2.5 - Retrieving the Cluster

Recommendation Systems

3.1 - Popularity Based Approach

3.2 - Content Based Recommendation

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

1) We used a Netflix Dataset with Movies constituting 69.1% and TV Shows constituting 30.9%.

2) Netflix's content is divided into several categories that targets Adults, Teens, Older kids and Kids.

3) We used the K means and Hierarchical Clustering Algorithms to cluster our data.

4) The optimal number of clusters we obtained is 2. Using this we built the Clusters and observed the following

   The Average Reviews from Users on TV Shows are more compared to Critics.

   Average IMDB US Voters Rating on TV Shows are more compared to IMDB Non-US Voters as goes with Movies.

   Average IMDB US Voters on TV Shows are more compared to Movies indicating marginal preference of US Voters to TV Shows.

5) On the basis of Popularity Based Approach

   The highest rated shows and movies on Netflix are not suitable for children below the age of 17.

   Average reviews from Netflix Users is more as compared to that of Critics.

   US Raters give a higher Rating compared to Non US Raters.

6) On the Basis of Content Based Approach

   We noted that Netflix could Recommend 5 Movies and TV Shows based on customer Interests


<h4>Notebook Link : <a href='https://github.com/abhisheknagarajan/Machine-Learning-Classification-Problem-on-Loan-Prediction/blob/main/Machine%20Learning%20Classification%20Problem%20on%20Loan%20Prediction.ipynb'>Machine_Learning_Classification_Problem_on_Loan_Prediction.ipynb</a></h4>

<h4>Dataset Link : <a href='https://www.kaggle.com/altruistdelhite04/loan-prediction-problem-dataset'>Loan _Prediction.csv.ipynb</a></h4>
