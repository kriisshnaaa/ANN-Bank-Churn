# 🏦 Customer Churn Prediction using ANN

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=28&duration=3000&pause=1000&color=00C853&center=true&vCenter=true&width=800&lines=Customer+Churn+Prediction;Artificial+Neural+Network+(ANN);TensorFlow+%7C+Streamlit+%7C+Scikit-Learn;Machine+Learning+Deployment+Project" />

<br>

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge\&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-ANN-orange?style=for-the-badge\&logo=tensorflow)
![Streamlit](https://img.shields.io/badge/Streamlit-Deployed-red?style=for-the-badge\&logo=streamlit)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-yellow?style=for-the-badge\&logo=scikitlearn)

</div>
<div align="center">

<a href="https://bankchurnclassifiation.streamlit.app/">
    <img src="https://img.shields.io/badge/🚀_Live_Demo-Open_App-success?style=for-the-badge">
</a>

</div>
---

## 🚀 Project Overview

Predict whether a customer is likely to leave a bank using an Artificial Neural Network trained on customer demographic and banking information.

### 🎯 Goal

Banks lose customers every day.

This project helps identify customers who are likely to leave the bank so that retention strategies can be applied proactively.

---

## ✨ Features

✅ Customer Churn Prediction

✅ Artificial Neural Network (ANN)

✅ TensorFlow/Keras Implementation

✅ Data Preprocessing Pipeline

✅ Feature Scaling

✅ One-Hot Encoding

✅ Label Encoding

✅ Streamlit Web Application

✅ Real-Time Predictions

---

## 🧠 ANN Architecture

```text
Input Layer (12 Features)
        │
        ▼
Dense Layer (64 Neurons, ReLU)
        │
        ▼
Dense Layer (32 Neurons, ReLU)
        │
        ▼
Dense Layer (1 Neuron, Sigmoid)
        │
        ▼
Churn Probability
```

---

## 📊 Model Performance

| Metric              | Score               |
| ------------------- | ------------------- |
| Training Accuracy   | ~86%                |
| Validation Accuracy | ~85-86%             |
| Optimizer           | Adam                |
| Loss Function       | Binary Crossentropy |

---

## ⚙️ Technologies Used

| Technology   | Purpose               |
| ------------ | --------------------- |
| Python       | Programming Language  |
| TensorFlow   | ANN Development       |
| Scikit-Learn | Preprocessing         |
| Pandas       | Data Handling         |
| NumPy        | Numerical Computation |
| Streamlit    | Deployment            |

---

## 📸 Application Preview

<p align="center">
  <img width="1258" height="800" alt="image" src="https://github.com/user-attachments/assets/8657260e-cb9d-4c4a-a272-a24ee7320865" />

</p>

---

## 🔄 Machine Learning Workflow

```text
Raw Dataset
     │
     ▼
Data Cleaning
     │
     ▼
Label Encoding
     │
     ▼
One Hot Encoding
     │
     ▼
Feature Scaling
     │
     ▼
Train Test Split
     │
     ▼
ANN Training
     │
     ▼
Model Saving
     │
     ▼
Streamlit Deployment
```

---

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/customer-churn-prediction.git

cd customer-churn-prediction

pip install -r requirements.txt

streamlit run app.py
```

---

<details>

<summary>📂 Project Structure</summary>

```text
Customer-Churn-Prediction
│
├── app.py
├── model.h5
├── scaler.pickle
├── label_encoder_gender.pkl
├── onehot_encoder_geo.pkl
├── requirements.txt
├── README.md
│
└── notebooks
    └── experiments.ipynb
```

</details>

---

## 🎯 Example Prediction

### Input

```text
Credit Score      : 600
Geography         : France
Gender            : Male
Age               : 40
Balance           : 60000
Tenure            : 3
Products          : 2
Active Member     : Yes
```

### Output

```text
Churn Probability : 0.82

Customer is likely to churn.
```

---

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a star ⭐

Made with ❤️ using TensorFlow & Streamlit

</div>
