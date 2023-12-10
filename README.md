# Pneumonia-Image-Classifier
Convolutional neural network that differentiates pneumonia infected lungs from normal ones.

# X-Ray Pneumonia Detection using Convolutional Neural Network

## Overview

This project implements a Convolutional Neural Network (CNN) using TensorFlow to differentiate between X-rays with pneumonia and those without. The model achieved impressive performance metrics:

- Precision: 96.35%
- Recall: 94.51%
- Binary Accuracy: 93.40%

## Dataset

The model was trained on a dataset sourced from Kaggle, which you can find [here](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia).


## Data Preprocessing

Before training the model, a thorough data preprocessing step was conducted. Images not meeting quality standards and those not belonging to specified image types (jpeg, jpg, bmp, png) were removed from the dataset. This ensures that the model is trained on a clean and relevant dataset.

## Model Architecture

The CNN model architecture comprises three convolutional layers with max-pooling, followed by flattening and dense layers. The model is compiled using the Adam optimizer and binary cross-entropy loss, with accuracy as the metric. The model summary provides insights into the layers and parameters.

## Training

The model was trained for 20 epochs, and training progress was monitored using TensorBoard. The training process exhibited steady improvement in both accuracy and loss over the epochs.

## Evaluation

After training, the model was evaluated on a test set, and performance metrics were calculated. Precision, recall, and binary accuracy were used to assess the model's ability to classify X-rays accurately.

## Future Work

Future improvements may include fine-tuning the model for enhanced accuracy and exploring additional datasets to make the model more robust.

## Technologies Used

- TensorFlow
- Python
- OpenCV
- Matplotlib

