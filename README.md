# Iris-Flower-Classification
This project builds a classification model to predict the species of Iris flowers based on four key measurements: sepal length, sepal width, petal length, and petal width. We use a Random Forest Classifier to perform the classification and evaluate model performance.

iris-flower-classification/
├── iris_classification.py
├── IRIS.csv
├── README.md
└── requirements.txt (optional)


# 🌸 Iris Flower Classification

This project presents a simple yet effective machine learning model that classifies Iris flowers into three species based on their sepal and petal dimensions. It is designed as part of a pre-assignment for an internship and demonstrates key ML concepts including data preprocessing, visualization, model training, evaluation, and feature importance analysis.

---

## 🎯 Task Objectives

- Develop a classification model to identify Iris flowers into three species:
  - Setosa
  - Versicolor
  - Virginica
- Perform necessary preprocessing:
  - Encode target labels
  - Scale features
- Visualize data to understand relationships
- Train a robust classification model (Random Forest)
- Evaluate model performance using standard metrics
- Identify the most important features contributing to classification

---

## 🚀 How to Run the Project

### 📋 Prerequisites

Make sure you have Python installed along with the following libraries:
```bash
pip install pandas seaborn matplotlib scikit-learn

🧠 Model Used
Random Forest Classifier

Chosen for its accuracy and interpretability

Handles multi-class classification well


📊 Output Highlights
🔍 Accuracy: >95% (depends on random split)

📈 Classification Report: Includes precision, recall, F1-score

🌟 Top Features: Petal length and petal width were most significant
