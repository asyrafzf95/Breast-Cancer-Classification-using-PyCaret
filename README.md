# 🧠 Breast Cancer Classification using PyCaret

This project uses the Wisconsin Breast Cancer dataset to build a classification model that predicts whether a tumor is **benign** or **malignant**. The entire machine learning workflow is implemented using **PyCaret**, a low-code library that simplifies model training and evaluation.

---

## 📊 Dataset Overview

- **Source:** UCI Machine Learning Repository  
- **Records:** 569 samples  
- **Features:** 30 numerical features  
- **Target Variable:** `diagnosis` (M = Malignant, B = Benign)

---

## 🔍 Project Steps

1. **Data Preprocessing**
   - Removed irrelevant columns (`id`, `Unnamed: 32`)
   - Handled missing values
   - Exploratory Data Analysis with histograms, box plots, and count plots

2. **Modeling with PyCaret**
   - Initialized PyCaret with `setup()`
   - Compared multiple models using `compare_models()`
   - Selected and tuned the best-performing model (CatBoost Classifier)

3. **Model Evaluation**
   - Evaluated using Accuracy, AUC, Recall, Precision, F1-Score
   - Visualized with confusion matrix and other PyCaret plots

---

## ✅ Model Performance

- **Best Model:** CatBoost Classifier  
- **Accuracy:** ~97.2%  
- **AUC Score:** ~98.5%  
- **F1-Score:** ~96.3%  
- The model performs excellently on test data, showing strong generalization and robustness.
- The model demonstrates high accuracy and recall, making it reliable for real-world tumor classification tasks. Hyperparameter tuning further improved generalization and robustness.

---

## 🛠️ Tech Stack

- **Python**
- **PyCaret**
- **Pandas**, **NumPy**
- **Seaborn**, **Matplotlib**
- **Jupyter Notebook**


