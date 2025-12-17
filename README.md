# ❤️ Heart Disease Prediction Project
The project covers:

* Data collection from Kaggle
* Data cleaning & preprocessing
* Exploratory Data Analysis (EDA)
* Model training (Logistic Regression & Random Forest)
* Model evaluation
* Feature importance analysis
* Model saving
* User data upload & prediction

---

## 📂 Dataset

* **Source:** Kaggle – UCI Heart Disease Dataset
* **Dataset Name:** `heart_disease_uci.csv`

The target column:

* `num` → Indicates heart disease severity
* Converted to binary:

  * `0` → No Heart Disease
  * `1` → Heart Disease Present

---

## 🛠️ Technologies Used

* **Python**
* **Google Colab**
* **Libraries:**

  * pandas
  * numpy
  * matplotlib
  * seaborn
  * scikit-learn
  * joblib

---

## 🚀 Project Workflow

### 🔹 Day 1: Data Setup

* Upload Kaggle API key (`kaggle.json`)
* Download dataset from Kaggle
* Load dataset using pandas

### 🔹 Day 2: Data Exploration & Preprocessing

* View dataset structure and columns
* Handle missing values:

  * Numeric → Mean imputation
* Visualizations:

  * Histograms for numeric features
  * Correlation heatmap

### 🔹 Day 3: Feature Engineering & Model Training

* Separate features (X) and target (y)
* One-hot encode categorical variables
* Train-test split (80-20)
* Feature scaling using `StandardScaler`
* Train **Logistic Regression** model

### 🔹 Day 4: Advanced Model & Evaluation

* Evaluate Logistic Regression:

  * Accuracy
  * Classification Report
  * Confusion Matrix
* Train **Random Forest Classifier**
* Compare accuracy
* Plot **Feature Importance**

### 🔹 Day 5: Model Saving & User Prediction

* Save trained model and scaler using `joblib`
* Create a user input template CSV
* Upload user dataset
* Preprocess user data
* Align features with training data
* Predict heart disease outcome

---

## 📊 Models Used

### 1️⃣ Logistic Regression

* Baseline model
* Used with scaled features

### 2️⃣ Random Forest Classifier

* Improved accuracy
* Provides feature importance
* Final model saved for predictions

---

## 📈 Model Evaluation Metrics

* Accuracy Score
* Precision, Recall, F1-score
* Confusion Matrix Visualization

**Note:**

* Accuracy between **75% – 98%** is considered good

---

## 💾 Saved Files

* `heart_rf_model.pkl` → Trained Random Forest model
* `heart_scaler.pkl` → StandardScaler object
* `Heart_user_template.csv` → Sample input format for users

---

## 👤 User Prediction Steps

1. Upload `heart_dataset.csv`
2. System preprocesses data automatically
3. Model predicts heart disease
4. Output column added:

   * `Heart_Disease_Prediction`

---

## 📌 How to Run

1. Open the notebook in **Google Colab**
2. Upload `kaggle.json`
3. Run cells sequentially
4. Upload user CSV for prediction

---

## ✅ Final Output

The final output is a dataframe showing:

* User input features
* Predicted heart disease result (0 or 1)

---

## 📚 Learning Outcomes

* Real-world ML pipeline implementation
* Handling missing data
* Feature encoding & scaling
* Model comparison
* Model persistence
* User-based predictions

---

## ✨ Author
VELPURU NIHITHA
**Heart Disease Prediction – ML Project**
Built for learning and academic purposes
