# Intelligent Health & Network Analytics Suite

An integrated Machine Learning project that combines **classification** and **regression** techniques to solve real-world problems in both **healthcare** and **network performance analysis**.

This repository demonstrates the application of supervised machine learning algorithms for:

* Predicting heart disease using **K-Nearest Neighbors (KNN)**
* Predicting network performance metrics using **Regression Models**

The project highlights data preprocessing, feature engineering, model training, evaluation, and predictive analytics using Python and Scikit-learn.

---

# 📋 Project Overview

This repository contains two machine learning systems:

## 1. Heart Disease Classification

A healthcare prediction system that classifies whether a patient is likely to have heart disease based on clinical attributes.

### Algorithm Used

* K-Nearest Neighbors (KNN)

### Achieved Performance

* **Accuracy:** 91.30%

---

## 2. Network Performance Prediction

A regression-based system that predicts network performance metrics using structured numerical network data.

### Algorithm Used

* Linear Regression

### Achieved Performance

* **R² Score:** 0.8813

---

# 🎯 Objectives

The main goals of this project are:

* Apply supervised machine learning techniques to real-world datasets
* Build both classification and regression pipelines
* Perform preprocessing and feature engineering
* Evaluate model performance using standard metrics
* Demonstrate practical AI applications in healthcare and networking

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# 📊 Datasets

## Healthcare Dataset

The heart disease dataset contains:

* 918 patient records
* Clinical and medical attributes
* Binary target classification

### Features Include

* Age
* Sex
* Chest pain type
* Cholesterol
* Blood pressure
* ECG results
* Maximum heart rate
* Exercise angina
* ST slope

---

## Network Dataset

The network dataset contains:

* Structured numerical network data
* Multiple input features
* Continuous performance target variable

Used to train regression models for predicting network behavior and performance indicators.

---

# 🚀 Machine Learning Workflow

## 1. Data Preprocessing

* Handling missing values
* Feature scaling using `StandardScaler`
* One-Hot Encoding for categorical variables
* Data balancing techniques
* Feature selection

---

## 2. Train/Test Split

Datasets were split into:

* **80% Training**
* **20% Testing**

---

## 3. Model Training

### Classification Model

```python
from sklearn.neighbors import KNeighborsClassifier

classifier = KNeighborsClassifier(
    n_neighbors=5,
    metric='minkowski',
    p=2
)
```

### Regression Model

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()
```

---

# 📈 Results

## Heart Disease Classification Results

| Metric    | Score  |
| --------- | ------ |
| Accuracy  | 91.30% |
| Precision | 87%    |
| Recall    | 93%    |
| F1-Score  | 90%    |

### Key Insights

* Strong prediction accuracy
* Very low false negatives
* Effective preprocessing improved performance significantly

---

## Network Performance Regression Results

| Metric   | Score  |
| -------- | ------ |
| R² Score | 0.8813 |
| MSE      | 0.1358 |
| RMSE     | 0.1850 |

### Key Insights

* Regression successfully captured relationships in the dataset
* Feature scaling improved model stability
* Good generalization on unseen data

---

# 💻 Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/PROJECT_NAME.git
cd PROJECT_NAME
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

Or manually:

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```

---

# ▶️ Running the Projects

## Open Jupyter Notebook

```bash
jupyter notebook
```

Run:

* `classification_final.ipynb`
* `regression_final.ipynb`

---

# 📁 Project Structure

```bash
Intelligent-Health-Network-Analytics/
│
├── datasets/
│   ├── heart.csv
│   └── network performance2.csv
│
├── notebooks/
│   ├── classification_final.ipynb
│   └── regression_final.ipynb
│
├── requirements.txt
├── README.md
└── images/
```

---

# 🔍 Features

## Healthcare Prediction System

* Binary disease classification
* Data balancing
* Feature encoding
* Medical risk prediction

## Network Analytics System

* Network metric prediction
* Regression analysis
* Numerical feature processing
* Performance forecasting

---

# 📚 Learning Outcomes

Through this project:

* Implemented classification and regression pipelines
* Improved understanding of preprocessing techniques
* Learned model evaluation strategies
* Applied machine learning to multiple domains
* Practiced data analysis and visualization

---

# 🎓 Future Improvements

* Add Deep Learning models
* Build a web dashboard using Flask or FastAPI
* Deploy models online
* Add hyperparameter tuning
* Implement advanced ensemble algorithms
* Add real-time prediction APIs

---

# 📷 Suggested Improvements for GitHub

To make this repository stronger for recruiters/interviewers, consider adding:

* Architecture diagrams
* Dataset visualizations
* Confusion matrix screenshots
* Regression plots
* Demo GIFs
* Deployment links

---

# ⚠️ Disclaimer

This project is for educational and research purposes only.

The healthcare prediction system should not be used as a substitute for professional medical diagnosis.

---

# 👨‍💻 Author

Developed by a Computer Science student passionate about:

* Machine Learning
* Networking
* Backend Development
* Data Analytics

---

# ⭐ Project Highlights

✅ Machine Learning Classification
✅ Machine Learning Regression
✅ Real-world Datasets
✅ Data Preprocessing
✅ Model Evaluation
✅ Python & Scikit-learn
✅ Healthcare + Networking Applications
