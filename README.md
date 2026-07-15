# Breast Cancer Classification using Feedforward Neural Network (FFNN)
# 📌 Project Overview

This project implements a **Feedforward Neural Network (FFNN)** for the classification of breast cancer tumors as **Benign** or **Malignant** using the **Breast Cancer Wisconsin Diagnostic Dataset**.

The model was designed and trained using **TensorFlow/Keras** in a **Kaggle Notebook** environment. Various deep learning techniques such as **Batch Normalization**, **Dropout**, and **Early Stopping** were incorporated to improve model performance and reduce overfitting.

## 🎯 Objectives

- Build a Feedforward Neural Network (FFNN)
- Perform binary classification of breast cancer tumors
- Compare different optimizers and loss functions
- Improve model generalization using regularization techniques
- Evaluate model performance using standard classification metrics

## 📂 Dataset

**Breast Cancer Wisconsin (Diagnostic) Dataset**

- Total Samples: 569
- Features: 30
- Classes:
  - Malignant (M)
  - Benign (B)

Dataset Source:

https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

## 🛠 Development Environment

This project was developed using:

- Kaggle Notebook
- Python 3
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

GPU acceleration available through Kaggle was used during model training.

## 🧠 Neural Network Architecture

The FFNN architecture consists of:

- Input Layer
- Hidden Layers with ReLU Activation
- Batch Normalization
- Dropout Layers
- Output Layer with Sigmoid Activation

The architecture diagram is available in:

```
nn.svg
```

---

## 📊 Model Features

The implementation includes:

- Feedforward Neural Network
- Data Preprocessing
- Feature Scaling
- Train-Test Split
- Batch Normalization
- Dropout Regularization
- Early Stopping
- SGD Optimizer
- Adam Optimizer
- Binary Cross-Entropy Loss
- Mean Squared Error Loss

---

## 📈 Performance Metrics

The trained model was evaluated using:

- Accuracy
- Precision
- Recall (Sensitivity)
- Specificity
- F1-Score
- ROC-AUC Score
- Confusion Matrix

Example Results

| Metric | Value |
|---------|-------|
| Accuracy | 93.86% |
| Precision | 92.68% |
| Recall | 90.48% |
| Specificity | 95.83% |
| F1-Score | 91.57% |
| ROC-AUC | 98.71% |

---

## 📁 Repository Structure

```
kaggle/
│
├── assignment1-dl.ipynb
├── nn.svg
├── README.md
```

---

## ▶️ How to Run

1. Clone the repository

```bash
git clone https://github.com/chellurujyothiradhitya-crypto/kaggle.git
```

2. Open the notebook

```
assignment1-dl.ipynb
```

3. Install required libraries

```bash
pip install tensorflow kaggle pandas numpy matplotlib scikit-learn
```

4. Run all notebook cells sequentially.

---

## 📚 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Kaggle Notebook

---

## 📖 Learning Outcomes

Through this project, the following concepts were implemented and analyzed:

- Feedforward Neural Networks
- Binary Classification
- Deep Learning Model Design
- Hyperparameter Tuning
- Batch Normalization
- Dropout Regularization
- Early Stopping
- Optimizer Comparison
- Loss Function Comparison
- Performance Evaluation

---

## 👨‍💻 Author

**ch JYOTHIRADHITYA**

