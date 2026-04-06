# End-to-End Heart Disease Analysis and Prediction
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Markdown](https://img.shields.io/badge/Markdown-000000?style=for-the-badge&logo=markdown&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-FA0F00?style=for-the-badge&logo=jupyter&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=google-colab&logoColor=white)

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
│
├── data/
│   ├── original/ 
│   │   └── heart_disease_uci.csv      # Original data from Kaggle
│   │
│   ├── prediction/
│   │   └── heart_disease_uci_with_target.csv      # Final prediction data
│   │
│   └── preprocessed/
│       └── heart_disease_uci_preprocessed.csv      # Preprocessing data
│
├── src/
│   ├── DA_05_GD1_Preprocessing.ipynb 
│   ├── DA_05_GD2_EDA.ipynb
│   ├── DA_05_GD3_Hypothesis_Testing.ipynb
│   └── DA_05_GD4_Model_Evaluation+Bonus.ipynb
│
└── README.md
```

## Technologies Used
Programming & Environment: Python, Jupyter Notebook / Google Colab
- Data Processing & Analysis: Pandas, Numpy
- Data Visualization: Matplotlib, Seaborn
- Statistical Analysis: Scipy, Statsmodels
- Machine Learning: Scikit-learn (Classification, Clustering, Model Selection, Feature Selection, Evaluation Metrics)
- Imbalanced Data Handling: imbalanced-learn (SMOTE)
- Others: Openpyxl, tqdm, warnings
## Pipeline
There are 8 steps: 
 1. Data collection: Download Heart Disease UCI dataset from Kaggle.
 2. Data preprocessing: Preprocessing data by cleaning data, formatting data.
 3. Exploratory Data Analysis (EDA): Visualizing relationships by using suitable charts, analyzing distributions of variables, identifying correlations between features.
 4. Statistical Analysis & Hypothesis Testing: Applying statistical tests, evaluating the significane features related to heart disease
 5. Modeling: Training multiple machine learning models.
 6. Model evaluation: Evaluating models by using suitable metrics.
 7. Optimization: Tuning parameters, improving models performance.
 8. Prediction: Predicting the likelihood the heart disease, identifying important features contributing to predictions, and giving insights.
 ## How to run
 Clone all repository:
 ```bash
git clone https://github.com/mau09022004/Heart-Disease-Analysis-and-Prediction.git
cd Heart-Disease-Analysis-and-Prediction
```
## Author
* **Nguyễn Hà Anh**: [Anh Nguyen](https://github.com/ahnguyen24)
* **Bùi Lê Khôi**: [1ekh01](https://github.com/1ekh01)
* **Bùi Công Mậu**: [mau09022004](https://github.com/mau09022004)
* **Thái Hữu Thọ**: [huuThoTT](https://github.com/huuThoTT)
