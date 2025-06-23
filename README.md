# Disease Diagnosis Prediction

This project builds machine learning models to predict the likelihood of diseases such as **diabetes** or **heart disease** based on clinical features. The goal is to aid healthcare professionals in **early diagnosis** and **preventive care**.

---

## 📁 Dataset

We used publicly available datasets:
- **PIMA Indians Diabetes Dataset** ([Download CSV](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database))
- **Heart Disease Dataset** ([Download CSV](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci))

Each dataset contains patient records with features such as glucose level, BMI, blood pressure, age, etc., and a target label indicating disease presence.

---

## 📊 Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Visualized feature distributions
- Correlation analysis
- Checked for missing values and outliers

### 2. Data Preprocessing
- Feature scaling using `StandardScaler`
- Feature selection using `SelectKBest`
- Train-test split (80/20)

### 3. Model Training
Implemented and compared the following models:
- 🟢 Gradient Boosting Classifier
- 🔵 Support Vector Machine (SVM)
- 🟣 Neural Network (MLPClassifier)

### 4. Model Evaluation
Evaluated models using:
- ✅ F1 Score
- 📈 AUC-ROC Curves
- 📊 Confusion Matrix

### 5. Manual Prediction Support
- Enter patient data manually to get predictions
- `joblib` is used to load saved models and scalers

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/disease-diagnosis-prediction.git
   cd disease-diagnosis-prediction
