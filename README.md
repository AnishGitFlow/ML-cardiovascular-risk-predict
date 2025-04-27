# ML-cardiovascular-risk-predict

# Cardiovascular Risk Prediction

This project predicts the 10-year risk of coronary heart disease (CHD) using patient health data and machine learning models. The notebook explores data preprocessing, feature engineering, model training, and evaluation to identify the best-performing classifier for CHD risk prediction.

## Problem Statement

Predict whether a patient has a 10-year risk of future coronary heart disease (CHD) based on clinical and demographic features.

## Dataset

The dataset contains 3,390 records with 17 features, including:
- Demographics (age, sex, education)
- Lifestyle factors (smoking, cigarettes per day)
- Medical history (hypertension, diabetes, stroke, medications)
- Clinical measurements (cholesterol, blood pressure, BMI, heart rate, glucose)
- Target: `TenYearCHD` (0 = No, 1 = Yes)

## Approach

- Data cleaning and handling missing values
- Exploratory data analysis and visualization
- Feature engineering and encoding
- Model training using:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)
  - XGBoost
- Model evaluation using accuracy, precision, recall, F1-score, and confusion matrix

## Usage

1. Clone the repository:
    ```
    git clone https://github.com/AnishGitFlow/cardiovascular-risk.git
    ```
2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```
3. Open and run the Jupyter notebook:
    ```
    jupyter notebook cardiovascular_risk.ipynb
    ```

## Results

The notebook compares multiple classifiers and reports their performance. The best model can be selected based on evaluation metrics for deployment or further research.

## Requirements

See `requirements.txt` for the list of dependencies.

## License

This project is for educational purposes.
