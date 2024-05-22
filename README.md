Deep Learning Framework for ADHD Diagnosis

This repository contains the code and documentation for my thesis project, which focused on developing a multimodal deep learning framework for the diagnosis and analysis of Attention-Deficit/Hyperactivity Disorder (ADHD) using physiological data.

Project Overview

ADHD is a prevalent neurodevelopmental disorder traditionally diagnosed through subjective and time-consuming assessments. This project investigates the potential of multimodal deep learning frameworks to enhance ADHD diagnosis by leveraging physiological data, specifically heart rate variability (HRV) and motor activity data.

Key Features

    Multimodal Data Integration: The framework integrates HRV and motor activity data to capture a more comprehensive picture of physiological patterns associated with ADHD.
    Deep Learning Models: Utilizes Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks to analyze complex temporal and spatial patterns in the data.
    Variable-Length Sequence Handling: Employs adaptive pooling layers to accommodate variations in sequence lengths, making the model more flexible and applicable to real-world data.

Repository Contents

    Code: Python scripts for data preprocessing, model implementation, training, and evaluation.
    Data: Instructions on how to access the HYPERAKTIV dataset used in this research.
    Documentation: Detailed explanations of the models, hyperparameter configurations, and evaluation results.

Dependencies

    Python 3.8
    TensorFlow 2.4
    Scikit-learn
    Jupyter Notebooks or Google Colab

Usage

    Clone the repository.
    Install the required dependencies.
    Download the HYPERAKTIV dataset and preprocess it according to the instructions.
    Run the Python scripts to train and evaluate the models.

Results

The dual-branch 1D CNN models outperformed the CNN-LSTM model, achieving a test accuracy of 85.71%. The results highlight the effectiveness of capturing unique patterns from HRV and motor activity data streams, contributing to improved diagnostic accuracy.
