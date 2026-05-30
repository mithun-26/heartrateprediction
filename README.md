# Heart Disease Prediction System

## Overview

The Heart Disease Prediction System is a Machine Learning-based web application that predicts the likelihood of heart disease using multiple classification algorithms. The application allows users to input medical parameters and obtain predictions from four different machine learning models through an interactive Streamlit interface.

This project demonstrates the practical application of machine learning in healthcare by assisting in the early assessment of cardiovascular disease risk.

---

## Features

* Interactive web interface built with Streamlit
* Real-time heart disease prediction
* Multiple machine learning models for comparison

  * Logistic Regression
  * Decision Tree
  * Random Forest
  * Support Vector Machine (SVM)
* Automated data preprocessing
* Feature scaling using a trained scaler
* Random Forest feature importance visualization
* User-friendly input forms for medical parameters

---

## Technologies Used

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-Learn
* Joblib

---

## Dataset Features

The prediction is based on the following medical attributes:

| Feature  | Description                          |
| -------- | ------------------------------------ |
| Age      | Age of the patient                   |
| Sex      | Male or Female                       |
| CP       | Chest Pain Type                      |
| Trestbps | Resting Blood Pressure               |
| Chol     | Serum Cholesterol                    |
| FBS      | Fasting Blood Sugar                  |
| Restecg  | Resting Electrocardiographic Results |
| Thalach  | Maximum Heart Rate Achieved          |
| Exang    | Exercise Induced Angina              |
| Oldpeak  | ST Depression                        |
| Slope    | Slope of Peak Exercise ST Segment    |
| CA       | Number of Major Vessels              |
| Thal     | Thalassemia Status                   |

---

## Machine Learning Models

The application uses four supervised learning algorithms:

### Logistic Regression

A statistical classification model that predicts the probability of heart disease.

### Decision Tree

A tree-based model that makes decisions based on feature conditions.

### Random Forest

An ensemble learning method that combines multiple decision trees for improved accuracy and robustness.

### Support Vector Machine (SVM)

A powerful classification algorithm that separates classes using optimal hyperplanes.

---

## Project Structure



## Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
```

### Create Virtual Environment

```bash
python -m venv venv
```

Activate the virtual environment:

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install streamlit pandas numpy scikit-learn joblib
```

---

## Running the Application

```bash
streamlit run app.py
```

The application will be available at:

```text
http://localhost:8501
```

---

## How It Works

1. User enters medical information through the sidebar.
2. Input data is preprocessed and encoded.
3. Features are aligned with the training dataset structure.
4. Data is scaled using the trained scaler.
5. Predictions are generated using:

   * Logistic Regression
   * Decision Tree
   * Random Forest
   * SVM
6. Results are displayed instantly.

---

## Feature Importance Analysis

The application provides a feature importance visualization using the Random Forest model, helping users understand which medical parameters contribute most significantly to predictions.

---

## Future Improvements

* Model performance comparison dashboard
* Probability score predictions
* ROC and Confusion Matrix visualization
* SHAP Explainability Integration
* Deployment on AWS or Streamlit Cloud
* Integration with Electronic Health Records (EHR)
* Deep Learning-based prediction models

---

## Disclaimer

This project is intended for educational and research purposes only. It should not be used as a substitute for professional medical advice, diagnosis, or treatment.

---

## Author

**Mithun K A**

Artificial Intelligence & Machine Learning Enthusiast

---

