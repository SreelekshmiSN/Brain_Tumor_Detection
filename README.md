

#  Brain Tumor Detection using DenseNet121

## Overview

This project presents a Deep Learning-based Brain Tumor Detection and Classification system using MRI scan images.

## The system classifies brain MRI images into four categories:

- Glioma Tumor
- Meningioma Tumor
- Pituitary Tumor
- No Tumor

### The project combines:
- Transfer Learning
- Convolutional Neural Networks (CNN)
- Attention Mechanisms
- Regularization Techniques
- Quantization Approaches
- Batch Normalization

to improve classification accuracy and model performance.

---

## Tumor Classes

glioma
meningioma
pituitary
notumor

## Key Features

Multi-class Brain Tumor Classification
DenseNet121 Transfer Learning
CNN-based Feature Extraction
Batch Normalization
Self-Attention Block Integration
Quantization Techniques
Regularization for Overfitting Reduction
Data Augmentation
Model Evaluation Metrics
Confusion Matrix Visualization
Accuracy & Loss Graphs
Prediction with Confidence Score

### Technologies Used
Python
TensorFlow
Keras
NumPy
OpenCV
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
Deep Learning Architecture
Base Model

### The primary model uses:

DenseNet121
Pretrained on ImageNet
Used for transfer learning
Extracts deep image features efficiently
Additional Deep Learning Components

### The project further improves performance using:

1. Convolutional Neural Networks (CNN)

Used for spatial feature extraction from MRI images.

2. Batch Normalization

Improves training stability and accelerates convergence.

3. Self-Attention Block

Enhances important region focus within MRI scans.

4. Quantization Techniques

Used for optimization and reduced computational complexity.

5. Regularization Techniques

Helps reduce overfitting and improve generalization.

### Includes:

Dropout
Weight Regularization
Dataset Structure
Datasets/
│
├── Training/
│   ├── glioma/
│   ├── meningioma/
│   ├── pituitary/
│   └── notumor/
│
└── Testing/
    ├── glioma/
    ├── meningioma/
    ├── pituitary/
    └── notumor/
    
### Project Structure

Brain_Tumor_Detection/
│
├── Datasets/
├── Models/
│   └── brain_tumor_model_V2.keras
│
├── brain_tumor_detection.ipynb
├── README.md
├── LICENSE
└── .gitignore

### Installation

Clone Repository
git clone https://github.com/YOUR_USERNAME/Brain_Tumor_Detection.git
cd Brain_Tumor_Detection
Create Environment
conda create -n brainenv python=3.10
conda activate brainenv
Install Dependencies
pip install tensorflow==2.10.0
pip install numpy==1.23.5
pip install scipy==1.10.1
pip install opencv-python==4.7.0.72
pip install matplotlib seaborn scikit-learn notebook
Run Jupyter Notebook
jupyter notebook

Open:

brain_tumor_detection.ipynb

Model Training

### The notebook performs:

Image preprocessing
Data augmentation
CNN feature extraction
DenseNet121 transfer learning
Training and validation
Model saving

### Saved model:

Models/brain_tumor_model_V2.keras
Evaluation Metrics

### The project includes:

Accuracy Score
Precision
Recall
Validation Accuracy
Loss Curves
Confusion Matrix
Classification Report
Visualization Outputs
Training & Validation Accuracy

Model training accuracy and validation accuracy are visualized using graphs.

Training & Validation Loss

Loss curves help analyze convergence and overfitting.

Confusion Matrix

Used for evaluating class-wise prediction performance.

Prediction System

### The model predicts MRI scan images and provides:

Predicted Tumor Type
Confidence Score

Example:

Predicted Class: glioma
Confidence: 0.95
Results

### The trained model achieved strong classification performance on MRI brain tumor datasets using DenseNet121 combined with advanced deep learning optimization techniques.

Future Improvements
Real-time Brain MRI Detection
Web Application Deployment
Mobile App Integration
Grad-CAM Visualization
Medical Report Generation
Edge Device Optimization

### Author

Sreelekshmi S N

### Deep Learning & Computer Vision Project

This project is licensed under the MIT License.


