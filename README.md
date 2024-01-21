# Automated-Monthly-Sales-Report-and-E-mail-share-Project


![Capturediabetes](https://github.com/Mona-Bhagat/Diabetes-Prediction-using-SVM-algorithm/assets/148805047/8256a2ec-8b82-4993-a2c2-dbd55022ebd5)



# Project Overview
This project aims to build a Diabetes Disease Prediction system using the Machine Learning algorithm SVM (Support Vector Machine), kernel 'Linear'

# Data Sources
The primary dataset used for this analysis is the multivariate type of dataset "diabetes" file. The dataset is publicly available on link - https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database
The model diagnostically predicts whether or not a patient has diabetes, based on certain diagnostic measurements  (BMI, insulin level, age ) and the target variable 'Outcome'. 


# Tools
	• Excel CSV
 	• Google Colab
  • Following dependencies/libraries were imported:
  * pandas
  * numpy
  * from sklearn.preprocessing import StandardScaler
  * from sklearn.model_selection import train_test_split
  * from sklearn.linear_model import svm
  * from sklearn.metrics import accuracy_score
  
# Steps involved

* Import of required libraries
* import of data
* Checking the number of missing values 
* Separating the data into features and Target
* Data standardization. Required as feature columns (Age, Glucose) had different scales
* Splitting the data into training and test data
* Model training using Support Vector Machine Model, kernel as linear
* Model evaluation using accuracy score
* Building a Predictive system with our trained model


# Results
The analysis results are summarized as follows:
* Accuracy on Training data:  0.7833876221498371
* Accuracy score on Test Data:  0.7727272727272727
* The model build was able to correctly recognize the presence of diabetes with sample data 
