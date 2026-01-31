# Kyphosis Surgery Outcome Prediction

This project applies **machine learning techniques** to predict the outcome of
kyphosis surgery using clinical data. The goal is to support medical decision-making
by identifying factors associated with surgical success.

## Objective
To solve a **binary classification problem** where the target variable indicates
whether kyphosis is present or absent after surgery:
- `Kyphosis = absent`: successful surgery
- `Kyphosis = present`: unsuccessful surgery

## Dataset
The project uses the `kyphosis.csv` dataset, widely employed for educational and
research purposes. The dataset includes clinical variables such as:
- Patient age
- Number of vertebrae involved
- Starting point of the surgical intervention

## Methodology
The workflow follows a standard machine learning pipeline:
1. Exploratory Data Analysis (EDA)
2. Data preprocessing
3. Handling class imbalance using SMOTE
4. Model training (Logistic Regression)
5. Model evaluation using:
   - Accuracy
   - Confusion Matrix
   - Classification Report
   - ROC Curve and AUC

Special attention is given to the **interpretability of the results**, which is
especially important in healthcare-related applications.

## Repository structure
- `kyphosis_surgery_prediction.ipynb`: main notebook
- `data/`: dataset used in the project

## Usage
Open the notebook and run the cells sequentially. The dataset path may need to be
adjusted depending on the execution environment.
