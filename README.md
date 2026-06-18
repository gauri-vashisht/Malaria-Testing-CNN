# Malaria Cell Detection using Deep Learning

## Overview

Malaria remains one of the world's most serious infectious diseases, affecting millions of people annually. Early and accurate diagnosis is critical for timely treatment and reducing mortality rates.

This project develops a **Convolutional Neural Network (CNN)** capable of automatically classifying red blood cell (RBC) images as **Parasitized (Infected)** or **Uninfected**. The model leverages deep learning techniques to assist medical professionals in screening large volumes of microscopy images efficiently and accurately.

---

## Problem Statement

Manual examination of blood smear images is time-consuming, labor-intensive, and subject to human error. The objective of this project is to build an automated image classification system that can:

* Detect malaria-infected red blood cells
* Improve diagnostic efficiency
* Reduce dependency on manual screening
* Demonstrate the effectiveness of deep learning in medical imaging applications

---

## Dataset

The model was trained using a publicly available malaria cell image dataset containing more than **27,000 labeled RBC images**.

### Classes

* Parasitized (Malaria Infected)
* Uninfected (Healthy)

### Dataset Characteristics

* Microscopic blood smear images
* Balanced classification problem
* Real-world medical imaging data

---

## Technologies Used

### Programming Language

* Python

### Libraries & Frameworks

* TensorFlow
* Keras
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

### Deep Learning Concepts

* Convolutional Neural Networks (CNN)
* Data Augmentation
* Image Preprocessing
* Hyperparameter Tuning
* Model Evaluation
* Explainable AI (Grad-CAM)

---

## Methodology

### 1. Data Preprocessing

The image dataset underwent several preprocessing steps:

* Image resizing
* Pixel normalization
* Data augmentation
* Dataset splitting into training, validation, and test sets

These steps improved model generalization and reduced overfitting.

### 2. CNN Architecture

The model was built using multiple:

* Convolutional Layers
* ReLU Activation Functions
* Max Pooling Layers
* Fully Connected Dense Layers
* Dropout Regularization

The architecture was designed to automatically learn relevant visual features from blood cell images.

### 3. Model Training

The CNN was trained using:

* Binary Classification Loss Function
* Adam Optimizer
* Mini-Batch Gradient Descent
* Validation Monitoring

Hyperparameters were tuned to maximize predictive performance while preventing overfitting.

---

## Model Evaluation

Performance was assessed using multiple classification metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

### Results

* Achieved approximately **97% classification accuracy**
* Successfully distinguished infected and healthy cells
* Demonstrated strong generalization on unseen test samples

---

## Explainable AI (Grad-CAM)

To improve model transparency and interpretability, Grad-CAM visualization was implemented.

### Benefits

* Highlights image regions influencing model predictions
* Provides visual explanations for classification decisions
* Increases trust in deep learning-based medical diagnosis systems

---

## Project Workflow

Dataset Collection
↓
Image Preprocessing
↓
Data Augmentation
↓
CNN Model Development
↓
Model Training
↓
Performance Evaluation
↓
Grad-CAM Visualization
↓
Prediction & Analysis

---

## Key Learnings

Through this project, I gained practical experience in:

* Deep Learning Model Development
* Computer Vision Applications
* Medical Image Classification
* TensorFlow & Keras
* Data Augmentation Techniques
* Performance Evaluation Metrics
* Explainable Artificial Intelligence (XAI)
* End-to-End Machine Learning Pipelines

---

## Business & Real-World Impact

This project demonstrates how AI can support healthcare professionals by:

* Reducing diagnostic turnaround time
* Improving screening efficiency
* Assisting in large-scale disease detection
* Supporting data-driven healthcare decisions

The techniques used in this project can also be extended to other medical imaging tasks such as cancer detection, diabetic retinopathy screening, and pathology image analysis.

---

## Future Improvements

* Transfer Learning using ResNet50, EfficientNet, or MobileNet
* Model Deployment using Flask/FastAPI
* Real-time Prediction Interface
* Cloud Deployment on AWS
* Multi-Class Parasite Detection
* Advanced Explainability Techniques

---

## Author

**Gauri Vashisht**

Electronics & Computer Engineering
Thapar Institute of Engineering & Technology

GitHub: github.com/gauri-vashisht
