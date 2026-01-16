# Automated Object Classification for Smart CCTV Surveillance

This project implements an enhanced Convolutional Neural Network(CNN) for 
automated object classification in smart CCTV surveillance systems.

## Objective
To reduce unnecessary storage and manual monitoring by recording footage
only when relevant objects are detected with high confidence.

## Dataset
- Fashion-MNIST (used as a proxy dataset)
- Grayscale images (28×28)
- 10 object categories

## Model Enhancements
- Batch Normalization
- Dropout Regularization
- Data Augmentation
- Confidence-based selective recording

## Results
- Test Accuracy: ~87%
- Reduced overfitting
- Lightweight model suitable for edge deployment

## Selective Recording Logic
Frames are recorded only if prediction confidence exceeds a predefined threshold.

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy, Matplotlib

## How to Run
```bash
pip install tensorflow numpy matplotlib scikit-learn
Open the notebook and run all cells in Jupyter Notebook
