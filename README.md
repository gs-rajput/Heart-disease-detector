HEART DISEASE DETECTOR

A Machine Learning project that predicts the likelihood of heart disease using the Heart Disease dataset from Kaggle.
This project demonstrates data preprocessing, exploratory data analysis (EDA), model training, evaluation, and predictions on new patient data in a Jupyter Notebook.

DATASET

Source: Kaggle – Heart Disease Dataset (https://www.kaggle.com/ronitf/heart-disease-uci
)
Total Records: 303 patients
Target column: target →
1 = Heart disease present
0 = No heart disease


INSTALLATION

Clone this repository and install dependencies:
git clone https://github.com/yourusername/Heart-Disease-Detector.git

cd Heart-Disease-Detector
pip install -r requirements.txt

HOW TO RUN

Download the dataset from Kaggle and place heart.csv in the project folder.

Launch Jupyter Notebook:
jupyter notebook

Open and run heart_disease_detector.ipynb.

The notebook will:

Load the dataset

Perform preprocessing (cleaning, scaling, splitting)

Train a Logistic Regression model

Evaluate accuracy and metrics

Predict heart disease for new patient data

RESULTS

Model Used: Logistic Regression
Train-Test Split: 80-20
Accuracy: Around 80% (may vary)

EXAMPLE PREDICTION

Example patient data:
[35, 0, 1, 110, 180, 0, 0, 190, 0, 0.0, 2, 0, 3]

Process:
Scale with the trained scaler
Predict using the trained model
Output → 0 (No Heart Disease)


REQUIREMENTS

Python 3.10+
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter

Install with: pip install -r requirements.txt