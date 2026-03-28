# 🐱🐶 Cats vs Dogs Classification using CNN

## 👩‍💻 Author
**Varshini**

---

## 🎯 Objective

To build a **Convolutional Neural Network (CNN)** model that classifies images as **cat 🐱 or dog 🐶** using the CIFAR-10 dataset, and extend the approach to **multi-class image classification**.

---

## 📚 Project Overview

This project implements deep learning models using **TensorFlow/Keras** for image classification tasks:

- 🔹 Binary Classification (Cat vs Dog)  
- 🔹 Multi-Class Classification (CIFAR-10 – 10 classes)  

The dataset used is **CIFAR-10**, which contains 60,000 32x32 color images across 10 categories.

---

## ⚙️ Workflow

- 📥 Load dataset using TensorFlow  
- 🔍 Filter dataset for cat & dog classes (binary classification)  
- 🧹 Data preprocessing (normalization, splitting)  
- 🧠 CNN model building  
- ⚙️ Model training and validation  
- 📊 Performance evaluation  
- 🔁 Extend to multi-class classification  

---

## 🧠 Model Architecture

### 🔹 Binary Classification Model

- Conv2D (32 filters) + ReLU  
- MaxPooling  
- Dropout  
- Conv2D (64 filters) + ReLU  
- MaxPooling  
- Dropout  
- Flatten  
- Dense (128) + ReLU  
- Dropout  
- Output layer (Sigmoid)  

---

### 🔹 Multi-Class Classification Model

- Multiple Conv2D layers (32, 64 filters)  
- MaxPooling layers  
- Dropout for regularization  
- Dense (512 neurons)  
- Output layer (Softmax – 10 classes)  

---

```## 🗂️ Project Structure
Cats-vs-Dogs-Classification-using-CNN/
├── Cats_vs_Dogs_Classification_using_CNN.ipynb # Main notebook
└── README.md # Documentation```


---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:**  
  - TensorFlow / Keras  
  - NumPy  
  - Matplotlib  
  - Scikit-learn  

---

## 📊 Results

### 🔹 Binary Classification (Cat vs Dog)
- ✅ Test Accuracy: **~75%**  

### 🔹 Multi-Class Classification (CIFAR-10)
- ✅ Test Accuracy: **~77.9%**  

---

## 📈 Outputs

- Training & validation accuracy graphs  
- Loss curves  
- Predictions on sample images  
- Visualization of model performance  

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/bvsvarshini/Cats-vs-Dogs-Classification-using-CNN.git
