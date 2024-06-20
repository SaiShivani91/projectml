## Student Performance Predictor System using Machine Learning

This is an end to end machine learning project. The main objective of the project is to build a predictor system that helps students to predict their marks or performance based on various features.
Data collection, Data Analysis, Feature Engineering, Data Visualization, Model Training, Model Evaluation and Model Deployment are the main steps involved in the project.

# Data Collection:

The dataset consists of 1000 observations and 8 features. THe various features of the dataset are:
* 'gender': Describes the gender of the student (Male and Female)
* 'race_ethnicity': Describes the race/ethnicity of the student (group A, group B, group C, group D and group E)
* 'parental_level_of_education': Describes the parents' education level of the student (bachelors' degree, associates' degree, some college, masters' degree, high school and some high school)
* 'lunch': Describes the type of lunch student has taken before exam (standard and free/reduced)
* 'test_preparation_course': Describes whether the student completed the test course or not (none and completed)
* 'math_score': Describe the score obtained by the student in math (a value between 0 to 100)
* 'reading_score': Describe the score obtained by the student in reading (a value between 0 to 100)
* 'writing_score': Describe the score obtained by the student in wrting (a value between 0 to 100)

The target feature in the dataset is 'math_score'.

# Data Analysis:

Here, various features are analysed. various steps like:

* Check for missing values
* Check for duplicated values
* Check for data type of each feature
* Check for unique values
* Check for stataistics summary of the data
* Check for numerical and categorical features in the data
* Check for outliers

  # Feature Engineering:

  Missing values are handled using imputation. Categorical features are converted into numerical features using one hot encoder.

  # Data Visualization:

  All the features are visualized using various plots like histogram, kde, coutplot and scattterplot. Varois analysis like univariate nalaysis and Bivarite analysis are performed  in order to find out the relation between various features.

  ![image](https://github.com/SaiShivani91/projectml/assets/167123523/36006f2c-b856-496b-883c-61feaf61ddff "Distribution of Female and Male")

  The above image shows the didtribution of male and female students in the dataset. It can be observed that the dataset is balanced in terms of gender.

![image](https://github.com/SaiShivani91/projectml/assets/167123523/70d94bac-19e7-49c0-9133-1b9a20c1f0ac)

The above image shows the average scores obtained by students of each group wrt race_ethnicity feature.

![image](https://github.com/SaiShivani91/projectml/assets/167123523/68245fae-62f2-4a62-b2da-47896e21ae4d)

This plot shows how the features are related to each other and the target variable 'math_score'. It shows that there is purely linear relationship between the features.

# Model Training:

Various machine learning models like Linear regression, Random Forest, Decision Tree, KNN, GradientBoost, AdaBoost, XGBoost and CatBoost were implemented along with the hyper parameter tuning. 

# Model Evaluation:

All the models are evaluated in terms of r2_Score and the model with highest r2_score is considered as the best model. Here, linear regression model is the best model with the r2_score of 0.88.

# Model Deployment:

The application is developed using Flask. The model is successfully deployed using AWS Elastic Beanstalk and codepipeline. This two were helpful in creating the required environment and creating the pipeline connecting the environment and source code for the application deployment enabling the continuous delivery (CD).


  


  

  

