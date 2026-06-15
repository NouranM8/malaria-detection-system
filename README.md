# Malaria Detection System (AI & Deep Learning)

## 📌 Overview
This project is a deep learning-based system for detecting malaria from blood smear images using Convolutional Neural Networks (CNN).  
The system classifies different malaria parasite types from microscopic images and provides automated prediction with a user-friendly interface.

---

## 🧠 Problem Statement
Malaria diagnosis using traditional microscopic methods is time-consuming, labor-intensive, and prone to human error.  
This project aims to automate malaria detection using AI to improve speed, accuracy, and accessibility.

---

## ⚙️ Tech Stack
- Python  
- TensorFlow / Keras  
- Convolutional Neural Networks (CNN)  
- NumPy  
- Matplotlib  
- Scikit-learn  
- Tkinter (GUI)  

---

## 📊 Dataset
- Blood smear microscopic images dataset  
- Classes:
  - Falciparum  
  - Malariae  
  - Ovale  
  - Vivax  

---

## 🚀 Features
- Image preprocessing and normalization  
- Data augmentation (rotation, flipping, zooming)  
- CNN-based deep learning model  
- Class imbalance handling using class weights  
- Model evaluation using confusion matrix & classification report  
- Real-time image prediction using GUI (Tkinter)  

---

## 🧠 Model Architecture
- Convolutional Layers for feature extraction  
- Max Pooling layers for dimensionality reduction  
- Dense layers for classification  
- Dropout + L2 regularization to reduce overfitting  
- Softmax activation for multi-class output  

---

## 📈 Results
- Achieved ~84% accuracy on test dataset  
- Evaluated using:
  - Confusion Matrix  
  - Precision / Recall / F1-score  

---

## 💻 How to Run
### 1️⃣ Install dependencies
```bash
pip install -r requirements.txt
### 2️⃣ Train the model 
python main.py 
### 3️⃣ Run GUI for prediction
python app.py
