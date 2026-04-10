# CNN_Encoder_Decoder
This project builds a CNN Encoder-Decoder autoencoder for image reconstruction on CIFAR-10. It combines convolution, dense blocks, and residual blocks to learn compact image features and reconstruct them with low MSE. Created for studying deep learning architectures and feature representation.

# CNN Encoder-Decoder for Image Reconstruction

This project implements a CNN Encoder-Decoder autoencoder for reconstructing images from the CIFAR-10 dataset using TensorFlow/Keras. The model is designed to learn compact feature representations and then reconstruct the original images as accurately as possible.

## Purpose
This notebook was created to study how encoder-decoder architectures work in deep learning, especially for image reconstruction tasks. It also explores how Dense Blocks and Residual Blocks can improve feature extraction and reconstruction quality.

## What the project does
- Loads and preprocesses the CIFAR-10 dataset
- Builds an Encoder-Decoder autoencoder
- Uses convolution layers for feature extraction
- Applies Dense Blocks to preserve and combine learned features
- Uses Residual Blocks to refine representations
- Trains the model with MSE loss
- Reconstructs test images and compares them with the originals
- Visualizes training and validation loss

## Model Highlights
- **Encoder:** Extracts important image features from input images
- **Dense Block:** Reuses and concatenates features from previous layers
- **Residual Block:** Helps refine features by learning residual mappings
- **Decoder:** Reconstructs the image back to its original size
- **Output Layer:** Uses sigmoid activation for normalized pixel output

## Why this project is useful
This project is useful for:
- learning the basics of autoencoders
- understanding encoder-decoder architectures
- studying Dense and Residual connections in CNNs
- experimenting with image reconstruction and feature compression
- serving as a foundation for more advanced tasks such as denoising, compression, or representation learning

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## Dataset
- CIFAR-10

## Output
The notebook shows:
- reconstructed images compared with original images
- training and validation loss curves
- final reconstruction performance using MSE
