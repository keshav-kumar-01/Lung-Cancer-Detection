# Lung Cancer Detection

This repository contains code for lung cancer detection using deep learning techniques.

## Installation

You can install the required packages using the following command:

```bash
pip install tensorflow==2.9.0
```
## Description
The detection model is built using TensorFlow and Keras, leveraging convolutional neural networks (CNNs) for image classification. The dataset used for training and testing consists of images of lung and colon tissues.
## Usage
To train the model, run the provided Python script lung_cancer_detection.py. Make sure to adjust the file paths according to your dataset location. After training, you can evaluate the model's performance and make predictions on new data.
## Preprocessing
The preprocessing steps include histogram equalization and contrast limited adaptive histogram equalization (CLAHE) to enhance the images before feeding them into the model. This helps in improving the model's ability to learn features from the images effectively.
## Dependencies
TensorFlow 2.9.0
Keras
NumPy
Pandas
Matplotlib
OpenCV
## Contributors
Keshav Kumar
