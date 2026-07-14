# Heart Disease Prediction using Machine Learning

## Project Overview
This project focuses on building a machine learning model to predict the likelihood of heart disease based on various medical attributes. 
The model uses a dataset containing medical information such as age, sex, blood pressure, cholesterol levels, and more to classify whether or not a patient is likely to develop heart disease.

Heart disease is one of the leading causes of death worldwide, and early prediction of heart-related conditions can help in effective treatment and prevention. 
This project demonstrates how to implement a machine learning pipeline to classify heart disease risk, using classification algorithms like Logistic Regression, Random Forest, or Support Vector Machines (SVM).

## Key Features
- **Data Preprocessing**: Handles missing values, normalizes the data, and encodes categorical variables.
- **Feature Engineering**: Feature selection based on correlation and importance to reduce model complexity.
- **Machine Learning Models**: Implements multiple machine learning algorithms to find the best-performing model:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
- **Model Evaluation**: Evaluates model performance using accuracy, confusion matrix, precision, recall, and F1-score.
- **Cross-Validation**: Uses k-fold cross-validation to generalize model performance and avoid overfitting.

## Dataset
The dataset used in this project is the **UCI Heart Disease Dataset**, which contains 303 instances and 14 features, including:
- **Age**: Age of the patient.
- **Sex**: Gender (1 = male, 0 = female).
- **Chest Pain Type (cp)**: 0 = typical angina, 1 = atypical angina, 2 = non-anginal pain, 3 = asymptomatic.
- **Resting Blood Pressure (trestbps)**: The resting blood pressure (in mm Hg).
- **Cholesterol (chol)**: Serum cholesterol level in mg/dl.
- **Fasting Blood Sugar (fbs)**: > 120 mg/dl (1 = true, 0 = false).
- **Resting ECG (restecg)**: Resting electrocardiographic results (values 0, 1, 2).
- **Maximum Heart Rate (thalach)**: Maximum heart rate achieved.
- **Exercise-Induced Angina (exang)**: 1 = yes, 0 = no.
- **Oldpeak**: ST depression induced by exercise relative to rest.
- **Slope**: Slope of the peak exercise ST segment (0, 1, 2).
- **Number of Major Vessels (ca)**: Number of major vessels (0-3) colored by fluoroscopy.
- **Thalassemia (thal)**: 1 = normal, 2 = fixed defect, 3 = reversible defect.
- **Target**: 0 = no heart disease, 1 = heart disease (target variable).

## Model Architecture
The following machine learning algorithms are applied to predict heart disease:
- **Logistic Regression**: A simple linear classifier for binary classification.
- **Random Forest**: An ensemble learning method using multiple decision trees.
- **SVM (Support Vector Machine)**: A robust classifier that finds the optimal hyperplane.
- **KNN (K-Nearest Neighbors)**: A non-parametric method used for classification.

## Technologies Used
- **Python 3**
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib** and **Seaborn**: For data visualization.
- **scikit-learn**: For implementing machine learning models and evaluation metrics.
