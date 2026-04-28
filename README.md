# 💳 Credit Risk Prediction

A Machine Learning project that predicts whether a loan applicant is **high risk (Bad)** or **low risk (Good)** based on financial and personal details.

This project includes a **Streamlit web application** for real-time credit risk prediction.

---

## 🚀 Project Overview

Credit risk prediction helps financial institutions decide whether to approve or reject a loan application.

This project uses multiple machine learning models to classify applicants into:
- ✅ Good Credit Risk  
- ❌ Bad Credit Risk  

---

## 📁 Dataset

- File: `german_credit_data.csv`

### Features:
- Age  
- Sex  
- Job  
- Housing  
- Saving accounts  
- Checking account  
- Credit amount  
- Duration  

### Target:
- Credit Risk (Good / Bad)

---

## ⚙️ Workflow

1. Data Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Encoding Categorical Variables  
4. Feature Engineering  
5. Model Training  
6. Model Evaluation  
7. Model Selection  
8. Deployment using Streamlit  

---

## 🤖 Models Used

- Decision Tree  
- Random Forest  
- Extra Trees  
- XGBoost  

---

## 📈 Model Performance

| Model          | Accuracy |
|---------------|----------|
| XGBoost       | **0.676** |
| Extra Trees   | 0.648    |
| Random Forest | 0.619    |
| Decision Tree | 0.581    |

✅ **Best Model: XGBoost**

---

## 🧠 Key Insights

- Tree-based ensemble models perform better than simple models  
- XGBoost achieved the highest accuracy  
- Financial indicators like credit amount and duration play a key role  
- Account balance features significantly impact risk prediction  

---

## 💻 Streamlit App

This project includes a user-friendly web app where users can:

- Enter applicant details  
- Predict credit risk instantly  

---

## ▶️ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/credit-risk-prediction.git
cd credit-risk-prediction
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the App
```bash
streamlit run app.py
```

---

## 📦 Required Files

- `app.py`  
- `german_credit_data.csv`  
- `xgboost_credit_risk.pkl`  
- `Sex_encoder.pkl`  
- `Housing_encoder.pkl`  
- `Saving accounts_encoder.pkl`  
- `Checking account_encoder.pkl`  

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- XGBoost  
- Streamlit  

---

## 📌 Future Improvements

- Improve model accuracy with hyperparameter tuning  
- Add more financial features  
- Deploy the app on cloud  
- Add explainability (SHAP / LIME)  

---

## 👨‍💻 Author

**Ram Vilas**  
Data Science Enthusiast  

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
