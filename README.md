# ♻️ Waste Classifier AI

This is an AI-powered image classification model that categorizes waste into **Biodegradable** and **Non-Biodegradable** categories. It supports environmental sustainability by promoting proper waste segregation using machine learning.

## 📌 Project Overview

- **Goal**: Automatically classify waste into biodegradable and non-biodegradable using deep learning.
- **Model**: Convolutional Neural Network (CNN) built with TensorFlow/Keras.
- **Dataset**: Two-class labeled image dataset (Biodegradable / Non-Biodegradable).
- **Use Case**: Sustainability, Smart Cities, Environmental Monitoring.

## 🚀 Features

- CNN model with >90% validation accuracy
- Lightweight and suitable for deployment on mobile/web platforms
- Built using Google Colab, enabling ease of access and training
- Saved as `.h5` model for reuse in deployment environments

## 🧠 Model Architecture

- 3 Convolutional layers with ReLU activation
- Max Pooling for dimensionality reduction
- Dense fully connected layers with Dropout regularization
- Softmax output layer for classification

## 🏗️ How It Works

1. Dataset preprocessing using `ImageDataGenerator`
2. Model training on 80% of the data
3. Validation using 20% split
4. Exported model: `waste_classifier_model.h5` not uploaded because of file size

## 💡 Potential Improvements

- Deployment via Flask, FastAPI, or TensorFlow.js
- Integration into IoT bins or recycling centers
- Expansion to multi-class waste categories

## 📁 Dataset

- Not included due to size. Contact author if required.
- Structure:
