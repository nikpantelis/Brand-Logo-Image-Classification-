# 🏷️ Logo Classification using Deep Learning

A deep learning project that classifies brand logos from the **FlickrLogos-27** dataset using TensorFlow/Keras. The project includes data preprocessing, logo extraction using bounding boxes, model training, evaluation, and prediction on unseen images.

---

## 📌 Project Overview

This project builds an image classification pipeline capable of recognizing different brand logos. The raw images are first processed using the provided annotation files to crop only the logo regions before training a convolutional neural network.

The workflow covers the complete machine learning pipeline, from data preparation to model evaluation.

---

## ✨ Features

- Load and preprocess the FlickrLogos-27 dataset
- Parse annotation files
- Crop logo regions using bounding box coordinates
- Clean and validate dataset annotations
- Visualize dataset samples and class distribution
- Create stratified training and validation splits
- Apply image augmentation
- Train a CNN using TensorFlow/Keras
- Evaluate model performance on unseen data
- Save trained models and predictions

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Pillow (PIL)
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

This project uses the **FlickrLogos-27** dataset, which contains images from 27 different logo classes along with bounding box annotations for logo localization.

Dataset preprocessing includes:

- Annotation parsing
- Bounding box validation
- Logo cropping
- Dataset cleaning
- Train/Validation split generation

---

## 🚀 Project Pipeline

1. Import libraries and configure environment
2. Load annotation files
3. Clean and validate metadata
4. Visualize raw images
5. Crop logo regions
6. Explore class distribution
7. Create train/validation datasets
8. Train the deep learning model
9. Evaluate classification performance
10. Save the trained model and predictions

---

## 📊 Model Evaluation

The trained model is evaluated using standard image classification metrics, including:

- Accuracy
- Classification Report
- Validation Performance

---

## 📁 Project Structure

```
Project_Logo_Classification.ipynb
README.md
```

---

## 🎯 Learning Objectives

- Image preprocessing using bounding box annotations
- Image augmentation for deep learning
- Building CNN-based image classifiers
- Dataset visualization and analysis
- Model evaluation using classification metrics

---

## Future Improvements

- Transfer learning with EfficientNet or ResNet
- Hyperparameter optimization
- Model explainability using Grad-CAM
- Deployment as a web application
- Support for additional logo datasets

---

## Author

**Pantelis Nikolaidis**

Master's Student in Data Science

Interested in Machine Learning, Deep Learning, Computer Vision, and Data Analytics.
