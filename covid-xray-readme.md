# Covid-19_and_Pneumonia_X-Ray_Detector

Aim of this project is to detect Covid-19 from X-ray and also able to differentitate Covid-19 from viral pneumonia and bacterial pneumonia. I have created a custom dataset that contains covid-19 x-ray images, viral pneumonia x-ray images, bacterial pneumonia x-ray images and normal person x-ray images. Each class contains 133 images.

## Dataset
I have used data from:
- https://github.com/ieee8023/covid-chestxray-dataset
- https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

### Class Labels
0 - Covid-19
1 - Normal X-ray
2 - Viral Pneumonia X-ray
3 - Bacterial Pneumonia X-ray

## Project Resources
All resources can be accessed using this link:
https://drive.google.com/drive/folders/16x0Tzcn9sh_CrtBPXN1ZRmkQZZNF8Ivz?usp=drive_link

## Project Structure
```
├── data/
│   ├── covid/
│   ├── normal/
│   ├── viral_pneumonia/
│   └── bacterial_pneumonia/
├── models/
├── notebooks/
└── README.md
```

## Requirements
- Python 3.7+
- TensorFlow 2.x
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Model Architecture
The model uses a Convolutional Neural Network (CNN) architecture with the following key features:
- Multiple convolutional layers
- Batch normalization
- MaxPooling layers
- Dropout for regularization
- Dense layers for classification

## Results
The model achieves the following performance metrics:
- Training accuracy: [Add your accuracy]
- Validation accuracy: [Add your accuracy]
- Test accuracy: [Add your accuracy]

## Future Work
- Increase dataset size
- Implement additional model architectures
- Add visualization tools
- Improve model performance

## Note
This project is for research purposes only and should not be used as a substitute for professional medical diagnosis.
