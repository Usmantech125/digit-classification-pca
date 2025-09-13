# Digit Classification with PCA

This project demonstrates how to classify handwritten digits (0–9) using **Principal Component Analysis (PCA)** for dimensionality reduction and **Logistic Regression** for classification.

---

## 📌 Project Overview
- Dataset: **Scikit-learn Digits dataset**
- Each digit image is **8×8 pixels (64 features)**
- PCA reduces features from **64 → 30**
- Logistic Regression is trained on PCA-transformed data
- Achieved accuracy: **~96%**
- Also includes **2D PCA visualization** to see digit clusters

---

## 🧠 Key Concepts
1. **Features (64 inputs)**:  
   Each image has 64 pixel intensity values (0–16).  

2. **PCA (Dimensionality Reduction)**:  
   - Compresses data while keeping maximum information.  
   - Reduces 64-dimensional space into 30 components for training.  
   - For visualization, reduced into 2D.  

3. **Logistic Regression (Classification)**:  
   Predicts which digit (0–9) an image belongs to.

---

## 📂 Project Structure
