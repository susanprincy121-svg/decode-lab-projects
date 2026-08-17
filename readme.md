# Basic Classification Model (Iris Dataset)

A supervised machine learning project demonstrating the complete end-to-end classification pipeline using Python and Scikit-Learn.

---

## 📌 Project Overview
This project builds and evaluates a K-Nearest Neighbors (KNN) classification model to categorize Iris flower species (*setosa*, *versicolor*, and *virginica*) based on physical sepal and petal measurements.

---

## ✨ Key Features & Technical Steps
- **Data Loading & Exploration:** Extracted feature vectors and target labels from the Iris dataset using Pandas.
- **Data Splitting:** Partitioned dataset into 80% training and 20% testing sets (`train_test_split`).
- **Model Training:** Trained a `KNeighborsClassifier` ($K=3$) on supervised training data.
- **Model Evaluation:** Evaluated performance metrics using accuracy scoring and plotted a Confusion Matrix via `matplotlib`.
- **Inference Pipeline:** Implemented real-time sample prediction using unseen feature inputs.

---

## 🛠️ Tech Stack & Dependencies
- **Language:** Python 3.x
- **Environment:** Jupyter Notebook / Anaconda
- **Libraries:**
  - `scikit-learn`
  - `pandas`
  - `matplotlib`
