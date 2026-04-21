🧠 Stroke Prediction Using Machine Learning | Python

Predicting the likelihood of stroke occurrence using machine learning techniques to support early detection and preventive healthcare decisions.
________________________________________

📌 Project Overview

• Stroke is a major global health challenge and one of the leading causes of death worldwide. 

• Early detection of stroke risk is critical in reducing mortality and improving patient outcomes.

• This project uses machine learning techniques to analyse patient health data and predict the likelihood of stroke occurrence. 

• By identifying key risk factors such as age, hypertension, and glucose levels, the model provides insights that can support preventive healthcare strategies.
________________________________________
🚨 Problem Statement

• Stroke is the second leading cause of death globally, responsible for approximately 11% of total deaths worldwide. 

• Despite advances in healthcare, early detection of stroke risk remains a significant challenge due to the complex interaction of multiple health and lifestyle factors.

• Healthcare providers often rely on clinical assessments, which may not fully capture hidden patterns within patient data. 

• Without predictive tools, it becomes difficult to identify high-risk individuals early and implement preventive measures.

• This project addresses this challenge by applying machine learning techniques to patient data to predict stroke risk. 

• The goal is to uncover key predictors and build a model that supports early intervention and data-driven healthcare decision-making.
________________________________________

🎯 Project Objectives

•	Analyse patient health and lifestyle data to identify stroke risk factors

•	Perform exploratory data analysis (EDA) to understand feature distributions

•	Build and compare multiple machine learning models

•	Evaluate model performance using appropriate metrics

•	Identify the most effective model for stroke prediction
________________________________________

📂 Dataset Overview

The dataset was sourced from Kaggle and contains patient-level health and lifestyle information.

Key Features:

•	Gender

•	Age

•	Hypertension

•	Heart Disease

•	Marital Status

•	Work Type

•	Residence Type

•	Average Glucose Level

•	BMI


•	Smoking Status

Target Variable:

•	Stroke (1 = Stroke, 0 = No Stroke)

________________________________________
🧹 Data Preparation & Cleaning

•	Handled missing values (BMI imputed using mean)

•	Converted categorical variables into numerical format using dummy variables

•	Standardised data for modelling

•	Checked for inconsistencies in binary variables (hypertension, heart disease)
_
_______________________________________

📊 Exploratory Data Analysis (EDA)

Key Findings:

•	Stroke cases are highly imbalanced (more non-stroke than stroke cases)

•	Older patients (40–80 years) show higher stroke occurrence

•	Patients with hypertension and heart disease have higher stroke risk

•	Higher glucose levels are strongly associated with stroke

•	Smoking history increases stroke probability

•	BMI showed less significant impact compared to other variables

________________________________________

🤖 Machine Learning Models

The following models were developed and evaluated:

•	Logistic Regression

•	Decision Tree Classifier

•	Random Forest Classifier

________________________________________

📈 Model Training & Evaluation

•	Data split into training and testing sets

•	Models evaluated using:

o	Accuracy

o	Confusion Matrix

o	Precision-Recall

Results:


•	Logistic Regression: 93.8% accuracy

•	Decision Tree: 93.6% accuracy

•	Random Forest: 93.6% accuracy

👉 Logistic Regression performed best overall due to consistency and interpretability.

________________________________________

🔍 Key Insights

•	Age and glucose level are strong predictors of stroke risk

•	Hypertension and heart disease significantly increase risk

•	Smoking history contributes to higher stroke probability

•	Work type and lifestyle factors also influence stroke occurrence

•	BMI is not a strong standalone predictor

________________________________________


🎯 Business / Healthcare Impact

•	Supports early identification of high-risk patients

•	Enables preventive healthcare interventions

•	Helps clinicians make data-informed decisions


•	Demonstrates how machine learning can improve patient outcomes

________________________________________

🛠️ Tools & Technologies

•	Python (Pandas, NumPy, Scikit-learn)

•	Machine Learning Models (Logistic Regression, Decision Tree, Random Forest)

•	Jupyter Notebook

•	Data Visualization (Matplotlib / Seaborn)

________________________________________

🧪 Project Workflow

1.	Data Loading and Preprocessing

2.	Exploratory Data Analysis (EDA)

3.	Data Cleaning and Feature Engineering

4.	Model Training and Validation


5.	Model Evaluation

6.	Prediction and Insight Generation

________________________________________

🚀 Future Improvements

•	Apply SMOTE or balancing techniques for imbalanced data

•	Use ROC-AUC for deeper evaluation

•	Deploy model using a web application

•	Integrate real-time patient data

________________________________________

📝 Conclusion

• This project demonstrates how machine learning can be applied to healthcare data to predict stroke risk and identify key contributing factors. 

• The findings highlight the importance of age, glucose levels, and underlying health conditions in stroke occurrence.

• The final model provides a strong foundation for building predictive healthcare systems that can support early diagnosis and improve patient outcomes.

