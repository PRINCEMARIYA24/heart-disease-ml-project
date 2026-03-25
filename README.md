# Heart Disease Prediction using Machine Learning

## 📌 Project Overview
This project predicts the likelihood of heart disease based on patient health data.  
The goal is to assist early diagnosis and support medical decision-making.

---

## 📊 Dataset
- Source: UCI Heart Disease Dataset
- Features include:
  - Age
  - Sex
  - Chest Pain Type
  - Cholesterol
  - Blood Pressure
  - Maximum Heart Rate

---

## ⚙️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## 🔍 Project Workflow
1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Model Training
5. Model Evaluation

---

## 🤖 Models Used
- Logistic Regression
- Decision Tree
- Random Forest

---

## 📈 Model Performance

| Model               | Accuracy |
|--------------------|----------|
| Logistic Regression| 82%      |
| Decision Tree      | 84%      |
| Random Forest      | 88%      |

---

## 💡 Key Insights
- Higher cholesterol increases heart disease risk
- Certain chest pain types strongly correlate with disease
- Age is a major contributing factor

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
python src/train_model.py
