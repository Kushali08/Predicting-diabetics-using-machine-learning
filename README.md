Classification
About the Project

This project predicts whether a patient has diabetes (1) or not (0) using machine learning.
The dataset contains patient health details such as pregnancies, glucose, blood pressure, insulin, BMI, age, and more.
The goal is to support early diagnosis and improve healthcare planning.

 Objectives

Predict diabetes using patient health data.

Find important factors affecting diabetes risk.

Compare different ML models and select the best one.

 Dataset Information

Rows (Observations): 768

Columns (Features): 8 features + 1 target (Outcome)

Attribute	Description	Data Type
Pregnancies	,Number of times pregnant	,Integer
Glucose,	Plasma glucose concentration (mg/dL),	Integer
BloodPressure,	Diastolic blood pressure (mm Hg),	Integer
SkinThickness,	Triceps skin fold thickness (mm),	Integer
Insulin,	2-Hour serum insulin (mu U/ml),	Integer
BMI,	Body Mass Index,	Float
DiabetesPedigreeFunction,	Diabetes likelihood based on family history,	Float
Age,	Age in years,	Integer
Outcome	1 = Diabetic, 0 = Non-diabetic	Integer

Data cleaning (no missing or duplicate values).

Exploratory analysis with histograms, scatter plots, and heatmaps.

Gradient Boosting gave the best accuracy = 85% (80:20 split).
