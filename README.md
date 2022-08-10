# Diabetic_data ML
Predict the onset of diabetes based on diagnostic measures. This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective of the dataset is to diagnostically predict whether a patient has diabetes, based on certain diagnostic measurements included in the dataset.In this dataset, the term Diabetes Pedigree Function means it is function which scores likelihood of diabetes based on family history.

# Aim of the Project
- 1) The objective of this project is to be whether someone has diabetes or not.
- 2) Dataset has a several Medical Variables(Independent) and one  target variable or Outcome Variable(Dependent)
- 3) The independent variables in this data set are :-'Pregnancies', 'Glucose', 'BloodPressure', 'SkinThickness', 'Insulin','BMI', 'DiabetesPedigreeFunction', 'Age'
- 4) The outcome variable value is either 1 or 0 indicating whether a person has diabetes(1) or not(0).
- 5) performed various machine learning models for  which model is improving the accuracy score

## Columns of the dataset
**Pregnancies**: Number of times pregnant

**Glucose**: Plasma glucose concentration 2 hours in an oral glucose tolerance test

**Blood Pressure**: Diastolic blood pressure (mm Hg)

**Skin Thickness**: Triceps skin fold thickness (mm

**Insulin**: 2-Hour serum insulin (mu U/ml)

**BMI**: Body mass index (weight in kg/(height in m)^2)

**Diabetes Pedigree Function**: Diabetes pedigree function

**Age**: Age (years)

**Outcome**: Class variable (0 or 1) 0 mean non-diabetic and 1 means diabetic

# How to manage a project step by step implementation of models
- Analysis the dataset perfomed the Exploratory Data Analysis and checking the skew columns performed the mean  ,median its depending upon the skewness
- There are outliers in columns finding the columns by using  box plot & performed the  outliers  by using the QuantileTransformer machine learning technique 
- The train-test split is a technique for evaluating the performance of a machine learning algorithm. spliting the data into  20% test and 80% train 
-  performed models are used in Linear Regression,Logistic Regression,Decision Tree,RandomForestClassifier,Support Vector Classification
-   performed models for improving the  accuracy score 
- Achieved accuracy score of 79.87 % after training  the model ,RandomForestClassifier is model
