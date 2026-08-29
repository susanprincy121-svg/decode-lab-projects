# Decode Labs Project 2: Multi-Class Flower Classification System

An end-to-end Machine Learning project that classifies Iris flower species based on physical measurements using supervised learning techniques.

---

## 📌 Project Overview
The objective of this project is to build, evaluate, and deploy a supervised classification model capable of categorizing Iris flowers into three target species: **Setosa**, **Versicolor**, and **Virginica**. Using morphological feature measurements, the model learns underlying feature distributions to make precise predictions on unseen data.

This project demonstrates foundational Machine Learning practices including exploratory data analysis, feature pre-processing, dataset splitting, model selection, and comprehensive performance evaluation.

---

## 🛠️ Key Features & Technical Architecture

* **Data Preprocessing & Preparation:** Handles feature scaling and splits the dataset into training and testing sets to prevent data leakage.
* **Supervised Machine Learning Model:** Implements classification algorithms (such as Decision Trees / Random Forest / Logistic Regression) trained on historical feature dimensions.
* **Performance Evaluation:** Uses quantitative metrics including Accuracy, Precision, Recall, F1-Score, and a Confusion Matrix visualization.
* **Inference Pipeline:** Accepts custom user input parameters (sepal length, sepal width, petal length, petal width) and outputs the predicted flower class.

---

## 📊 Dataset & Feature Description

The model is trained on the standard **Iris Dataset** consisting of 150 instances (50 samples per class).

### Features (Model Inputs)
1. **Sepal Length** (cm)
2. **Sepal Width** (cm)
3. **Petal Length** (cm)
4. **Petal Width** (cm)

### Target Classes (Model Outputs)
* `Iris-setosa`
* `Iris-versicolor`
* `Iris-virginica`

---

## 📈 Model Performance & Evaluation

The trained model was evaluated on a held-out test dataset containing 30 samples (10 setosa, 9 versicolor, 11 virginica).

### Evaluation Highlights
* **Accuracy:** **100% (1.00)** on the test set.
* **Misclassification Rate:** **0%** — all test samples were correctly identified.

### Confusion Matrix Breakdown
The evaluation matrix confirms perfect diagonal alignment across all predicted versus actual classes:

| Actual \ Predicted | Setosa | Versicolor | Virginica |
| :--- | :---: | :---: | :---: |
| **Setosa** | **10** | 0 | 0 |
| **Versicolor** | 0 | **9** | 0 |
| **Virginica** | 0 | 0 | **11** |

---

## ⚙️ Tech Stack & Dependencies

* **Language:** Python 3.x
* **Environment:** Jupyter Notebook / Anaconda
* **Libraries:**
  * `pandas` – Data manipulation and DataFrame management
  * `numpy` – Numerical array processing
  * `scikit-learn` – Machine learning algorithms, dataset splitting, and metrics
  * `matplotlib` & `seaborn` – Data visualization and confusion matrix plotting

---

## 💻 Installation & Usage

### 1. Clone the Repository
```bash
git clone [https://github.com/YOUR_USERNAME/Decode-Labs-Project2-Data-Classification.git](https://github.com/YOUR_USERNAME/Decode-Labs-Project2-Data-Classification.git)
cd Decode-Labs-Project2-Data-Classification
