# Diabetes Prediction using PyTorch

This project demonstrates the use of a PyTorch-based Artificial Neural Network (ANN) for predicting diabetes. The dataset used is sourced from the **Pima Indians Diabetes Dataset**.

## Features
- Binary classification to predict diabetes (1 for diabetic, 0 for non-diabetic).
- Data preprocessing using Pandas.
- Custom PyTorch ANN model with training and validation.
- Visualization of training loss using Matplotlib.

---

## Dataset

The dataset contains the following features:
- `Pregnancies`: Number of times pregnant
- `Glucose`: Plasma glucose concentration (mg/dL)
- `BloodPressure`: Diastolic blood pressure (mm Hg)
- `SkinThickness`: Triceps skinfold thickness (mm)
- `Insulin`: 2-Hour serum insulin (mu U/ml)
- `BMI`: Body Mass Index (weight in kg/(height in m)^2)
- `DiabetesPedigreeFunction`: Diabetes pedigree function (genetic impact)
- `Age`: Age of the patient
- `Outcome`: Target variable (1 for diabetic, 0 for non-diabetic)

---

## Installation

### Prerequisites
- Python 3.8 or higher
- PyTorch
- Pandas
- Matplotlib
- Scikit-learn (for data splitting)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diabetes_prediction.git
   cd diabetes_prediction
