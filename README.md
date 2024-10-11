# Signature-Classification-using-CNN

A signature recognition project using HOG, SIFT, and CNN approaches to classify signatures, with comprehensive evaluations and visualizations of model performance.

## Project Structure

The project is organized as follows:

- **Data Augmentation and Preprocessing**: Image data generators for training and testing datasets with normalization and slight transformations.
- **Feature Extraction**:
  - **HOG (Histogram of Oriented Gradients)**
  - **SIFT (Scale-Invariant Feature Transform)**
  - **CNN (Convolutional Neural Network)**
- **Model Training**:
  - **HOG-ANN** and **SIFT-ANN** using artificial neural networks.
  - **CNN** with batch normalization, dropout, and early stopping.
- **Evaluation**: Model performance metrics such as accuracy, precision, recall, and F1-score.
