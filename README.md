# 🧠 MNIST Handwritten Digit Classification using Neural Network

## 📌 Project Overview
This project implements a Deep Learning model to classify handwritten digits (0–9) using the MNIST dataset. The model is built using TensorFlow/Keras and achieves around 98% accuracy on the test dataset.

---

## 📂 Dataset
- Dataset: MNIST
- Training samples: 60,000
- Testing samples: 10,000
- Image size: 28 × 28 (grayscale)
- Classes: 10 (digits 0–9)

---

## ⚙️ Technologies Used
- Python  
- NumPy  
- TensorFlow / Keras  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- PIL  

---

## 🏗️ Model Architecture
A simple Artificial Neural Network (ANN):

- Dense Layer: 512 neurons (ReLU)
- Output Layer: 10 neurons (Softmax)

```python
model = models.Sequential([
    layers.Dense(512, activation='relu'),
    layers.Dense(10, activation='softmax')
])
