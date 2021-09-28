# Predict_Housing_Price_using_ML_algorithms

- This is the very first hands-on project that I attempted to apply multiple Machine Learning algorithms, including:
  - Linear Regression
  - Logistic Regression
  - DecisionTreeRegression
  - RandomForestRegression
  - AdaBoost

- Dataset used in this small project is California Housing Price dataset, which used in the second chapter of Aurélien Géron's book 'Hands-On Machine learning with Scikit-Learn and TensorFlow'. However, the dataset contains information from the 1990 California census. Still, it is widely used for fresh learners when studying Machine Learning algorithms.

- For preprocessing data, I used some techniques provided by `scikit-learn` like 
  - `SimpleImputer` for filling missing numerical missing values
  - `OneHotEncoder` and OrdinalEncoder for categorical values
  - `StandardScaler` for feature-scaling
  - Eventually, everything is put together via `Pipeline`

- While training, I also applied `RandomSearchCV` and `GridSearchCV` to optimize computational expense for fine-tuning while training ML models.
