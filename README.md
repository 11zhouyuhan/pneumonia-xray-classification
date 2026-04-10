# Pneumonia X-Ray Classification

## Project Introduction

This project uses a chest X-ray image dataset to build a Convolutional Neural Network (CNN) for binary classification of pneumonia. The model can distinguish between normal lungs and pneumonia-infected X-ray images.

## Data Source

- **Dataset Name**: Chest X-Ray Images (Pneumonia)
- **Source**: Kaggle
- **Data Size**: 5,856 X-ray images (JPEG format), divided into training, validation, and test sets

## Project Workflow

- Step 1: Data loading and preprocessing (image resizing, normalization, data augmentation)
- Step 2: Build Convolutional Neural Network (CNN) model
- Step 3: Model training (10 epochs, GPU accelerated)
- Step 4: Model evaluation (accuracy, precision, recall, confusion matrix)
- Step 5: Result visualization

## Model Performance

- Test set accuracy: 79%
- Pneumonia class precision: 0.76
- Pneumonia class recall: 0.98 (low missed diagnosis rate, especially important for medical scenarios)
- Normal class precision: 0.93
- Normal class recall: 0.48

### Confusion Matrix

| Actual\Predicted | Predicted Normal | Predicted Pneumonia |
|------------------|------------------|---------------------|
| Actual Normal    | 113              | 121                 |
| Actual Pneumonia | 9                | 381                 |

## Technologies Used

- Python (PyTorch, Torchvision, NumPy, Matplotlib, Seaborn)
- Convolutional Neural Network (CNN)
- Data augmentation (random flip, rotation)
- GPU accelerated training

## How to Run

1. Clone this repository to your local machine
2. Install dependencies: `pip install torch torchvision numpy matplotlib seaborn scikit-learn`
3. Launch Jupyter Notebook and run `pneumonia_xray_classification.ipynb`

## Project Value

- Graduate school application: Demonstrates practical skills in deep learning and computer vision
- Job resume: Shows project experience with PyTorch, CNN, and medical image processing
- Medical AI introduction: Understands the application of image classification in medical diagnosis

## Contact

- GitHub: 11zhouyuhan
- Project Link: https://github.com/11zhouyuhan/pneumonia-xray-classification
