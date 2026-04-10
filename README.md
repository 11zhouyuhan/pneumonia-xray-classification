# Pneumonia X-Ray Classification - Pneumonia X-ray Image Recognition

Project Introduction

This project uses a chest X-ray image dataset to construct a convolutional neural network (CNN) for binary classification recognition of pneumonia. The model can distinguish between normal lungs and X-rays of pneumonia infection.

Data source

- ** Dataset Name ** : Chest X-Ray Images (Pneumonia)
- ** Source: Kaggle
- ** Data Size ** : 5,856 X-ray images (JPEG format), divided into a training set, a validation set, and a test set

Project process

Step 1: Data loading and preprocessing (image scaling, normalization, data augmentation)
Step 2: Build the convolutional Neural Network (CNN) model
Step 3: Model Training (10 epochs, using GPU acceleration)
Step Four: Model Evaluation (Accuracy Rate, precision Rate, recall Rate, confusion matrix
Step 5: Visualization of results

Model effect

- Accuracy rate of the test set: 79%
- Accuracy rate of pneumonia category: 0.76
- Recall rate for pneumonia category: 0.98 (Low rate of missed diagnosis, particularly important for medical scenarios)
- Normal category accuracy rate: 0.93
- Normal category recall rate: 0.48

Confusion matrix

Actual/Prediction: Normal prediction: Pneumonia prediction
|-----------|----------|----------|
Actual normal: 113, 121
Actual pneumonia cases: 9-381

The technology used

- Python (PyTorch, Torchvision, NumPy, Matplotlib, Seaborn)
Convolutional Neural Network (CNN
- Data augmentation (random flipping, rotation)
Gpu-accelerated training

How to run

1. Clone the repository to the local machine
2. install dependencies: pip install torch torchvision numpy matplotlib seaborn scikit-learn
3. Start Jupyter Notebook and run pneumonia_xray_classification.ipynb

Project value

- Postgraduate entrance examination/recommendation for postgraduate study re-examination: Prove the practical ability of deep learning and computer vision
- Resume: Demonstrate experience in PyTorch, CNN, and medical image processing projects
- Introduction to Medical AI: Understanding the Application of Image Classification in Medical Diagnosis

Contact Information

-GitHub: 11zhouyuhan
- project link: https://github.com/11zhouyuhan/pneumonia-xray-classification
