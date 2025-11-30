# Age and Gender Detection ML Model

## Project Overview
This project implements a machine learning model that detects and predicts the age and gender of individuals from images. It uses convolutional neural networks (CNN) to process image data.

## Objective
- Build a multi-output neural network that can predict age and gender simultaneously
- Achieve high accuracy in both classifications
- Create a deployable model for real-world image inputs

## Technologies Used
- Python 3.x
- TensorFlow / Keras
- OpenCV
- NumPy & Pandas
- Matplotlib & Seaborn

## Dataset
- Image dataset with labeled age and gender information
- Preprocessed and normalized for model training
- Data split: Training (80%), Validation (10%), Testing (10%)

## Model Architecture
- Input: RGB images (224x224 pixels)
- Backbone: Pre-trained CNN architecture
- Output Layer 1: Gender (Binary Classification)
- Output Layer 2: Age (Regression/Classification)

## Files in This Project
- age_gender_detection.ipynb - Main notebook
- model_weights.h5 - Trained model
- data/ - Dataset folder
- results/ - Output predictions

## How to Use
1. Open the Jupyter notebook
2. Load and preprocess data
3. Build and train the model
4. Evaluate performance
5. Make predictions on new images

## Key Learnings
- Multi-output neural network design
- Transfer learning techniques
- Image preprocessing and augmentation
- Model evaluation and optimization
