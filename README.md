
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
```
Digit-Classification-PCA/
│── notebook.ipynb        # Jupyter Notebook with code
│── README.md             # Project description
```

---

## 🚀 How to Run
1. Clone repository or download files.  
2. Install dependencies:
   ```bash
   pip install scikit-learn matplotlib
   ```
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook notebook.ipynb
   ```

---

## 📊 Results
- Model Accuracy: **~96%**
- PCA 2D Visualization: Digits form clear clusters in reduced space.



---

## ✅ Conclusion
PCA helps reduce feature dimensions, speeds up training, removes noise, and enables visualization.  
This makes it a powerful preprocessing step for ML pipelines.

---
