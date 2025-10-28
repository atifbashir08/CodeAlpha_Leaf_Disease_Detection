# CodeAlpha_Leaf_Disease_Detection
CodeAlpha Internship – Leaf Disease Detection using Deep Learning (CNN + Transfer Learning) – Classifies tomato leaves as healthy or infected (early/late blight) using TensorFlow and Keras.

# 🌿 Leaf Disease Detection (Tomato) using Deep Learning

## 📌 Overview
This project detects and classifies tomato leaf diseases using **Convolutional Neural Networks (CNN)** and **Transfer Learning**.  
It helps automatically identify plant diseases, supporting early diagnosis and improved crop management in agriculture.

This project was completed as part of my **CodeAlpha Internship (Task 1: Leaf Disease Detection)**.

---

## 🎯 Objectives
- Build a deep learning model to detect diseases in tomato leaves.  
- Use image preprocessing and data augmentation for better generalization.  
- Train and evaluate the model using MobileNetV2 (Transfer Learning).  
- Analyze accuracy, loss, and confusion matrix for performance.  

---

## 🧠 Model Details
- **Base Model:** MobileNetV2 (pre-trained on ImageNet)  
- **Classes:** Tomato Healthy, Tomato Early Blight, Tomato Late Blight  
- **Input Size:** 224 × 224 × 3  
- **Framework:** TensorFlow / Keras  

---

## 📂 Dataset
A subset of the [PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease) was used.  
Only the following classes were included:
- `Tomato___healthy`
- `Tomato___Early_blight`
- `Tomato___Late_blight`
