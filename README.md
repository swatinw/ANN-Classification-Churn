# ANN-Classification-Churn

# 📉 Customer Churn Prediction App

An AI-powered web app that predicts the likelihood of a customer leaving a bank based on personal and transaction details. Built using a deep learning model and deployed with Streamlit.

---

## 🔗 Live Demo

👉 [Click here to try the Streamlit app](https://ann-classification-churn-jk6vmwxeashewstidkkmg7.streamlit.app/)

---

## 🔍 Overview

This project predicts **customer churn** using a trained **Artificial Neural Network (ANN)** model. The app processes user inputs like credit score, tenure, balance, and geography to determine the churn probability.

---

## 🚀 Features

- ✅ Real-time churn prediction with probabilities
- 🧠 Trained ANN model (.h5) using TensorFlow/Keras
- 📦 Streamlit web interface
- 🔐 Uses pre-saved label encoders and scalers
- 📂 Reads input data and displays clean UI

---

## 📁 Project Structure

```
├── app.py                      # Streamlit app
├── prediction.ipynb           # Model inference & preprocessing
├── Hyperparameter_prediction.ipynb # Tuning notebook
├── Churn_Modelling.csv        # Training dataset
├── model.h5                   # Trained ANN model
├── scaler.pkl                 # Feature scaler
├── label_encoder_gender.pkl   # Label encoder for gender
├── onehot_encoder_geo.pkl     # OneHotEncoder for geography
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation
```

---

## 📊 Input Features

- Credit Score
- Age
- Tenure
- Balance
- Num of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Geography
- Gender

---

## 🧠 Model Info

- **Type**: Artificial Neural Network (ANN)
- **Framework**: TensorFlow / Keras
- **Layers**: Input → Hidden (ReLU) → Output (Sigmoid)
- **Loss**: Binary Crossentropy
- **Optimizer**: Adam

---

## 📦 Installation

```bash
git clone https://github.com/your-username/customer-churn-predictor
cd customer-churn-predictor
pip install -r requirements.txt
streamlit run app.py
```

---

## 🛠 Tech Stack

- Python 3.11+
- Streamlit
- TensorFlow / Keras
- Scikit-learn
- Pandas, NumPy

---

## ✅ Future Improvements

- 🧪 Model explainability with SHAP
- 💾 Save predictions to database
- 📈 Monitor live inference performance
- 🌐 Deploy on Streamlit Cloud or Hugging Face Spaces

---

## 👤 Author

**Swati Sharma**  

🔗 [LinkedIn](https://www.linkedin.com/in/swati-sharma-17s50s01/)  
📂 [GitHub](https://github.com/swatinw)

---

📬 _Have ideas or feedback? Let's collaborate on impactful ML apps!_
