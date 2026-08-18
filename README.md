# ❤️ Heart Disease Prediction – Machine Learning Project  
### BITS Pilani – Assignment 2  
Submitted by: PALADI S G VENKATA VIJAY

📌 Project Overview  
This project builds a Machine Learning system to predict Heart Disease using the UCI Heart Dataset.

It includes:

✔ Data preprocessing & feature engineering

✔ Training 6 ML models

✔ Computing all evaluation metrics

✔ Saving models as .pkl

✔ Streamlit app for prediction & model comparison

✔ 3D visualization

✔ Clean UI with dark mode

## 📂 Project Structure

Assignment 2/
│── heart.csv
│── test.ipynb # Model training + metrics + saving models
│── heart_app.py # Streamlit application
│── model_metrics.json # Saved performance metrics
│── Logistic_Regression.pkl
│── Decision_Tree.pkl
│── Random_Forest.pkl
│── XGBoost.pkl
│── KNN.pkl
│── Naive_Bayes.pkl
│── scaler.pkl
│── feature_names.pkl
│── requirements.txt
│── ML_Assignment_2.pdf # Assignment document
│── README.md



## 🚀 How the Project Works

### 1️⃣ Model Training — `test.ipynb`
This notebook performs:

✔️ Load & clean data  
✔️ Train-Test Split  
✔️ Train 6 ML Models  
- Logistic Regression  
- Decision Tree  
- KNN  
- Naive Bayes  
- Random Forest  
- XGBoost  

✔️ Compute all metrics:  
- Accuracy  
- ROC-AUC  
- Precision  
- Recall  
- F1 Score  
- MCC  

✔️ Save outputs:  
- All trained models → `.pkl`  
- Scaler → `scaler.pkl`  
- Feature Names → `feature_names.pkl`  
- Metrics → `model_metrics.json`

---

## 🖥️ 2️⃣ Streamlit App — `heart_app.py`

Features included:

### 🔮 Prediction Module
- User inputs patient data  
- Data is preprocessed using saved scaler  
- Best model (XGBoost) predicts the risk  
- Shows:
  - ⚠️ High Risk (red)
  - ✅ Low Risk (green)

---

### 📊 Model Comparison Dashboard
Includes:

Performance table

Accuracy bar graph

ROC-AUC bar graph

Radar chart

3D scatter plot (Age vs Cholesterol vs MaxHR)

### 🌙 UI Enhancements
Dark mode toggle

Custom CSS

Sidebar navigation

Modern visualization

## ▶️ How to Run the Streamlit App

### Install Dependencies

pip install -r requirements.txt



### Run App

streamlit run heart_app.py



---

## 📈 Results Summary

| Model               | Accuracy | ROC_AUC | Precision | Recall | F1 Score | MCC    |
| ------------------- | -------- | ------- | --------- | ------ | -------- | ------ |
| Logistic Regression | 0.8859   | 0.8803  | 0.8716    | 0.9314 | 0.9005   | 0.7694 |
| Decision Tree       | 0.7772   | 0.7715  | 0.7850    | 0.8235 | 0.8038   | 0.5471 |
| KNN                 | 0.8859   | 0.8827  | 0.8857    | 0.9118 | 0.8986   | 0.7686 |
| Naive Bayes         | 0.9130   | 0.9131  | 0.9300    | 0.9117 | 0.9208   | 0.8246 |
| Random Forest       | 0.8913   | 0.8888  | 0.8942    | 0.9117 | 0.9029   | 0.7797 |
| XGBoost             | 0.8588   | 0.8570  | 0.8725    | 0.8725 | 0.8725   | 0.7140 |


## 📦 Requirements  
All dependencies are listed in `requirements.txt`.

---

## 📚 How to Use in BITS Lab

1. Upload:
   - `heart_app.py`
   - All `.pkl` model files  
   - `model_metrics.json`
   - `heart.csv`
   - `requirements.txt`

2. Install dependencies using:

pip install -r requirements.txt


3. Run Streamlit:

streamlit run heart_app.py


4. Demonstrate:
   - Prediction Page  
   - Model Comparison Dashboard  
   - 3D Visualization  
   - Accuracy/ROC-AUC graphs  
   - Radar Chart  

5. Submit all files along with:
   - PDF report (from assignment)
   - Screenshots of outputs

---

## 📝 Author  
Paladi S G Venkata Vijay
BITS Pilani – WILP  






