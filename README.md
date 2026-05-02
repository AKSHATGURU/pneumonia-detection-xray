# pneumonia-detection-xray
# 🩺 Pneumonia Detection using Deep Learning

## 📌 Overview
This project focuses on detecting pneumonia from chest X-ray images using a deep learning model based on ResNet50 architecture. The model classifies images into two categories: **Normal** and **Pneumonia**.

---

## 🚀 Features
- Binary classification (Normal vs Pneumonia)
- Transfer learning using ResNet50
- Data augmentation to improve generalization
- Early stopping & model checkpointing
- Performance evaluation using confusion matrix and classification report

---

## 🧠 Model Architecture
- Base Model: ResNet50 (pretrained on ImageNet)
- Layers:
  - Global Average Pooling
  - Dense Layer
  - Dropout

---

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 🗂 Dataset
Chest X-ray dataset containing:
- NORMAL images
- PNEUMONIA images

---

## ⚙️ Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- NumPy / Matplotlib

---

## ▶️ Run the Project
1. Open the notebook
2. Run all cells
3. Ensure dataset path is correctly set

---

## 🔗 Live Notebook (Colab)
https://colab.research.google.com/github/AKSHATGURU/pneumonia-detection-xray/blob/main/x_ray_0.ipynb


