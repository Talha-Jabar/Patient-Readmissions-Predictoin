# Patient-Readmissions-Predictoin
Machine Learning || Prediction Model || XGBoost 
# Predicting Patient Readmissions

This repository contains a machine learning project on **Predicting Patient Readmissions**, where models are trained to predict whether a patient will be readmitted to the hospital within a certain timeframe based on historical medical records.

## Project Overview
Predicting patient readmissions is a critical task in healthcare, helping hospitals to improve patient care and reduce costs. In this project, machine learning techniques are used to analyze patient data and predict the likelihood of readmission.

## Dataset
The dataset used in this project is provided in a CSV file (`diabetic_data.csv`). It contains detailed records of diabetic patients, including their medical history and hospital visits.

### Features in the Dataset
- **Patient ID**: Unique identifier for each patient.
- **Admission Type**: Type of admission (emergency, urgent, elective).
- **Diagnosis Codes**: ICD-9 codes for primary and secondary diagnoses.
- **Procedures**: Codes for medical procedures performed.
- **Length of Stay**: Duration of hospital stay.
- **Medication**: Information on medications prescribed.
- **Readmission**: Target variable indicating whether the patient was readmitted ("Yes" or "No").

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd predicting-patient-readmissions
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook Predicting_Patient_Readmissions.ipynb
   ```
4. Follow the steps in the notebook to preprocess the data, train the model, and evaluate its performance.

## Requirements
- Python 3.8+
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
  
## Methodology
1. **Data Preprocessing**:
   - Handling missing values.
   - Encoding categorical features.
   - Feature scaling.

2. **Model Training**:
   - Several classification models are evaluated, including Logistic Regression, Random Forest, and Gradient Boosting.
   - The best-performing model is selected based on cross-validation results.

3. **Evaluation**:
   - The model's performance is evaluated using accuracy, precision, recall, and F1-score.
   - A confusion matrix and ROC curve are plotted to assess classification performance.

## Results
The notebook provides:
- Predictions on patient readmissions.
- Model evaluation metrics.
- Feature importance analysis.

## Future Improvements
- Experiment with deep learning models for better performance.
- Incorporate additional patient demographic data.
- Deploy the model as an API for integration with hospital management systems.
