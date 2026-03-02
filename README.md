# 🍎 Apple Fresh vs Rotten Classification Model

A Deep Learning based image classification model that predicts whether an apple is **Fresh** or **Rotten** using Transfer Learning with MobileNetV2.

---

## 📌 Project Overview

This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify apples into two categories:
- Fresh
- Rotten

Transfer Learning was applied using a pretrained MobileNetV2 model to improve performance on a limited dataset.

---

## 🚀 Technologies Used

- Python
- TensorFlow
- Keras
- Transfer Learning (MobileNetV2)
- Google Colab (Model Training)

---

## 🧠 Model Architecture

- Input Layer (224x224x3)
- MobileNetV2 (Pretrained on ImageNet, feature extractor)
- Global Average Pooling
- Dense Layer (ReLU)
- Dropout (Regularization)
- Output Layer (Sigmoid activation for binary classification)

The model was implemented using the **Keras Functional API** to ensure stable serialization and production readiness.

---

## 📊 Training Details

- Loss Function: Binary Crossentropy
- Optimizer: Adam
- Evaluation Metric: Accuracy
- Image Size: 224x224
- Data Augmentation applied to improve generalization

---

## 📁 Project Structure
apple-classifier/
│
├── apple_classifier.ipynb
├── README.md
├── requirements.txt
└── .gitignore

---

## 📈 Future Improvements

- Convert into a Flask-based web application for real-time prediction
- Deploy using Docker or Cloud platforms
- Improve accuracy with fine-tuning and hyperparameter optimization

---

## 📌 Author

Kanak Agrawal  
B.Tech CSE (Data Science)
