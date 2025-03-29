# 🧬 Breast Cancer Prediction using Logistic Regression

This project builds a machine learning model to classify breast cancer tumors as **malignant** or **benign** using clinical data. It uses a **Logistic Regression** classifier, a simple yet powerful algorithm suitable for binary classification tasks.

---

## 📁 Project Structure

breast-cancer-prediction/
│
├── data/                  # Raw and processed datasets
│   ├── raw/               # Original dataset files
│   └── processed/         # Cleaned or transformed data
│
├── notebooks/             # Jupyter notebooks for EDA, modeling, evaluation
│   ├── 
│
├── src/                   # Source code (scripts)
│   ├── data_preprocessing.py
│   ├── model.py
│   └── utils.py
│
├── models/                # Trained and saved ML models (.pkl, .joblib)
│
├── outputs/               # Evaluation results, plots, reports
│   ├── confusion_matrix.png
│   └── metrics_report.txt
│
├── tests/                 # Unit tests for your code (optional)
│   └── test_model.py
│
├── README.md              # Project overview and instructions
├── requirements.txt       # List of required Python packages
├── .gitignore             # Files and folders to be ignored by Git
└── LICENSE                # (Optional) License file for open-source sharing


---

## 🔍 Dataset

We use the **Breast Cancer Wisconsin (Diagnostic) Dataset**, available via:

- [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- `sklearn.datasets.load_breast_cancer` (optional for small projects)

---

## 🚀 Steps in the Project

1. **Import libraries and download data**
2. **Explore and clean the dataset**
3. **Encode categorical labels**
4. **Split data into training and testing sets**
5. **Scale features**
6. **Build and train a Logistic Regression model**
7. **Evaluate model using accuracy, confusion matrix, and classification report**


---

## 🧠 Algorithms Used

- **Logistic Regression** (from `sklearn.linear_model`)


---

## 📊 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Precision

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/afaelRamirez21/breast_cancer_prediction.git
   cd breast-cancer-prediction
