# Iris Neural Network Classification – Overfitting Control & Model Evaluation

This project implements a **Neural Network classifier using TensorFlow/Keras** on the **Iris dataset**.  
The main focus is controlling **overfitting** and properly evaluating model performance.

---

## 📌 Project Overview

- Dataset: Iris (4 input features, 3 output classes)
- Framework: TensorFlow / Keras
- Goal: Build a neural network classifier and reduce overfitting using proper techniques.

---

## 🧠 Workflow

### 1️⃣ Data Loading
- Loaded Iris dataset using `sklearn.datasets`
- 4 numerical input features
- 3 target classes

---

### 2️⃣ Preprocessing
- Train / Validation / Test split
- Feature scaling using `StandardScaler`
- Prepared data for neural network training

---

### 3️⃣ Neural Network Architecture

- Input layer (4 features)
- Dense hidden layer (ReLU activation)
- **L2 Regularization**
- **Dropout (0.3)** to reduce overfitting
- Output layer (3 neurons, multi-class classification)

---

### 4️⃣ Overfitting Prevention Techniques

- ✅ L2 Regularization
- ✅ Dropout Layer
- ✅ Early Stopping (monitoring validation loss)
- ✅ Feature Scaling
- ✅ Validation Set Monitoring

These techniques were applied because the model was initially overfitting.

---

## 📊 Evaluation Metrics

- Accuracy (Test & Validation)
- F1-Score
- Comparison between validation and test performance
