# ♻️ Waste Classification Using Deep Learning

A deep learning project for **multi-class waste image classification** using a **Custom Convolutional Neural Network (CNN)** and **ResNet18 Transfer Learning** implemented in **PyTorch**.

This project compares a CNN built from scratch with a pretrained ResNet18 model to analyze the effectiveness of transfer learning for waste image classification.

---

## 📌 Project Overview

Proper waste segregation is essential for effective recycling and environmental sustainability. Manual waste sorting is time-consuming and prone to errors.

This project aims to automate waste classification using deep learning techniques by classifying images into **10 different waste categories**.

Two different approaches were implemented and compared:

- Custom CNN
- Transfer Learning using ResNet18

---

## 🎯 Objectives

- Build a Custom CNN for image classification.
- Apply Transfer Learning using ResNet18.
- Compare the performance of both models.
- Evaluate the models using standard classification metrics.
- Understand the impact of transfer learning on image classification tasks.

---

## 🗂️ Dataset

- **Dataset:** Waste Classification Dataset
- **Number of Classes:** 10

Classes:

- Battery
- Biological
- Cardboard
- Clothes
- Glass
- Metal
- Paper
- Plastic
- Shoes
- Trash

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 🧠 Models Implemented

### 1️⃣ Custom CNN

Architecture includes:

- Convolution Layers
- Batch Normalization
- ReLU Activation
- Max Pooling
- Dropout
- Fully Connected Layers

---

### 2️⃣ Transfer Learning (ResNet18)

- Pretrained ResNet18
- Replaced Final Fully Connected Layer
- Fine-tuned for 10-class classification

---

## 📊 Results

| Model | Test Accuracy |
|--------|---------------|
| Custom CNN | **67.70%** |
| ResNet18 Transfer Learning | **75.53%** |

Transfer Learning achieved significantly better performance by leveraging pretrained ImageNet features.

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Test Accuracy
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

---

## 📁 Repository Structure

```
Waste-Classification-Using-Deep-Learning/
│
├── README.md
├── LICENSE
├── Custom_CNN.ipynb
├── Transfer_Learning_ResNet18.ipynb
└── images/
```

---

## 🚀 Future Improvements

- Train on a larger and more balanced dataset.
- Experiment with EfficientNet and Vision Transformers.
- Deploy the model using Flask or Streamlit.
- Integrate with IoT-based smart waste segregation systems.

---

## 💡 Key Learnings

During this project, I gained hands-on experience with:

- Image Classification
- Deep Learning Fundamentals
- CNN Architecture Design
- Transfer Learning
- Data Augmentation
- Model Evaluation
- PyTorch Workflow
- Performance Comparison

---

## 📬 Connect With Me

If you have suggestions, feedback, or ideas for improvement, feel free to connect or raise an issue in this repository.

⭐ If you found this project helpful, consider giving it a star!
