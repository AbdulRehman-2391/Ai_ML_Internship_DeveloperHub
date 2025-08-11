# Task 3: Heart Disease Prediction

## Objective
Build a model to predict whether a person is at risk of heart disease using the UCI Heart Disease dataset.

## Files in this folder
- `heart_disease_classification.ipynb` — Jupyter notebook (data loading, EDA, modeling, evaluation).
- `heart.csv` — dataset file (download from Kaggle and place here).
- `README.md` — this file.

## Dataset
Heart Disease UCI Dataset (Kaggle / UCI). Save the CSV as `heart.csv` in this folder.

## Steps performed
1. Loaded the dataset using pandas.
2. Checked and handled missing values.
3. Performed basic EDA (distributions, correlations).
4. Preprocessed data: encoding categorical cols and scaling numeric features.
5. Trained two classifiers: Logistic Regression and Decision Tree.
6. Evaluated models using Accuracy, Confusion Matrix, and ROC-AUC.
7. Visualized actual vs predicted performance and ROC curves.
8. Reported feature importance from both models.

## Libraries used
- pandas, numpy, seaborn, matplotlib  
- scikit-learn

## How to run
1. Place `heart.csv` in the `Task_3_Heart_Disease` folder (download from Kaggle).  
2. Open `heart_disease_classification.ipynb` in Colab or Jupyter and run all cells.  
3. Upload `heart_disease_classification.ipynb` and `README.md` to GitHub.

## Commit message suggestion
`Add Task 3: Heart Disease Prediction (notebook + README + dataset)`
