# Derivable-judgement
#  Derivable Judgement - Health Prediction System

##  Project Overview

This project is based on a health dataset where we predict whether a patient has a disease or not.
It uses machine learning to derive judgement from health parameters like Age, BMI, and Blood Pressure.

---

##  Objective

The main objective of this project is to:

* Analyze health data
* Predict disease risk (0 = No Disease, 1 = Disease)
* Help in decision-making using data

---

##  Dataset Information

The dataset contains the following features:

* Age → Age of the patient
* BMI → Body Mass Index
* Blood Pressure → Patient's BP level
* Disease → Target variable (0 or 1)

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn

---

##  Methodology

1. Load the dataset
2. Split data into training and testing sets
3. Train the model using Logistic Regression
4. Predict results on test data
5. Evaluate model accuracy

---

##  Model Used

* Logistic Regression
  This model is used for binary classification (Disease / No Disease).

---

##  Results

* The model predicts whether a patient is at risk or not
* Accuracy is calculated to measure performance
* Higher BMI and Blood Pressure increase disease risk

---

##  Example Prediction

Input:
Age = 45, BMI = 33, Blood Pressure = 142

Output:
➡ High Risk of Disease

---

##  Conclusion

This project shows how machine learning can help in healthcare by predicting diseases.
It helps doctors and users to make better decisions based on data.

---

##  Future Improvements

* Use larger real-world dataset
* Add more features (cholesterol, sugar level)
* Improve accuracy with advanced models
* Create a web or mobile app
