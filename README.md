# End-to-End Heart Disease Analysis and Prediction
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-FA0F00?style=for-the-badge&logo=jupyter&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

## Overview
This project focuses on analyzing heart disease data to uncover key factors influencing cardiovascular conditions and support data-driven decision-making in healthcare.By using the UCI Heart Disease dataset, containing clinical and demographic information of patients from the UCI Machine Learning Repository.The main objective of this project is to predict whether a patient is likely to have heart disease.

## Dataset

This is a multivariate dataset consisting of both numerical and categorical variables that describe patient health conditions, clinical test results, and demographic information. These features are used to analyze patterns and build predictive models for heart disease classification.

- **id**: Unique identifier for each patient  
- **age**: Age of the patient (years)  
- **origin**: Source dataset / place of study  
- **sex**: Gender of the patient  
- **cp**: Chest pain type (typical angina, atypical angina, non-anginal, asymptomatic)  
- **trestbps**: Resting blood pressure (mm Hg)  
- **chol**: Serum cholesterol level (mg/dl)  
- **fbs**: Fasting blood sugar > 120 mg/dl (True/False)  
- **restecg**: Resting electrocardiographic results  
- **thalach**: Maximum heart rate achieved  
- **exang**: Exercise-induced angina (True/False)  
- **oldpeak**: ST depression induced by exercise relative to rest  
- **slope**: Slope of the peak exercise ST segment  
- **ca**: Number of major vessels (0–3) colored by fluoroscopy  
- **thal**: Thalassemia condition (normal, fixed defect, reversible defect)  
- **target (num)**: Presence of heart disease (prediction label)  

## Project Structure
```
Heart-Disease-Analysis-and-Prediction/
├─ data/
│   ├─ processed/       # Processed data (Running code -> folder will be created)
│   └─ raw/             # Original data
├─ src/
│   └─ process/
│       ├─ data/
│       │   ├─ eda.ipynb           # Data visualization through Python
│       │   └─ splitdata.ipynb     # Divided dataset into 2 parts: train, test dataset
│       │
│       ├─ data_crawling/
│       │   └─ crawler.ipynb # Crawling data by Python
│       │
│       ├─ preprocessing/
│       │   ├─ normalization.ipynb        # Normalize dataset into suitable format
│       │   └─ preprocessing.ipynb        # Preprocessing dataset
│       │
│       └─ questions/
│           ├─ question1.ipynb
│           ├─ question2.ipynb
│           ├─ question3.ipynb
│           ├─ question4.ipynb
│           └─ question5.ipynb
│
├─ .gitignore
├─ requirements.txt
└─ README.md
```
