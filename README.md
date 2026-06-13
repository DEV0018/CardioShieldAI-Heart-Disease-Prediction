# CardioShieldAI-Heart-Disease-Prediction
Machine Learning-based Heart Disease Prediction System using Python and Streamlit with real-time prediction and a responsive healthcare dashboard.
# ❤️ CardioShield AI - Heart Disease Prediction System

An intelligent **Machine Learning-based Heart Disease Prediction System** built using **Python, Scikit-Learn, and Streamlit**. The application predicts the likelihood of heart disease based on patient health parameters and provides real-time results through an interactive clinical dashboard.

---

## 🚀 Features

* 📊 Machine Learning-based heart disease prediction
* 🩺 Clinical dashboard with responsive UI
* ⚡ Real-time prediction using a trained model
* 🔄 Data preprocessing and feature scaling
* 💾 Model serialization using Pickle
* 🌐 Streamlit web application
* 📈 User-friendly healthcare interface
* ☁️ Ready for deployment on Streamlit Cloud

---

## 🧠 Machine Learning Workflow

```text
Dataset Collection
        ↓
Data Preprocessing
        ↓
Feature Selection
        ↓
Feature Scaling
        ↓
Model Training
        ↓
Model Evaluation
        ↓
Model Serialization
        ↓
Streamlit Deployment
```

---

## 📂 Project Structure

```bash
heart-disease-prediction/
│
├── app.py                         # Streamlit application
├── train_model.py                 # Model training script
├── heart_model.pkl                # Trained machine learning model
├── scaler.pkl                     # StandardScaler object
├── heart disease dataset.xlsx     # Dataset
├── inspect_data.py                # Dataset inspection
├── inspect_encoding.py            # Encoding analysis
├── inspect_values.py              # Value analysis
├── requirements.txt               # Dependencies
├── README.md                      # Project documentation
└── CardioShield_AI_Clinical_Report.pdf
```

---

## 📋 Dataset Features

The model uses the following medical parameters:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* Oldpeak
* ST Slope

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-Learn
* Streamlit
* Pickle
* OpenPyXL

### Tools

* VS Code
* Git
* GitHub

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

---

## 📊 Prediction Pipeline

1. User enters medical parameters.
2. Input data is preprocessed.
3. Features are scaled using StandardScaler.
4. The trained machine learning model is loaded.
5. Heart disease prediction is generated.
6. Results are displayed through the Streamlit dashboard.

---

## 📸 Screenshots

### Home Page

(Add screenshot here)

### Prediction Dashboard

(Add screenshot here)

### Output Page

(Add screenshot here)

---

## 📈 Future Enhancements

* Explainable AI using SHAP
* Multiple model comparison
* Random Forest and XGBoost integration
* Hyperparameter tuning
* Confusion matrix visualization
* Prediction history
* User authentication
* PDF report generation
* Database integration with MongoDB
* Docker support
* FastAPI backend
* Cloud deployment using AWS or Azure

---

## 🎯 Applications

* Healthcare Analytics
* Disease Risk Prediction
* Clinical Decision Support Systems
* Preventive Healthcare
* Medical Research
* AI-Assisted Diagnosis

---

## 📚 References

* Scikit-Learn Documentation
* Streamlit Documentation
* Pandas Documentation
* NumPy Documentation
* Python Documentation

---

## 👨‍💻 Author

### Devaraj

**B.E. Artificial Intelligence and Machine Learning**
**B.M.S College of Engineering**

---

## ⭐ If you found this project useful, consider giving it a star!
