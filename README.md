# ❤️ Heart Disease Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-Classifier-green)
![License](https://img.shields.io/badge/License-MIT-yellow)


## 📌 Project Overview

This project predicts whether a patient is likely to have heart disease based on medical information. It uses the **UCI Heart Disease Dataset (processed.cleveland.data)** and compares multiple Machine Learning classification algorithms to identify the best-performing model.

The project includes data preprocessing, model training, evaluation, hyperparameter tuning, model comparison, and prediction using user-provided input.

---

## 🎯 Objective

The objective of this project is to predict the possibility of heart disease using patient medical data and compare different Machine Learning algorithms to determine the most accurate model.

---

## 📂 Dataset

**Dataset:** UCI Heart Disease Dataset

**File Used:**
- `processed.cleveland.data`

The dataset contains medical information such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG Results
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression
- Slope of ST Segment
- Number of Major Vessels
- Thalassemia
- Target (Heart Disease)

Missing values represented by `?` are handled during preprocessing.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Joblib

---

## 🤖 Machine Learning Models

The following classification algorithms were trained and compared:

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier
- XGBoost Classifier

---

## ⚙ Project Workflow

1. Import Required Libraries
2. Load Dataset
3. Assign Column Names
4. Explore Dataset
5. Handle Missing Values
6. Data Preprocessing
7. Feature Selection
8. Train-Test Split
9. Feature Scaling (where required)
10. Train Multiple Models
11. Evaluate Model Performance
12. Compare Models
13. Hyperparameter Tuning
14. Select Best Model
15. Save Trained Model
16. Predict Heart Disease Using User Input

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score

---

## 💾 Model Saving

The best-performing model is saved using **Joblib** for future predictions.

---

## 👨‍💻 User Prediction

The project allows users to enter their medical information through keyboard input.

The trained model predicts:

- Heart Disease: Yes or No
- Prediction Probability

---

## 📁 Project Structure

```
Heart-Disease-Prediction/
│
├── processed.cleveland.data
├── Heart_Disease_Prediction.ipynb
├── best_model.pkl
├── README.md
└── requirements.txt
```

---

## ▶ How to Run

1. Clone the repository.

```bash
git clone <repository-link>
```

2. Install the required libraries.

```bash
pip install pandas numpy matplotlib scikit-learn xgboost joblib
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all notebook cells.

5. Enter patient medical details when prompted.

6. View the prediction result.

---

## 📈 Future Improvements

- Develop a Flask or Streamlit web application.
- Improve model performance using advanced feature engineering.
- Perform cross-validation.
- Add more medical datasets for improved generalization.

---

## 📚 Dataset Source

UCI Machine Learning Repository

Heart Disease Dataset

---

## 👤 Author

**Muhammad Anees Jafar**

BS Computer Science

Machine Learning Enthusiast

GitHub: *(Add your GitHub profile link here)*

LinkedIn: *(Add your LinkedIn profile link here)*

---

## ⭐ If you found this project helpful, consider giving it a Star on GitHub.