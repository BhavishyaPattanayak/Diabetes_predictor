# Diabetes_predictor
Predicts whether a patient has diabetes
This project demonstrates the creation of a diabetes predictor using various machine learning algorithms implemented with scikit-learn. Decision Tree, Random Forest, Support Vector Machine (SVM), and Naive Bayes classifiers were implemented and evaluated. Random Forest emerged as the most accurate model, and hence, it was chosen for the final diabetes predictor.
The goal of this project is to develop a diabetes predictor based on available healthcare data. The dataset contains features like glucose level, blood pressure, BMI, and others, which can be used to predict whether a person has diabetes or not.
Four different classification algorithms were implemented using scikit-learn:

1.Decision Tree
2.Random Forest
3.Support Vector Machine (SVM)
4.Naive Bayes
Each algorithm was trained and evaluated using the diabetes dataset to measure its accuracy and performance.
After evaluating the performance of each algorithm, the Random Forest classifier was found to have the highest accuracy on the dataset (0.8064516129032258). As a result, the Random Forest algorithm was chosen as the final model for the diabetes predictor.
To use the model, input your values:
rfc.predict([[Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age]])
