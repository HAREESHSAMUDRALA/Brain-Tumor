# Image Enhancement Using Deep Learning

This project implements an **Enhanced Super-Resolution Convolutional Neural Network (SRCNN)** for improving the quality of low-resolution images.

## Objective

The model learns to reconstruct **128×128 high-resolution grayscale images** from **64×64 low-resolution images**.

## Methodology

* Dataset: Images sourced from Kaggle
* Input: 64×64 grayscale images
* Target: 128×128 grayscale images
* Model: Enhanced SRCNN with 4 convolutional layers
* Activations: ReLU
* Batch Normalization used in intermediate layers
* Loss: Mean Squared Error (MSE)
* Optimizer: Adam
* Learning Rate: `1e-4`
* Epochs: `10`

## Evaluation

The model is evaluated using:

* **PSNR** – measures reconstruction quality
* **SSIM** – measures structural similarity

The PSNR improved from approximately **26 dB to 27.75 dB** during training.

## Result

The trained Enhanced SRCNN successfully improves the quality of low-resolution images through deep-learning-based super-resolution.
