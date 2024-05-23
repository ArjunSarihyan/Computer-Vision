# Skin Cancer Detection with TensorFlow and CNN

## Introduction
In the realm of healthcare technology, the project "Detecting Skin Cancer with TensorFlow and CNN in Python" aims to revolutionize skin cancer diagnosis by leveraging machine learning techniques. This project lays the groundwork for training a robust Convolutional Neural Network (CNN) using TensorFlow and Keras to accurately predict skin cancer cases from images.

## Dataset
The dataset used in this project consists of images of skin lesions categorized into benign and malignant classes. Due to limitations in file hosting, the dataset is not included in the repository. However, you can find similar datasets on platforms like Kaggle or by accessing medical image databases.

## Task Overview

### Task 1: Data Preprocessing
The dataset preprocessing involves reading images, resizing them to a standard size (224x224), and encoding labels using scikit-learn's `LabelEncoder`.

### Task 2: Data Split
The preprocessed dataset is split into training and testing sets using scikit-learn's `train_test_split` function.

### Task 3: Model Training
A Convolutional Neural Network (CNN) model is built and trained using TensorFlow and Keras. The model architecture consists of multiple convolutional and pooling layers followed by dense layers for classification.

### Task 4: Model Evaluation
The trained model is evaluated using precision, recall, and F1 score metrics to assess its performance on the test set.

### Task 5: Single Image Prediction
A user-friendly function is provided to predict skin cancer from a single image. The function loads a pre-trained model and predicts the class label (benign or malignant) for the input image.

## Notes
- The main source code files are not included in the repository due to file size constraints. Please download the file to view in webpage format.
