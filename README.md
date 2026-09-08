# Waste Image Classification

A deep learning project for classifying waste images using **MobileNetV2** with adaptive image preprocessing techniques to improve classification performance under challenging image conditions.

## Overview

This project focuses on classifying waste images into four categories:

- Glass
- Metal
- Paper
- Plastic

The project uses a pretrained **MobileNetV2** model with transfer learning. Different preprocessing techniques were evaluated to improve image quality and classification performance, particularly for difficult samples.

## Image Preprocessing

The preprocessing pipeline explores several image enhancement techniques:

- Bilateral Filtering
- CLAHE (Contrast Limited Adaptive Histogram Equalization)
- Gamma Correction

These techniques help improve image quality by reducing noise and enhancing contrast and brightness.

## Model

**MobileNetV2** was used as the main deep learning architecture due to its lightweight and efficient design.

The model was fine-tuned using transfer learning for the four waste categories.

## Results

The baseline model achieved approximately **71.15% accuracy** on challenging samples.

After applying adaptive preprocessing techniques, the classification accuracy improved to approximately **82.69%**.

## Technologies Used

- Python
- PyTorch
- Torchvision
- OpenCV
- MobileNetV2
- Pandas
- Matplotlib
- Jupyter Notebook

## Project File

The complete implementation is available in:

`waste_classifier.ipynb`

## Project Context

This project was developed as an academic team project focused on applying image processing and deep learning techniques to waste classification.
