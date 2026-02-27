# 🌡️ Non-Contact Detection of Facial Health Conditions Using Infrared Images

## 📌 Overview

This project develops a computer vision–based framework for non-contact detection of facial health conditions using infrared (thermal) face images. The objective is to analyze temperature distribution patterns and spatial facial features to enable automated, non-invasive condition classification.

The system implements a complete deep learning pipeline including image preprocessing, feature extraction, model training, and performance evaluation.

---

## 🧪 Methodology

### 1️⃣ Image Preprocessing
- Infrared image normalization and noise reduction  
- Face detection and region-of-interest (ROI) extraction  
- Image resizing and pixel scaling  
- Data augmentation for model generalization  

### 2️⃣ Feature Engineering
- Extraction of thermal distribution patterns  
- Spatial feature mapping from facial regions  
- Conversion of images into model-compatible tensor representations  

### 3️⃣ Model Development
- Implementation of CNN-based deep learning architectures  
- Hyperparameter tuning for optimal convergence  
- Regularization techniques to mitigate overfitting  
- Train-validation splitting for performance assessment  

### 4️⃣ Model Evaluation
- Accuracy, Precision, Recall, F1-Score  
- Confusion Matrix analysis  
- ROC-AUC evaluation  
- Comparative validation across model variants  

---

## 🛠️ Tech Stack

- **Programming:** Python  
- **Image Processing:** OpenCV  
- **Data Handling:** NumPy, Pandas  
- **Modeling:** TensorFlow / PyTorch, Scikit-learn  
- **Visualization:** Matplotlib  

---

## 🎯 Objective

To design a reliable, non-invasive health monitoring system capable of detecting condition-specific patterns from infrared facial imagery using deep learning methodologies.
