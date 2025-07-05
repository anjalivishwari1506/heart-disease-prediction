# 💓 Heart Disease Prediction Model using Machine Learning and Flask

A web-based machine learning application that predicts the likelihood of heart disease in individuals based on clinical data. Built using the **Random Forest algorithm** and deployed via a **Flask web interface**, this project also features an interactive dashboard built with **HTML, CSS, JavaScript**, and **Chart.js**.

---

## 📌 Project Overview

This application allows users to input health-related information such as age, sex, cholesterol level, blood pressure, and more. It uses a trained Random Forest Classifier model to predict the presence of heart disease. The results are displayed on a dynamic dashboard with graphical visualizations and interpretation of input data.

---

## ⚙️ Tech Stack

- **Backend Framework:** Python (Flask)
- **Machine Learning Algorithm:** Random Forest Classifier
- **Frontend:** HTML5, CSS3, JavaScript (Chart.js)
- **Data Source:** [Kaggle - UCI Heart Disease Dataset](https://www.kaggle.com/ronitf/heart-disease-uci)
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, joblib

---

## 🔍 Key Features

### 🧾 User Input Form
- Collects patient data such as age, sex, chest pain type, cholesterol, fasting blood sugar, etc.
- HTML form with validation.

### 🔢 Prediction Logic
- Model is trained on Kaggle UCI dataset.
- Uses `joblib` to load and apply the Random Forest model.
- Predicts if the patient has heart disease or not.

### 📊 Dashboard & Report
- Tabular summary of input data.
- Prediction result (Disease / No Disease).
- Probability score of classification.
- Visualizations (e.g., cholesterol vs. age) using Chart.js.

### 📈 Data Visualization
- Includes bar charts, pie charts, and dynamic graphs.
- Helps understand which features contribute to the model prediction.

---

## 🧠 Machine Learning Workflow

1. **Data Collection**
   - Kaggle UCI Heart Disease dataset (14 attributes, 300+ rows)

2. **Preprocessing**
   - Handled missing values, encoded categorical variables, scaled numeric features.

3. **Model Training**
   - Random Forest Classifier optimized using GridSearchCV.
   - Data split into train/test sets with cross-validation.

4. **Model Evaluation**
   - Evaluated with accuracy, precision, recall, F1-score, and confusion matrix.

5. **Deployment**
   - Model served through Flask API.
   - Frontend collects user input → backend predicts → frontend displays result.

---

## 🖥️ Application Flow

1. **Home Page:** Brief intro about the model.
2. **Input Form:** Collects user health data.
3. **Prediction Page:** Shows prediction and dashboard.
4. **Dashboard:** Graphical visualization of results and key features.

---

## 📂 Project Structure

heart-disease-prediction/
├── app.py
├── templates/
│ ├── index.html
│ ├── form.html
│ └── result.html
├── static/
│ ├── css/
│ └── js/
├── model/
│ └── random_forest_model.pkl
├── dataset/
│ └── heart.csv
└── README.md

---
# screenshots 
![image](https://github.com/user-attachments/assets/a247736c-0f9c-4d4b-8ce5-65e4ec1f46d8)
![image](https://github.com/user-attachments/assets/080d8532-a474-4163-aff0-741673a0913a)

## ✅ Future Enhancements

- User authentication system to store past predictions.
- Integration with wearable APIs for real-time health data.
- Add SHAP or LIME for model explainability.
- Make the app fully mobile responsive (PWA).
- Export predictions as PDF reports.

---

## 🚀 Getting Started

### 🔧 Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/heart-disease-prediction.git

# Navigate into the project directory
cd heart-disease-prediction

# Install required dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

### 🙋‍♀️ About the Author
### Anjali Vishwari
MCA Student | AI & ML Enthusiast
📫 Email: anjalivishwari@gmail.com
🔗 LinkedIn: linkedin.com/in/anjalivishwari

