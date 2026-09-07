| Feature | Description |
|--------|-------------|
| `age` | Age of the patient |
| `sex` | Sex of the patient |
| `cp` | Chest pain type |
| `trestbps` | Resting blood pressure |
| `chol` | Serum cholesterol |
| `fbs` | Fasting blood sugar |
| `restecg` | Resting electrocardiographic results |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina |
| `oldpeak` | ST depression induced by exercise |
| `slope` | Slope of peak exercise ST segment |
| `ca` | Number of major vessels |
| `thal` | Thalassemia-related result |
| `target` | Heart disease classification |

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

