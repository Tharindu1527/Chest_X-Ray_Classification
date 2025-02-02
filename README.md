# COVID-19 and Pneumonia X-Ray Detector

## Project Overview
This project implements a deep learning model to detect and differentiate between COVID-19, viral pneumonia, bacterial pneumonia, and normal conditions using chest X-ray images. The model serves as a diagnostic aid tool for medical professionals.

## Dataset Information
The dataset is a custom compilation containing balanced classes with 133 images each:
- COVID-19 X-ray images (Class 0)
- Normal X-ray images (Class 1)
- Viral Pneumonia X-ray images (Class 2)
- Bacterial Pneumonia X-ray images (Class 3)

### Data Sources
The dataset was created using images from:
1. [COVID-19 Chest X-ray Dataset](https://github.com/ieee8023/covid-chestxray-dataset)
2. [Chest X-Ray Pneumonia Dataset](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

## Requirements
- Python 3.7+
- TensorFlow 
- NumPy
- Pandas
- Matplotlib
- scikit-learn

## Model Architecture
- The model uses a convolutional neural network (CNN) architecture
- Input: X-ray images (preprocessed and standardized)
- Output: 4-class classification (COVID-19, Normal, Viral Pneumonia, Bacterial Pneumonia)

## Performance Metrics
- Confusion Matrix
