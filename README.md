## Titanic-ML-Project
This project predicts whether a passenger on the Titanic survived or not using Machine Learning. We use the Titanic dataset from Kaggle and apply Logistic Regression and Random Forest classifiers to predict survival based on various passenger attributes.

## Table of Contents
1. Dataset
2. Project Workflow
3. Installation
4. Results & Evaluation
5. Future Improvements
6. Contributing
7. License
## Dataset
1. Source: Kaggle Titanic Dataset
2. Files Used:
    - train.csv (Training Data)
    - test.csv (Test Data)
3. Features:
    - Survived: Target variable (1 = Survived, 0 = Not Survived)
    - Pclass: Ticket class (1st, 2nd, 3rd)
    - Sex: Male or Female
    - Age: Passenger age
    - SibSp: Number of siblings/spouses aboard
    - Parch: Number of parents/children aboard
    - Fare: Ticket fare
    - Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Project Workflow
 1. Data Preprocessing
- Handle missing values (Age, Embarked, Cabin)
- Convert categorical values (Sex, Embarked) into numerical form
- Create new features (FamilySize = SibSp + Parch + 1)
- Remove irrelevant columns (PassengerId, Name, Ticket)
2. Exploratory Data Analysis (EDA)
- Visualizing survival rates by gender, class, and family size
- Analyzing correlation between features
3. Machine Learning Models
- Logistic Regression
- Random Forest Classifier
4. Model Evaluation
- Accuracy, Precision, Recall, F1-score
- Confusion Matrix
## Installation
To run this project, install the required Python libraries:
 -  pip install pandas numpy matplotlib seaborn scikit-learn

## Results & Evaluation
-  Logistic Regression Accuracy: ~81%
-  Random Forest Accuracy: ~85%

> Key Insights:

- Women had a higher survival rate than men
- First-class passengers had better survival chances
- Younger passengers had a higher probability of survival

## Future Improvements
- Hyperparameter Tuning (GridSearchCV for best parameters)
- Feature Engineering (Extracting more features from names and tickets)
- Ensemble Methods (Boosting models like XGBoost)
- Deep Learning Approach (Using a Neural Network for better performance)
