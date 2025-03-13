## DCGAN for Generating CelebA Faces



This project implements a Deep Convolutional Generative Adversarial Network (DCGAN) using PyTorch to generate realistic human faces based on the CelebA dataset.

# Dataset
The model is trained on the CelebA dataset, which consists of celebrity face images.

# Setup & Dependencies

This implementation requires the following dependencies:

Python
PyTorch
torchvision
Matplotlib
Kaggle (for accessing datasets)

# Project Structure

1. Dataset Loading & Preprocessing
    *Reads the CelebA dataset and applies transformations (resize, normalize).
   
2. Model Architecture
    *Generator: Transforms random noise into realistic images.
    *Discriminator: Classifies images as real or fake.
   
3. Training Pipeline
    *Uses Binary Cross-Entropy Loss (BCELoss).
    *Adam Optimizer for both Generator and Discriminator.
    *Outputs generated images after each epoch.

# Output
1. Trained model generates human-like faces.
2. Output images are saved/displayed after each epoch.

# References

-- DCGAN Paper: Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks
-- CelebA Dataset: CelebA Project Page  

Thank You !
