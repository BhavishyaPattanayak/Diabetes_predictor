# Diabetes Predictor

This project demonstrates the creation of a diabetes predictor using various machine learning algorithms implemented with scikit-learn. The goal is to develop a reliable model to predict whether a patient has diabetes based on available healthcare data.

## Project Overview

In this project, four different classification algorithms were implemented and evaluated:

1. Decision Tree
2. Random Forest
3. Support Vector Machine (SVM)
4. Naive Bayes

Each algorithm was trained and evaluated using a diabetes dataset that includes features such as glucose level, blood pressure, BMI, and more.

## Dataset

The dataset contains the following features:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

## Results

After evaluating the performance of each algorithm, the Random Forest classifier was found to have the highest accuracy on the dataset (0.8064516129032258). As a result, the Random Forest algorithm was chosen as the final model for the diabetes predictor.

## Usage

To use the model, input your values as shown below:

```python
rfc.predict([[Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age]])
```
## Conclusion

This project highlights the effectiveness of different machine learning algorithms in predicting diabetes, with the Random Forest classifier emerging as the most accurate model. The developed predictor can serve as a useful tool in healthcare settings to assist in early diabetes detection and intervention.

