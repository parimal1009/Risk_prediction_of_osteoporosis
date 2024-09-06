Osteoporosis Risk Prediction
Project Overview
This project aims to predict the risk of osteoporosis in patients using machine learning models trained on a dataset of medical records. Osteoporosis is a condition that weakens bones, making them fragile and more likely to break. The goal is to identify individuals at risk and enable early intervention and prevention strategies.

Dataset
The dataset contains comprehensive information on health factors influencing osteoporosis development, including demographic details, lifestyle choices, medical history, and bone health indicators.

Data Dictionary
Column	Description
ID	Unique identifier for each patient
Age	Age of the patient
Gender	Gender of the patient
Hormonal Changes	Whether the patient has undergone hormonal changes
Family History with Osteoporosis	Family history of osteoporosis
Race/Ethnicity	Race or ethnicity of the patient
Body Weight	Weight details of the patient
Calcium	Calcium levels in the patient's body
Vitamin D	Vitamin D levels in the patient's body
Physical Activity	Physical activity details of the patient
Smoking	Whether the patient smokes
Alcohol Consumption	Whether the patient consumes alcohol
Medical Conditions	Medical conditions of the patient
Medication	Medication details of the patient
Prior Fracture	Whether the patient has had a prior fracture
Osteoporosis	Whether the patient has osteoporosis (target variable)
Analysis
Exploratory Data Analysis
The dataset was analyzed to understand the distribution of variables and their relationships with osteoporosis. Key insights include:

Age and Osteoporosis: Patients between 20 to 40 years have a significantly lower risk.
Hormonal Changes: Patients who have undergone hormonal changes have a higher risk.
Body Weight: Lower body weight is associated with a higher risk.
Nutrition: Lower calcium and vitamin D levels are linked to higher osteoporosis risk.
Predictive Modeling
The following machine learning models were developed to predict osteoporosis risk:

Logistic Regression
Random Forest Classifier
Decision Tree Classifier
Support Vector Classifier
The Decision Tree Classifier provided the best performance with an accuracy of nearly 87%.

Feature Importance Analysis
Feature importance analysis was conducted to determine which factors most significantly impact osteoporosis risk. Key factors include age, hormonal changes, medical conditions, medications, and lifestyle habits.

Model Evaluation
The models were evaluated using the following metrics:

Accuracy
Precision
Recall
F1 Score
Conclusion
This project successfully developed machine learning models to predict osteoporosis risk. The Decision Tree Classifier model performed best, achieving an accuracy of 87%. These predictions can assist in early intervention and improved management of osteoporosis.
