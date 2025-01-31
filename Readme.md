# Heart Attack Prediction Dataset

This repository contains a dataset for predicting the likelihood of a heart attack based on various patient health characteristics. It is intended for educational purposes, research.

![image](https://github.com/user-attachments/assets/38213412-6724-4fa0-8f59-6a70a1bcbcd4)



## Dataset Overview

This dataset contains 194 records of patient data with 14 features. The data includes both numerical and categorical features, providing a comprehensive view of patient health conditions related to heart health. 

**Key Features:**

* **Target Variable:** The target variable is `heart_attack` (or similar name), which is a binary indicator (e.g., 1 for heart attack, 0 for no heart attack).

* **Features:** The features included in the dataset are:
    *  `age`: Age of the patient (numerical)
    *  `sex`: Gender of the patient (categorical, e.g., 0 for female, 1 for male)
    * `cp`: Chest pain type (categorical)
    * `trestbps`: Resting blood pressure (numerical)
    * `chol`: Serum cholesterol (numerical)
    * `fbs`: Fasting blood sugar (binary, e.g., 1 if > 120 mg/dl, 0 otherwise)
    * `restecg`: Resting electrocardiographic results (categorical)
    * `thalach`: Maximum heart rate achieved (numerical)
    * `exang`: Exercise induced angina (binary)
    * `oldpeak`: ST depression induced by exercise relative to rest (numerical)
    * `slope`: The slope of the peak exercise ST segment (categorical)
    * `ca`: Number of major vessels (0-3) colored by flourosopy (numerical)
    * `thal`: Thalassemia (categorical)
    * **(Add any other relevant features in your dataset)**

* **Data Source:**
  This dataset was compiled from a public repository Kaggle

  
* ## Data Dictionary

| Feature      | Description                                                | Data Type    | Example Values           |
|--------------|------------------------------------------------------------|--------------|-------------------------|
| `age`       | Patient's age in years                                     | Integer    | 45, 62, 70              |
| `sex`       | Patient's gender (0=female, 1=male)                       | Binary     | 0, 1                    |
| `cp`        | Chest pain type (1=typical angina, 2=atypical angina, 3=non-anginal pain, 4=asymptomatic)| Categorical| 1, 2, 3, 4              |
| `trestbps`  | Resting blood pressure in mm Hg                            | Integer    | 120, 140, 160            |
| `chol`      | Serum cholesterol in mg/dl                                   | Integer    | 200, 250, 300            |
| `fbs`       | Fasting blood sugar > 120 mg/dl (1=true, 0=false)           | Binary     | 0, 1                    |
| `restecg`   | Resting electrocardiographic results (0=normal, 1=having ST-T wave abnormality, 2=showing probable or definite left ventricular hypertrophy)| Categorical| 0, 1, 2              |
| `thalach`   | Maximum heart rate achieved                                | Integer    | 150, 165, 180            |
| `exang`     | Exercise induced angina (1=yes, 0=no)                    | Binary     | 0, 1                    |
| `oldpeak`   | ST depression induced by exercise relative to rest          | Float      | 0.0, 1.5, 2.5            |
| `slope`     | The slope of the peak exercise ST segment (1=upsloping, 2=flat, 3=downsloping)| Categorical| 1, 2, 3            |
| `ca`        | Number of major vessels (0-3) colored by flourosopy       | Integer    | 0, 1, 2, 3            |
| `thal`      | Thalassemia (3=normal, 6=fixed defect, 7=reversable defect)| Categorical| 3, 6, 7            |
| `heart_attack`as `num` | Target variable: Presence of heart attack (1=yes, 0=no)       | Binary     | 0, 1                    |

![image](https://github.com/user-attachments/assets/25717437-762d-4be2-8eda-4eb72b99219f)


## This dataset can be used for a variety of tasks, including:

* **Heart Attack Risk Prediction:** Building machine learning models to predict the likelihood of a heart attack based on patient characteristics.
* **Exploratory Data Analysis (EDA):** Analyzing the relationships between different features and the target variable.
* **Feature Importance Analysis:** Identifying the most important features contributing to heart attack risk.
* **Model Comparison:** Comparing the performance of different machine learning models for heart attack prediction.
* **Educational Purposes:** Demonstrating practical applications of machine learning in healthcare.
