# Heart Disease Prediction System

## Project Overview
This project is based on Machine Learning techniques used to predict the possibility of heart disease in a patient using medical attributes such as age, blood pressure, cholesterol, chest pain type, maximum heart rate, etc.

The project performs data preprocessing, visualization, model training, prediction, and evaluation using different classification algorithms.



## Objectives
- To analyze patient health data
- To preprocess and clean the dataset
- To train machine learning models
- To compare model performance
- To predict whether a person is likely to have heart disease or not



## Technologies Used
- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn



## Algorithms Used
### 1. Logistic Regression
Used for binary classification to predict heart disease presence.

### 2. K-Nearest Neighbors (KNN)
Classifies patients based on similarity with nearest data points.


## Steps Performed

### Data Collection
The heart disease dataset was imported using Pandas.

### Data Preprocessing
- Removed missing values
- Checked null values
- Feature selection performed
- Data scaling using StandardScaler

### Data Visualization
Graphs and plots were used to understand:
- Correlation between features
- Distribution of target values
- Important health parameters

### Model Training
Dataset was divided into:
- Training Data
- Testing Data

Models trained:
- Logistic Regression
- KNN Classifier

### Model Evaluation
Performance evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report



## Features Used
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- Oldpeak
- Slope
- CA
- Thal



## Results
- Logistic Regression provided good accuracy for prediction.
- KNN also performed effectively after feature scaling.
- The system successfully predicts the likelihood of heart disease.



## Conclusion
The Heart Disease Prediction System demonstrates how machine learning can assist in early disease prediction using patient medical data. This project helps in understanding classification algorithms and healthcare data analysis.



## Future Improvements
- Use larger datasets
- Deploy as a web application
- Add more machine learning models
- Improve accuracy using hyperparameter tuning
