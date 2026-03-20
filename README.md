# Malaria Cell Classification with CNN (PyTorch)

This project demonstrates image classification of malaria-infected cells using a Convolutional Neural Network (CNN) implemented in PyTorch, along with visualization techniques such as CAM and Grad-CAM.

---

## Overview

The goal of this project is to classify cell images into two categories:

- Infected (Parasitized)
- Uninfected

The model is trained on a dataset of cell images and uses deep learning techniques to learn patterns in medical imagery.

Additionally, the project includes visualization methods (CAM and Grad-CAM) to interpret model predictions.

---

## Features

- Image classification using CNN  
- Custom PyTorch dataset  
- Data preprocessing and transformation  
- Train/test split with stratification  
- Model training with early stopping  
- Visualization of model attention using:
  - CAM (Class Activation Map)
  - Grad-CAM  
- Overlay of heatmaps on input images  

---

## Technologies Used

- Python  
- PyTorch  
- NumPy  
- OpenCV  
- Matplotlib  
- scikit-learn  
- PIL  

---

## Model Architecture

The model is a simple Convolutional Neural Network:

- 3 convolutional layers  
- ReLU activations  
- MaxPooling  
- Adaptive average pooling  
- Fully connected classification layer  

---

## Training Process

- Loss function: CrossEntropyLoss  
- Optimizer: Adam  
- Early stopping used to prevent overfitting  
- Validation loss used to select the best model  

---

## Visualization

To improve interpretability, the project implements:

### CAM (Class Activation Map)
Uses classifier weights to identify important regions in the image.

### Grad-CAM
Uses gradients flowing into the last convolutional layer to highlight relevant areas.

These techniques help understand how the model makes decisions.

---

## How to Run

1. Clone the repository:
   git clone https://github.com/your-username/malaria-cnn-project.git

2. Install dependencies:
   pip install torch torchvision matplotlib opencv-python scikit-learn pillow

3. Update dataset path in the code:
   data_path = "path_to_cell_images"

4. Run the notebook or script

---

## Results

- The model successfully learns to distinguish infected and uninfected cells  
- Grad-CAM visualizations highlight important regions of the image  
- The approach demonstrates the effectiveness of CNNs for medical image classification  

---

## What This Project Demonstrates

- deep learning with PyTorch  
- image classification pipeline  
- working with custom datasets  
- model interpretability (CAM, Grad-CAM)  
- understanding of computer vision tasks  

---

## 🇺🇦 Опис українською

Цей проєкт демонструє класифікацію зображень клітин малярії за допомогою згорткової нейронної мережі (CNN).

Реалізовано:
- навчання моделі на PyTorch  
- обробку та підготовку даних  
- візуалізацію результатів (CAM, Grad-CAM)  
- аналіз того, як модель приймає рішення  
