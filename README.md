<h1 align="center">📉 Customer Churn Prediction using Artificial Neural Networks (ANN)</h1>

<p align="center">
  <i>Predicting customer churn to help businesses retain valuable clients using AI-driven insights.</i>
</p>

---

## 🧩 Project Overview

Customer churn is one of the biggest challenges faced by businesses, especially those that rely on recurring revenue models.  
This project leverages **Artificial Neural Networks (ANNs)** to analyze patterns in customer behavior and predict whether a customer is likely to **churn (leave)** or **stay**.

By identifying high-risk customers early, companies can take **data-driven actions** to enhance retention and improve profitability.

---

## 📂 Dataset Description

The dataset is based on customer banking data, containing demographic, account, and transactional details.

| Feature | Description |
|----------|-------------|
| **CreditScore** | Customer’s credit score |
| **Geography** | Country or region |
| **Gender** | Male / Female |
| **Age** | Customer’s age |
| **Tenure** | Years as a customer |
| **Balance** | Account balance |
| **NumOfProducts** | Number of bank products owned |
| **HasCrCard** | Has a credit card (1 = Yes, 0 = No) |
| **IsActiveMember** | Is an active member (1 = Yes, 0 = No) |
| **EstimatedSalary** | Estimated salary |
| **Exited** | Target variable — 1 if churned, 0 otherwise |

---

## ⚙️ Model Architecture

The project implements a **Feedforward Artificial Neural Network (ANN)** using **TensorFlow** and **Keras**.

**Model Details:**
- **Input Layer:** 11 features  
- **Hidden Layers:** 2 dense layers with *ReLU* activation  
- **Output Layer:** 1 neuron with *Sigmoid* activation  
- **Optimizer:** Adam  
- **Loss Function:** Binary Crossentropy  
- **Evaluation Metric:** Accuracy  

The model effectively distinguishes between churned and retained customers.

---

## 🧰 Tech Stack

| Category | Tools & Libraries |
|-----------|------------------|
| **Language** | Python |
| **Frameworks** | TensorFlow, Keras |
| **Libraries** | NumPy, Pandas, Matplotlib, Scikit-learn |
| **Deployment (optional)** | Streamlit / Flask |
| **Environment** | Jupyter Notebook, VS Code |

---

