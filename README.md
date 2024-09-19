# Diabetes Classification Project

## Introduction
In this diabetes classification project, the objective is to predict whether a patient has diabetes (1) or not (0) based on various health indicators. The dataset encompasses several features including the number of pregnancies, glucose level, blood pressure, skin thickness, insulin levels, BMI, and the diabetes pedigree function, which assesses genetic predisposition to diabetes. The goal is to build an effective machine learning model to classify patients into diabetic or non-diabetic categories, using the "Outcome" variable as the target for prediction.

## Data: For more information [here](https://www.kaggle.com/datasets/nancyalaswad90/review)
The dataset used in this project includes the following attributes:
- **Pregnancies:** Number of pregnancies experienced by the patient.
- **Glucose:** Glucose level in the blood, a key indicator of diabetes.
- **BloodPressure:** Measurement of blood pressure, which can influence diabetes risk.
- **SkinThickness:** Thickness of the skin, an indirect measure of body fat.
- **Insulin:** Insulin level in the blood, crucial for understanding glucose metabolism.
- **BMI:** Body mass index, which helps assess body weight relative to height.
- **DiabetesPedigreeFunction:** A measure reflecting the genetic likelihood of diabetes based on family history.

## Methodology
To handle missing values in the dataset, a dual approach was employed. Grouping methods were used for imputing missing values in some attributes based on the distribution within specific groups. For other attributes, regression models were utilized to predict and fill in missing values, ensuring a robust dataset for analysis. This preprocessing step was crucial for maintaining the integrity of the data and ensuring the accuracy of the subsequent models.

## Modeling
Various machine learning algorithms were applied to classify diabetes outcomes effectively. Models tested include:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- AdaBoost Classifier
- Support Vector Classifier (SVC)
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes (GaussianNB)

Among the models evaluated, the XGBoost Classifier emerged as the most effective, demonstrating superior performance in classifying patients accurately. Its high recall rate underscored its ability to correctly identify patients with diabetes, making it the best choice for this project.

## Conclusion
This diabetes classification project has successfully analyzed key health features such as 'Glucose', 'BMI', and 'Age' to predict diabetes outcomes. Through extensive model testing, XGBoost Classifier was identified as the most effective model, achieving the highest recall rate. This outcome highlights the model’s efficacy in minimizing missed diagnoses and ensuring that patients with diabetes are accurately identified. The project demonstrates the power of machine learning in healthcare, offering a valuable tool for early detection and intervention in diabetes management.

![importance](https://cityupload.io/2024/09/importance_3a2d3.png)
