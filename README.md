# Deep-Learning

# Handwritten Mathematical Expression Recognition using Deep Learning

## Overview

This project was developed as part of the Deep Learning course at HIT (Holon Institute of Technology).

The goal of the project is to recognize handwritten mathematical expressions and convert them into structured LaTeX representations using deep learning techniques.

The project implements a complete machine learning pipeline, including data preparation, image preprocessing, tokenization of mathematical expressions, model training, hyperparameter tuning, and evaluation.

---

## Problem Statement

Handwritten mathematical expression recognition is a challenging computer vision task that combines image understanding and sequence generation.

The objective is to automatically translate an image containing a handwritten mathematical formula into its corresponding LaTeX code representation.

Example:

Image:

x² + y² = z²

Output:

```latex
x^2 + y^2 = z^2
```

---

## Dataset

The project uses the CROHME23 dataset (Competition on Recognition of Online Handwritten Mathematical Expressions).

The dataset contains:

* Handwritten mathematical expressions
* Ground truth LaTeX annotations
* Training and testing samples
* Various mathematical symbols and structures

---

## Project Workflow

### 1. Data Cleaning

* Filtering invalid samples
* Removing corrupted files
* Matching images with annotations
* Dataset validation

### 2. Data Parsing

* Parsing annotation files
* Extracting LaTeX expressions
* Matching formulas with images

### 3. Image Preprocessing

* Image normalization
* Noise reduction
* Resizing and formatting
* Visualization of processed samples

### 4. Tokenization

* LaTeX token extraction
* Vocabulary construction
* Token dictionary generation
* Encoding mathematical expressions

### 5. Exploratory Data Analysis

* Token frequency analysis
* Formula length distribution
* Dataset statistics
* Visualization of data characteristics

### 6. Deep Learning Pipeline

* Dataset preparation
* Tensor conversion
* Training and validation split
* DataLoader implementation

### 7. Model Training

* Neural network training
* Performance monitoring
* Loss tracking
* Validation evaluation

### 8. Hyperparameter Optimization

* Learning rate tuning
* Batch size experimentation
* Model performance comparison

### 9. Model Evaluation

* Testing on unseen samples
* Prediction analysis
* Error analysis
* Performance assessment

---

## Technologies Used

* Python
* PyTorch
* TorchVision
* NumPy
* Pandas
* Matplotlib
* PIL
* Google Colab

---

## Skills Demonstrated

This project demonstrates practical experience in:

* Deep Learning
* Computer Vision
* Image Processing
* Optical Character Recognition (OCR)
* Data Preprocessing
* Neural Network Training
* Hyperparameter Optimization
* Sequence Modeling
* Scientific Computing with Python

---

## Repository Contents

* `DeepLearningProject.ipynb` – complete project implementation
* Dataset preprocessing pipeline
* Training and evaluation workflow
* Visualizations and analysis
