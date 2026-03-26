# Diabetic_Retinopathy_Image_Classification
Deep learning pipeline leveraging CNN architectures (ResNet50, EfficientNet-B2) to classify diabetic retinopathy severity using advanced image preprocessing and class imbalance handling techniques.

![status](https://img.shields.io/badge/status-Completed-brightgreen)
![Python](https://img.shields.io/badge/Language-Python-blue)
![CNN](https://img.shields.io/badge/Model-CNN-red)
![Project](https://img.shields.io/badge/Type-DeepLearning-purple)

Overview

This project presents an end-to-end deep learning solution for the classification of diabetic retinopathy severity using retinal fundus images. The pipeline integrates data preprocessing, class imbalance handling, and transfer learning-based convolutional neural networks to accurately classify images into five severity stages.

The objective is to develop a robust and scalable model capable of assisting in early detection and diagnosis, thereby supporting healthcare decision-making.

Objective

The objective is to develop a robust and scalable model capable of assisting in early detection and diagnosis, thereby supporting healthcare decision-making.

🔹 Classify retinal images into five stages of diabetic retinopathy (0–4)

🔹 Leverage transfer learning to improve classification performance

🔹 Address class imbalance inherent in medical datasets

🔹 Evaluate model performance using comprehensive classification metrics

Tech Stack

🔹 Programming Language: Python

🔹 Frameworks: TensorFlow, Keras

🔹 Libraries: OpenCV, NumPy, Pandas, Scikit-learn

🔹 Imbalance Handling: Imbalanced-learn (SMOTE)

Dataset

🔹 APTOS 2019 Blindness Detection Dataset

Model Architecture

Transfer learning techniques were applied using pre-trained CNN architectures:

🔹 ResNet50

🔹 EfficientNet-B2

Performance Evaluation

The model achieved an accuracy of approximately 77% and was evaluated using:

🔹 Confusion Matrix

🔹 Sensitivity and Specificity

🔹 Classification Report

These metrics provide a comprehensive understanding of model performance, particularly in a healthcare context where accuracy alone is insufficient.

Key Insights

🔹 Transfer learning significantly enhances model performance on limited datasets

🔹 Class imbalance has a notable impact on minority class predictions

🔹 Image preprocessing plays a critical role in improving feature extraction

🔹 Model performance varies across severity levels, indicating opportunities for further optimization

Key Learnings

🔹 Implementation of deep learning models for medical image classification

🔹 Techniques for handling imbalanced datasets in healthcare applications

🔹 Importance of preprocessing in improving model robustness

🔹 Evaluation of models using domain-relevant performance metrics

Project Value

This project demonstrates the ability to design and implement an end-to-end machine learning pipeline, combining data preprocessing, model development, and evaluation. It highlights practical experience in applying deep learning techniques to real-world healthcare problems.

📂 Repository Structure
/data  
/notebooks  
/models  
/images  
README.md  
