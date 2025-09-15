# Lab-ML-Project
Machine Learning project on lab sample analysis
# Lab Sample Machine Learning Project

## Project Overview
This project demonstrates a **Machine Learning workflow** applied to a lab oil and gas dataset. The goal is to **predict abnormal lab results** using supervised learning models. The dataset contains 50 lab samples with intentional mistakes to simulate real-world lab data cleaning challenges.

The project covers:  
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (Univariate & Bivariate Analysis)  
- Feature Engineering (scaling, ratios, interaction features)  
- Supervised Machine Learning (Logistic Regression, Random Forest, SVM)  
- Model Evaluation (Accuracy, Confusion Matrix, Classification Report)  

---

## Dataset
The dataset includes the following lab measurements:  

| Test 

| Density (D4052) 
| Sulfur High (D4294) 
| Sulfur Middle (D4294) 
| Sulfur Low (D4294) 
| Flash Point (D93) 
| Water by Karl Fischer (D4928) 
| Acid Number (D664) 
| Mercaptan (UOP 163) 
| Micro Carbon (D4530) 
| Vapor Pressure (D6377) 

> The dataset includes intentional errors for practicing data cleaning.

---

## Project Structure
Lab-ML-Project/
├── data/
│ ├── lab_dataset_raw.csv
│ ├── lab_dataset_cleaned.csv
│ └── lab_features_engineered.csv
├── notebooks/
│ ├── 1_Data_Cleaning.ipynb
│ ├── 2_Univariate_Analysis.ipynb
│ ├── 3_Bivariate_Analysis.ipynb
│ └── 4_Feature_Engineering_ML.ipynb
├── scripts/
│ ├── data_cleaning.py
│ ├── feature_engineering.py
│ └── train_models.py
├── reports/
│ ├── density_distribution.png
│ ├── flash_point_vs_label.png
│ └── feature_importance.png
├── README.md
└── requirements.txt
