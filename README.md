# Heart Disease Prediction

## Overview
The Heart Disease Prediction project is a machine learning application aimed at predicting whether an individual is at risk of developing heart disease in the future. Using historical health data, this system assists in early diagnosis and preventive healthcare.

This project leverages various machine learning techniques to analyze a dataset containing 14 features, including age, sex, chest pain type, cholesterol levels, and more. The final output is a binary classification where 1 indicates the presence of heart disease and 0 indicates its absence.

## Comprehensive Data Analysis
* Null values handling
* Categorical data encoding
* Outlier detection and removal
* Feature selection using correlation matrix
* Data scaling

## Technologies Used
* Programming Language: Python
* Libraries Used:
  * Scikit-learn: For implementing machine learning models.
  * NumPy: For numerical computations.
  * Pandas: For data manipulation and analysis.
  * Seaborn: For visualizing data distributions.
  * Matplotlib: For creating static, interactive, and animated visualizations.

## Dataset
The dataset was sourced from Kaggle.
The dataset used contains 14 features, including:
* Input Features:
  * Age
  * Sex
  * Chest Pain Type
  * Resting Blood Pressure
  * Cholesterol
  * Fasting Blood Sugar
  * Rest ECG
  * Maximum Heart Rate Achieved
  * Exercise-Induced Angina
  * Slope of Peak Exercise ST Segment
  * Number of Major Vessels Colored by Fluoroscopy
  * Thalassemia
* Target Feature:
  * 1: Presence of heart disease
  * 0: Absence of heart disease

## Model Performance

The following machine learning models were evaluated based on their classification accuracy:

| Model | Accuracy |
|---|---:|
| Logistic Regression | 85.25% |
| K-Nearest Neighbors | 67.21% |
| Decision Tree | 81.97% |
| Random Forest | 90.16% |
| XGBoost | 83.61% |

The accuracy comparison is also visualized in the Jupyter Notebook.

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/manojpathondiya2017-max/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
```

### 2. Install Required Libraries

```bash
pip install numpy pandas scikit-learn seaborn matplotlib
```

### 3. Run the Jupyter Notebook

Open `project1.ipynb` using Jupyter Notebook or Google Colab.

Make sure `heart.csv` is available in the same directory as the notebook.

### 4. Run All Cells

Execute all notebook cells to perform data preprocessing, train the machine learning models, and compare their accuracy.
