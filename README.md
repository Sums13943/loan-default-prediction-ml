# 🏦 Loan Default Prediction using Machine Learning

This project uses a machine learning model to predict whether a loan applicant is likely to default, based on features such as income, education, credit history, and loan amount.

> ✅ Built as a portfolio project to demonstrate end-to-end skills in data science, ML model development, and evaluation.

---

## 📌 Problem Statement

Financial institutions face significant risk due to loan defaults. Early prediction of high-risk applicants helps minimize losses. This model uses structured loan application data to classify applicants as likely to default (`1`) or not (`0`).

---

## 🛠️ Tools & Technologies Used

- **Python** – Core language
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-Learn** – Model training and evaluation
- **Random Forest Classifier** – Chosen algorithm
- **Jupyter Notebook / Google Colab** – Development environment
- **Joblib** – Model serialization

---

## 📂 Dataset

A synthetic dataset was generated for this demo. Each record represents a loan applicant, with fields such as:

- `applicant_income`
- `education`
- `credit_history`
- `loan_amount`
- `loan_default` (target variable)

---

## 🔍 Project Workflow

1. **Data Generation** – Created a realistic synthetic dataset.
2. **Exploratory Data Analysis (EDA)** – Inspected structure, checked missing values, and visualized distributions.
3. **Preprocessing** – Encoded categorical features and dropped irrelevant columns.
4. **Model Training** – Used a `RandomForestClassifier` for classification.
5. **Evaluation** – Metrics included Accuracy, Precision, Recall, Confusion Matrix, and ROC-AUC Curve.
6. **Feature Importance** – Ranked features contributing most to the prediction.
7. **Model Export** – Trained model was saved as a `.pkl` file for reuse.

---

## 📈 Key Results

- Achieved high accuracy on the test set
- ROC-AUC score demonstrates strong model performance
- Identified top contributing features (like income & credit history)

---

## 🧠 Skills Demonstrated

- End-to-end ML pipeline (EDA → Model → Evaluation)
- Real-world problem framing
- Handling of categorical and numerical features
- Interpretation of ML outputs (Confusion matrix, ROC curve)
- Saving and reloading models for deployment

---

## 🚀 Future Enhancements

- Improve model using hyperparameter tuning
- Add Streamlit or Flask interface for real-time predictions
- Integrate with real bank loan datasets (Kaggle, open APIs)
- Convert into a microservice or REST API
