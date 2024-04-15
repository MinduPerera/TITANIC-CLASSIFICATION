# TITANIC-CLASSIFICATION
This repository contains a machine learning project focused on predicting survival outcomes from the infamous Titanic disaster. Leveraging socio-economic status, age, gender, and other relevant factors, the system aims to determine whether a passenger would survive or not.
The project comprises a dataset sourced from the Python Seaborn Library, specifically the "Titanic dataset", alongside Python source code and comprehensive documentation delineating the implementation and utilization of the classification system. Contributions and feedback are encouraged and appreciated.

Key Features:
1. Dataset preprocessing and exploration
   #Handling Missing Values: Identifying and addressing missing data points by removing affected rows.
   
   #Feature Encoding: Converting categorical variables into numerical representations through techniques.
       df['sex'] -> Male = -1        Female = 1
       df['embarked'] -> 'S'= 1,'C'= 2,'Q'= 3
   #Feature Scaling: Standardizing or normalizing numerical features to bring them within a similar range, preventing certain features from dominating the model training process.

3. Machine learning model training and evaluation
   #Algorithm Selection: Logistic Regression
   #Model Evaluation: Evaluating model performance using relevant metrics such as accuracy, precision, recall, and F1-score, as well as visualizations like confusion matrices.
   
4. Prediction of survival outcomes based on passenger attributes


