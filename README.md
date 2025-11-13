# ❤️ Heart Disease Prediction using Machine Learning

## 🧠 Project Overview  
This project focuses on predicting the likelihood of **cardiovascular disease** using **Machine Learning models**.  
The goal is to leverage patient health data to identify key risk factors and assist in early diagnosis through predictive modeling.

---

## 📊 Dataset  
- **Dataset Name:** `cardio_train.csv`  
- **Rows & Columns:** 70,000+ rows, 13 columns  
- **Target Variable:** `cardio` (1 = Disease, 0 = No Disease)  
- **Key Features:** Age, Gender, Height, Weight, Blood Pressure, Cholesterol, Glucose, Smoking, Alcohol, Physical Activity, etc.

---

## 🧩 Project Workflow  

### 1️⃣ Data Loading and Inspection  
- Loaded dataset into Pandas DataFrame  
- Checked dataset shape, missing values, and distribution of the target variable  

### 2️⃣ Feature Engineering  
- Converted **age (in days)** to **years (yr)** for better interpretability  
- Rounded and visualized feature distributions  

### 3️⃣ Exploratory Data Analysis (EDA)  
- Visualized relationships between gender, age, and heart disease  
- Checked correlation between numerical variables  
- Gained insights about key risk factors  

### 4️⃣ Data Preparation  
- Dropped unnecessary columns (`id`, `yr`)  
- Separated features (X) and target (y)  
- Split data into **training (80%)** and **testing (20%)** sets  

### 5️⃣ Model Building  
Implemented and compared two classification algorithms:
- **🌲 Random Forest Classifier** — Accuracy: **0.716**  
- **🌿 Decision Tree Classifier** — Accuracy: **0.631**  

### 6️⃣ Model Evaluation  
- Compared accuracy scores  
- Random Forest outperformed Decision Tree in predictive capability  

---

## 🧪 Technologies Used  
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  

---

## 🚀 Future Improvements  
- Apply Hyperparameter Tuning (GridSearchCV / RandomizedSearchCV)  
- Add more advanced models (XGBoost, LightGBM)  
- Deploy the model using Streamlit or Flask  

---

## 📚 Key Learnings  
- Practical application of **data preprocessing, EDA, and feature engineering**  
- Hands-on experience with **classification models**  
- Comparison of model performance metrics  

---

## 👨‍💻 Author  
**Md. Zahid Hasan Maruf**  
📍 RUET CSE'21 
📧 [jhmaruf750@gmail.com](mailto:jhmaruf750@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/jhmaruf750) 

---

⭐ *If you found this project helpful, don't forget to star the repository!*
