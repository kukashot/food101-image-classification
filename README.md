
# 🍱 Food-101 Image Classification with CNN

This project is a deep learning-based image classification model built to classify food images into one of 101 different categories using the [Food-101 dataset](https://www.kaggle.com/datasets/dansbecker/food-101). It was developed as part of a midterm project for the Deep Learning course (Spring 2025).

---

## 📌 Problem Statement

Build a Convolutional Neural Network (CNN) to classify images of food into 101 distinct classes. The goal is to train a robust model that can generalize well on unseen data.

---

## 🗂 Dataset

- **Name**: Food-101
- **Size**: 101,000 images (101 categories, ~1000 images per class)
- **Source**: [Kaggle - Food-101](https://www.kaggle.com/datasets/dansbecker/food-101)

---

## 🧠 Model Architecture

- Input: 128x128 RGB Images
- Layers:
  - Convolutional Layers
  - MaxPooling
  - Dropout
  - Flatten
  - Fully Connected Layers
- Output: Softmax layer with 101 classes

---

## 🛠 Tools & Technologies

- Python
- TensorFlow / Keras
- ImageDataGenerator (for data augmentation)
- Matplotlib (for visualization)

---

## 📊 Results

- Model Accuracy: _Add final validation/test accuracy here_
- Loss Curves and Accuracy Plots: _Add plots in notebook_

---

## 🚀 How to Run

1. Clone the repo
2. Download and extract the Food-101 dataset from Kaggle
3. Update the dataset path in the notebook
4. Run the notebook: `Kunal_Katariya_Food-101.ipynb`

---

## ✅ Future Improvements

- Use Transfer Learning (e.g., ResNet50 or EfficientNet)
- Add confusion matrix and classification report
- Deploy as a web app (Flask or Streamlit)

---

## 👤 Author

**Kunal Katariya**  
M.S. in Information Systems, Pace University  
Spring 2025 – Deep Learning Project

