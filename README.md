# Pneumonia_Disease_Detection_Using_Chest_X-Ray_Images_Through_Deep_Learning_Techniques

This repository is a code storage for my Mini Project submission towards department of CSE(AI&ML) @ Vardhaman College of Engineering

## Dataset used : Kaggle Pneumonia Radiology Dataset

The Chest X-ray Images (Pneumonia) dataset on Kaggle is a crucial resource for training and evaluating machine learning models aimed at pneumonia detection from chest X-ray images. It is widely utilized in medical imaging and machine learning communities to develop algorithms that accurately distinguish between normal and pneumonia-affected X-rays. Researchers leverage this dataset to explore machine learning techniques, particularly convolutional neural networks (CNNs), to automate pneumonia diagnosis. The labeled data in this dataset supports robust model training and evaluation, enhancing diagnostic accuracy and efficiency in clinical settings.

## Proposed Model

Improved predictive performance can be achieved through the utilization of assembling a dataset of chest X-ray images categorized into pneumonia and normal cases. Images are standardized by resizing to 255x255 pixels and normalizing pixel values to a range of 0 to 1. DenseNet is selected for its efficiency and performance in image classification tasks. Variants like DenseNet-121 or DenseNet-169 are considered, balancing computational efficiency with accuracy. Batch normalization and ReLU activation ensure stability and non-linearity, while global average pooling reduces dimensionality before dense layers perform final classification. Leveraging DenseNet within a CNN framework ensures effective pneumonia prediction from chest X-ray images through meticulous data preprocessing, optimized model architecture, rigorous training, thorough evaluation, and robust deployment strategies. This ensemble approach leverages the strengths of both deep learning and gradient boosting techniques, aiming to improve accuracy and robustness in classification tasks.

## Results

| Classifier      | Accuracy         | Precision       | Recall | F1 Score |
|-----------------|------------------|-----------------|--------|----------|
| Proposed Ensembled Model |    98.82%     | 94.51%           | 95.09%| 94.79%          |

## Confusion Matrix

<img width="626" alt="Screenshot 2024-07-24 at 11 39 38 PM" src="https://github.com/user-attachments/assets/76cad39b-4dd3-4f66-897e-23a1369c166b">







