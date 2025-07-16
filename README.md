# 🫀 Predicting Cardiovascular Disease with Machine Learning 🚑📊

Welcome to the **Cardiovascular Disease Detection** project repository!  
This project utilizes machine learning algorithms to detect the likelihood of cardiovascular diseases based on patient health data. We explore multiple classification techniques and build robust models to assist in early diagnosis, which is critical in saving lives.

---

## 📚 Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Models Used](#models-used)
- [Usage](#usage)
- [Results](#results)
- [Visualizations](#visualizations)
- [Project Report](#project-report)

---

## Introduction

Cardiovascular diseases (CVDs) are a leading cause of global deaths. Early detection can significantly reduce the mortality rate. This project aims to predict the presence of CVD in patients using anonymized healthcare data and various machine learning models.

Our focus is on building **recall-optimized models** to minimize false negatives, ensuring that fewer actual CVD cases are missed.

---

## Dataset

The dataset contains **70,000 patient records** with the following attributes:

- Id (ID of the patient)
- Age (The age of patient in days) 
- Age  (The age of patient in years) 
- Height (The height of patients)
- Weight (The weight of patients)
- Gender (The gender of patients) 
- Ap_hi (systolic blood pressure)
- Ap_lo (diastolic blood pressure) 
- Cholesterol (Cholesterol level of patients) 
- Slucose (Glucose level of patients) 
- Smoking (Patient is habitual to smoking or not) 
- Alcohol (Patient is habitual to alcohol intake or not) 
- Active (Active life or passive life)
- Target variable: `cardio` (0 = No disease, 1 = Has disease)

---

## Models Used

We implemented and compared several machine learning algorithms:
- ✅ **Logistic Regression** (with threshold tuning using Youden’s Index)
- ✅ **Random Forest** (base and tuned)
- ✅ **Decision Tree**
- ✅ **Naïve Bayes**
- ✅ **K-Nearest Neighbors (KNN)** (with feature binning & scaling)
- ✅ **XGBoost**
- ✅ **AdaBoost**
- ✅ **Gradient Boosting**

---

## Usage
In India, huge mortality occurs due to cardiovascular diseases (CVDs) as these diseases are 
not diagnosed in early stages. Machine learning (ML) algorithms can be used to build 
efficient and economical prediction system for early diagnosis of CVDs in India. . This 
initiative will provide us with important information that can help us predict the patients with 
cardiovascular disease and It is implemented on the.pynb format.

---

## Results

We evaluated the models using the following key performance metrics:

- **Accuracy**
- **Recall** – especially critical in healthcare to minimize false negatives.

### 🔝 Top Performing Models Based on Recall:
- ✅ **Random Forest (Tuned)**
- ✅ **Gradient Boosting**

### 🔝 Top Performing Models Based on Accuracy:
- ✅ **AdaBoost**
- ✅ **Gradient Boosting**

---

## Visualizations

We used **Matplotlib** and **Seaborn** libraries to create insightful visualizations that helped us understand the impact of different features on cardiovascular risk. Key visualizations include:

- 📊 Distribution plots (Age, Height, Weight, BP)
- 🩺 Categorical bar charts (Cholesterol, Glucose, Lifestyle habits)
- 💉 Boxplots to identify and treat outliers
- 🔥 Correlation heatmap to understand feature relationships
- 🧬 Feature importance plot from Random Forest mode

📁 All visualizations are available in the [`Visualization/`](Visualization/) folder.


---

## Project Report

📥 Download the full PDF report to explore detailed documentation of the project, including:

- Business problem understanding  
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Engineering  
- Model development and tuning  
- Practical importance of the model in real-world healthcare settings

📄 [Download Final Report](CVD_Final%20report.pdf)

