# Face Recognition Biometric Authentication System

This repository contains the implementation of a face recognition-based biometric authentication system developed as a part of a computer security course assignment.

## Overview

The goal of this project was to design and implement a biometric authentication system using face recognition techniques. The system utilizes machine learning algorithms and evaluation metrics to verify user identities based on facial features.

## Key Features

- **Dataset Preparation**: Utilized publicly available benchmark datasets for testing, ensuring privacy and data integrity.
- **Feature Extraction**: Extracted features from grayscale face images using simple preprocessing techniques.
- **Classification**: Implemented a Support Vector Machine (SVM) classifier for distinguishing between genuine users and imposters.
- **Evaluation Metrics**: Calculated performance metrics including False Match Rate (FMR), False Non-Match Rate (FNMR), and Equal Error Rate (EER) to evaluate system accuracy.
- **GitHub Repository**: Includes detailed code implementation and a structured report summarizing the project.

## System Design and Architecture

The system comprises the following components:
- Data preprocessing to prepare face images for feature extraction.
- Feature representation using flattened image data.
- SVM classification model for biometric authentication.
- Evaluation of system performance using various metrics.

## Project Structure

- **`data/`**: Directory containing sample face images for testing.
- **`code.ipynb`**: Contains the Jupyter Notebook for data preprocessing, model training, and evaluation.
- **`Report.pdf`**: Includes a detailed report outlining the project objectives, methodology, implementation details, and evaluation results.


## Evaluation Results

The system achieved the following evaluation metrics:
- **Accuracy**: 0.62
- **FMR**: 0.35
- **FNMR**: 0.41
- **EER**: 0.35

## Future Enhancements

Potential improvements and future enhancements include:
- Implementing advanced feature extraction techniques (e.g., CNNs) for improved performance.
- Exploring ensemble learning methods to enhance classification accuracy.
- Optimizing threshold selection algorithms for adaptive decision-making.
