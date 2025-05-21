# Face Emotion Recognition with FER2013

This project implements a deep learning pipeline for **Face Emotion Recognition** using the [FER2013 dataset](https://www.kaggle.com/datasets/msambare/fer2013). The goal is to classify facial expressions into emotion categories such as *angry*, *disgust*, *fear*, *happy*, *sad*, *surprise*, and *neutral*.

## Project Overview

- **Dataset:** FER2013 (grayscale face images labeled by emotion)
- **Framework:** TensorFlow / Keras
- **Model:** Convolutional Neural Network (CNN)
- **Key Steps:**
    - Data loading and preprocessing
    - Data augmentation for robust training
    - Model design and training with early stopping
    - Evaluation and visualization of results

## Results

- **Training Accuracy:** 0.6345  
     The model correctly classified about 63.45% of the training samples.

- **Training Loss:** 0.9807  
     Represents the error between predictions and true labels on the training set.

- **Validation Accuracy:** 0.6474  
     The model correctly classified about 64.74% of the samples in the validation (test) set.

- **Validation Loss:** 0.9500  
     Measures the error on the validation set.

- **Visualization:** Training/validation curves and confusion matrix are included in the notebook.
