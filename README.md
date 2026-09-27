# 🎓 Enhancing Student Outcomes Through Machine Learning: Insights from Predictive Modeling

## 📌 Project Overview
This project explores the application of machine learning techniques to predict student performance and identify at-risk learners based on academic, demographic, and behavioral data. By developing robust predictive models, the study aims to provide educators with actionable insights to facilitate early, targeted interventions and improve overall academic success rates. 

## 🗄️ Dataset
* **Source:** Student Performance Prediction (2024) synthetic dataset by Souradip Pal.
* **Size:** 40,000 structured records.
* **Attributes Analyzed:** Study Hours per Week, Attendance Rate, Previous Grades, Participation in Extracurricular Activities, Parent Education Level, and the target variable, Passed.

## 🛠️ Methodology & Tools
* **Data Preprocessing:** Handled missing values (imputing medians for numerical data and 'Missing' for categorical data), corrected invalid entries (e.g., negative study hours, attendance rates exceeding 100%), and applied feature scaling using `StandardScaler`.
* **Class Balancing:** Addressed slight class imbalances in the target variable using the Synthetic Minority Over-sampling Technique (SMOTE).
* **Machine Learning Algorithms:** Evaluated Random Forest, Logistic Regression, K-Nearest Neighbors (KNN), Gradient Boosting, Naive Bayes, and a hard-voting Ensemble Classifier.
* **Tech Stack:** Python, Pandas, NumPy, Scikit-Learn, Imbalanced-learn, Matplotlib, and Seaborn.

## 📊 Key Findings & Model Performance
* **Top Performing Models:** Random Forest, Logistic Regression, Gradient Boosting, Naive Bayes, and the Voting Classifier all achieved a highly accurate 95% classification rate and an ROC AUC of 0.95. 
* **Competitive Baseline:** KNN performed competitively with a 94% accuracy.
* **Primary Predictors:** Attendance rate, weekly study hours, and previous grades emerged as the most significant indicators of a student's likelihood to pass. 
* **Extracurricular Impact:** The analysis revealed that participation in extracurricular activities had no significant impact on passing rates.
* **Business Value:** The predictive models demonstrate that proactive attendance monitoring and focused academic interventions can reliably enhance student retention and success.

## 📁 Repository Structure
* `student-performance-prediction-case-study.ipynb`: The complete Python codebase containing exploratory data analysis (EDA), data cleaning, SMOTE application, and model evaluation metrics.
* `student_performance_prediction.csv`: The dataset used for model training and testing.
