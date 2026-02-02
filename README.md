# Syntecxhub_Flower_Classification.
Project 1 - Week 2

# 🌸 Flower Classification Project

## Project Overview
This project focuses on **classifying iris flowers** using their physical measurements.  
We use the **Iris dataset**, a classic dataset in machine learning, to build and evaluate classification models.

The workflow includes:
- Exploratory Data Analysis (EDA)
- Feature visualization
- Model training and evaluation
- Confusion matrix analysis
- Building a simple CLI for predicting new flower species

---

## Dataset
- **Source**: Iris dataset from `scikit-learn`
- **Samples**: 150 flowers
- **Classes (Target)**:  
  1. Iris Setosa  
  2. Iris Versicolor  
  3. Iris Virginica
- **Features (Input Variables)**:
  - Sepal Length (cm)
  - Sepal Width (cm)
  - Petal Length (cm)
  - Petal Width (cm)

---

## Project Steps

1. **Exploratory Data Analysis (EDA)**
   - Inspect dataset structure
   - Visualize pairplots and feature distributions
   - Analyze correlations between features

2. **Model Training**
   - Logistic Regression
   - Decision Tree Classifier
   - Optional: Regularized Logistic Regression (L1 / L2)

3. **Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-score
   - Confusion matrix to identify misclassifications

4. **Prediction**
   - Build a simple **Command Line Interface (CLI)** to predict species for new inputs

---

## Requirements
- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

Install requirements using:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
