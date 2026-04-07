# 🫀 Heart Disease Classification (Machine Learning)

This repository contains a complete **machine learning project** that predicts whether a patient has heart disease based on clinical and diagnostic features. The goal is to build and evaluate models that can assist in early detection using structured health data.

---

## 🚀 Project Overview

Heart disease is a leading cause of death globally. Early prediction and diagnosis can significantly improve treatment outcomes. This project uses supervised learning techniques to classify patients as having heart disease or not.

The project includes:
- Exploratory data analysis (EDA)
- Data preprocessing
- Multiple classification models
- Model evaluation and comparison
- Interpretation of results

---

## 📂 Repository Contents

| File / Folder | Description |
|---------------|-------------|
| `heart-disease.ipynb` | Main Jupyter Notebook with entire analysis and modeling workflow |
| `data/heart.csv` | Dataset used for training and evaluation |
| `README.md` | This file |
| `output/` (optional) | Saved plots or models |

---

## 📈 Dataset

The dataset contains clinical and diagnostic attributes collected for patients. Each row represents a patient and columns include features such as:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol
- Fasting blood sugar
- Resting ECG results
- Max heart rate achieved
- Exercise induced angina
- ST depression induced by exercise
- Slope of peak exercise ST segment
- Number of major vessels colored by fluoroscopy
- Thalassemia  
- Target label: presence (1) or absence (0) of heart disease

---

## 🧠 Modeling Workflow

The notebook implements the following steps:

1. **Data Loading and Inspection**
2. **Exploratory Data Analysis (visualizations & summary statistics)**
3. **Data Cleaning**
4. **Feature Engineering**
5. **Train / Test Split**
6. **Model Training**
   - Logistic Regression
   - Random Forest
   - SVM
   - Other classifiers
7. **Evaluation**
   - Accuracy
   - Confusion matrix
   - ROC curves
   - Cross‑validation
8. **Comparison of models**
9. **Conclusions and insights**

---

## 📦 Requirements

To run the notebook locally, install the following dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
- Matplotlib, Seaborn

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
