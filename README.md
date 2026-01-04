INTERN_TASK_3_Titanic_survival
Titanic Survival Prediction
 Problem Statement
The goal of this task is to build a machine learning model that predicts whether a passenger survived the Titanic disaster based on available features such as age, gender, ticket class, fare, and embarkation port.
This is a binary classification problem where:
1 → Survived
0 → Did Not Survive
Tools & Technologies Used
Programming Language: Python
IDE: VS Code (Jupyter Extension)
Libraries:
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
Approach / Workflow
1️⃣ Data Loading
Loaded Titanic dataset (train.csv)
Inspected data shape, columns, and basic statistics
2️⃣ Data Cleaning
Handled missing values:
Age → filled with median
Fare → filled with median
Embarked → filled with mode
Dropped irrelevant columns (Cabin, Ticket, PassengerId)
3️⃣ Feature Engineering
Extracted Title from Name
Encoded categorical variables:
Sex, Embarked, Title
Converted features to numerical format
4️⃣ Model Building
Split data into train and test sets
Trained multiple models:
Logistic Regression
Random Forest Classifier
Selected the best performing model
5️⃣ Model Evaluation
Evaluated using:
Accuracy score
Confusion Matrix
Classification Report
Conclusion
This project demonstrates a complete machine learning pipeline, including data preprocessing, feature engineering, model training, evaluation, and model persistence.
The trained model successfully predicts passenger survival with good accuracy and follows best practices suitable for an internship-level machine learning task.
👤 Author
Krishna Kumar
Machine Learning Intern
