Osteoporosis Risk Prediction
Overview

This project aims to predict the risk of osteoporosis in patients using their medical records. Osteoporosis is a condition that weakens bones, making them more fragile and prone to fractures. By analyzing demographic details, lifestyle factors, and medical history, the project helps to identify individuals at risk and enables early intervention.
Dataset

The dataset consists of various health factors that influence osteoporosis development. These include demographic details, lifestyle habits, bone health indicators, and medical history.
Data Dictionary
Column	Description
ID	Unique identifier for each patient
Age	Age of the patient
Gender	Gender of the patient
Hormonal Changes	Whether the patient has undergone hormonal changes
Family History with Osteoporosis	Whether the patient has a family history of osteoporosis
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
Exploratory Data Analysis (EDA)

In the EDA, various relationships between the target variable (Osteoporosis) and features like age, gender, lifestyle, and medical conditions were analyzed. Key findings include:

    Age: Patients aged 20-40 have a significantly lower risk of osteoporosis.
    Hormonal Changes: Patients with hormonal changes have a higher risk.
    Body Weight: Lower body weight is associated with a higher risk.
    Lifestyle and Nutrition: Sedentary lifestyle and lower calcium/vitamin D levels are major risk factors.

Machine Learning Models

The following models were developed to predict the risk of osteoporosis:

    Logistic Regression
    Random Forest Classifier
    Decision Tree Classifier (Best performing model with 87% accuracy)
    Support Vector Classifier

Model Evaluation

Models were evaluated based on accuracy, precision, recall, F1 score, and confusion matrix. The Decision Tree Classifier provided the highest accuracy, making it the best choice for osteoporosis prediction.
Feature Importance

Feature importance analysis revealed that factors like Age, Hormonal Changes, Medical Conditions, and Body Weight are crucial in predicting the risk of osteoporosis.

Results

    The Decision Tree Classifier achieved an accuracy of 87%, making it the most accurate model for predicting osteoporosis risk.
    Further analysis revealed that key risk factors include Age, Hormonal Changes, and Body Weight.

Conclusion

This project successfully predicts the risk of osteoporosis in patients, enabling early intervention strategies. Future improvements could include tuning more hyperparameters, increasing data diversity, and testing more advanced models.
