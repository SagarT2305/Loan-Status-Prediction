# Loan-Status-Prediction

Problem Statement_1: For the given dataset, predict the Loan Eligibility Status for applicant.
Problem Statement_2: For the given dataset, predict the Loan Amount for the applicant.
Problem Statement_3: For the given dataset, predict the Loan AMount Term for the applicant.


Steps involved into developing this model

1. Remove columns with unique values.
2. Missing data treatment.
3. Data Visualization.
4. Pre-processing on data such as One Hot Encoding for categorical columns and Standardization for continuous columns.
5. Diving the dataset into training and testing sets.
6. Check correlation with other columns in the dataset and choose best features for the model.


Models used for predictions:

1. LogisticRegression
2. DecisionTreeClassifier with Pruning
3. RandomForestClassifier with Pruning
4. AdaBoostClassifier
5. KNeighborsClassifier
6. keras Tuner 
