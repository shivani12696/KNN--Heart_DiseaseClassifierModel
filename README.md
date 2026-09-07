age-------      Age
sex-----        Sex
cp------        Chest Pain Type   =>>> Type of chest pain
trestbps-       Resting Blood Pressure =>> Resting blood pressure (mm Hg)
chol-----       Serum Cholesterol   =>>>> Cholesterol level (mg/dL)
fbs------       Fasting Blood Sugar    =>>>  Whether fasting blood sugar is > 120 mg/dL
restecg-----    Resting Electrocardiographic Results => Result of resting ECG
thalach------   Maximum Heart Rate Achieved => Maximum heart rate during exercise
exang--------   Exercise-Induced Angina => Whether exercise causes angina
oldpeak------  ST Depression Induced by Exercise => ST depression caused by exercise relative to rest
slope--------  Slope of Peak Exercise ST Segment => Slope of the peak exercise ST segment
ca------------ Number of Major Vessels => Number of major vessels (0–3) visible by fluoroscopy
thal---------- Thalassemia => Blood disorder/thalassemia-related test result
target-------- Target =>> Whether heart disease is present, depending on the dataset's encoding

# ❤️ Heart Disease Prediction using K-Nearest Neighbors (KNN)

## 📌 Project Overview
This project focuses on building a **Machine Learning classification model** to predict whether a person is likely to have heart disease based on various clinical and demographic features.

The **K-Nearest Neighbors (KNN)** algorithm is used for classification. The project includes data preprocessing, exploratory data analysis (EDA), feature scaling, model training, hyperparameter tuning, evaluation, and visualization of model performance.

The main objective is to understand how patient-related attributes can be used to classify individuals into two categories:

- `0` → No Heart Disease
- `1` → Heart Disease

PROJECT INCLUDES::
└──Missing Value Analysis
└──Duplicate Analysis
└──Outlier Analysis
└──⚙️ Data Preprocessing
└──🤖 K-Nearest Neighbors (KNN)
└──🔧 Hyperparameter Tuning
└──📈 Model Evaluation
└──📊 Confusion Matrix

Key Observation:
The model achieved a particularly high recall of approximately 96.9%, meaning it correctly identified most of the actual positive heart-disease cases.

The model had approximately 81.6% precision, indicating that some positive predictions were false positives.

For a medical classification problem, recall is an especially important metric because failing to identify a person who actually has the disease can have serious consequences.

