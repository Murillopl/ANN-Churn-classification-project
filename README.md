# 🔍 Customer Churn Classification using ANN

This project is a deep learning application that uses an **Artificial Neural Network (ANN)** to predict **customer churn** — whether a customer is likely to cancel a service or not.

👉 **[Try the Live Demo](https://ann-classification-project-dfemyutmxhnieomcxikpah.streamlit.app/)**

---

## 📌 Project Overview

Churn prediction is critical for customer retention. In this project, a neural network model was built and trained to classify whether a customer will churn or stay, based on key features in the dataset.

### Objectives:
- Build a classification model using an ANN.
- Analyze and preprocess the dataset.
- Evaluate model performance using standard classification metrics.
- Deploy the model using Streamlit.

---

## 🧠 Model Architecture

- **Input Layer:** Normalized customer features (e.g. tenure, CreditScore, Balance, EstimatedSalary, etc.)
- **Hidden Layers:** Fully connected layers with ReLU activation.
- **Output Layer:** Sigmoid activation for binary classification (churn or not).

---

## 🧪 Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas / NumPy 
- Streamlit (for deployment)

---

## 📊 Dataset

A churn dataset was used containing customer-related information, such as:
- Balance
- Credit Score
- Tenure
- Estimated Salary
- Whether the customer has churned (target variable)

---

## 🚀 How to Run Locally

1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

---

## 📈 Model Evaluation

The model was evaluated using:
- Accuracy

The ANN achieved good performance in identifying customers who are at risk of churning.

---

## 🌐 Live Demo

Check out the live version here:  
🔗 [https://ann-classification-project-dfemyutmxhnieomcxikpah.streamlit.app/](https://ann-classification-project-dfemyutmxhnieomcxikpah.streamlit.app/)

---

## 📬 Contact

If you have any questions or feedback, feel free to reach out!
