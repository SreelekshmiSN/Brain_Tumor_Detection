

#  Brain Tumor Detection using DenseNet121

## Overview

This project implements a deep learning-based Brain Tumor Detection system using MRI scan images.
The model is built using TensorFlow/Keras with DenseNet121 Transfer Learning for multi-class classification of brain tumors.

### The system can classify MRI images into the following categories:

Glioma
Meningioma
Pituitary Tumor
No Tumor

### The project also includes:

Model training
Evaluation metrics
Visualization graphs
Confusion matrix
Prediction on custom MRI images
Features
Deep Learning-based tumor classification
Transfer Learning using DenseNet121
Data Augmentation
Model Evaluation & Accuracy Metrics
Confusion Matrix Visualization
Prediction with Confidence Score
TensorFlow/Keras implementation
Jupyter Notebook workflow
Tech Stack
Python
TensorFlow / Keras
NumPy
OpenCV
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook

## Dataset

Dataset:Brain Tumor MRI Dataset(Kaggle)

### The dataset contains MRI brain scan images categorized into:

Training/
    glioma/
    meningioma/
    pituitary/
    notumor/

Testing/
    glioma/
    meningioma/
    pituitary/
    notumor/
Model Architecture

## The project uses:

DenseNet121 (Pretrained on ImageNet)
Global Average Pooling
Dropout Layer
Dense Output Layer with Softmax Activation
Training Details
Parameter	Value
Image Size	224x224
Batch Size	32
Epochs	10
Optimizer	Adam
Loss Function	Categorical Crossentropy

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

## Installation

Clone Repository
git clone https://github.com/SreelekshmiSN/Brain_Tumor_Detection.git
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

### jupyter notebook

Open:

brain_tumor_detection.ipynb
Model Training

### Run the notebook cells sequentially to:

Load dataset
Preprocess images
Train model
Save trained model

## Saved model:

Models/brain_tumor_model_V2.keras
Model Evaluation

## The project includes:

Accuracy Score
Validation Accuracy
Loss Graphs
Precision & Recall Curves
Confusion Matrix
Classification Report
Prediction

The model can predict MRI images with confidence scores.

### Example Output:

Predicted Class: glioma
Confidence: 0.95
Results

The trained model achieved high classification accuracy on the testing dataset with effective multi-class prediction performance.

## Future Improvements

Deploy as Web Application
Real-time MRI Prediction
Grad-CAM Visualization
Mobile App Integration
Medical Report Generation

## Author

Sreelekshmi S N

## License

This project is licensed under the MIT License.





