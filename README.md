# Car Recognition using Deep Learning (Demo)

## Overview
This repository demonstrates a Convolutional Neural Network (CNN) implementation for binary car image classification. The model architecture is designed for large-scale deployment while providing a demo version for quick evaluation.

## Demo Version
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/13Vz2sKiiXK_Cc5kvVeUT9_IWbAOz1Ul6?usp=sharing)

The demo notebook includes:
- Custom CNN architecture optimized for production use
- Data augmentation techniques
- Transfer learning implementation with VGG16
- Comprehensive performance visualization

## Quick Start
1. Open the demo notebook in Google Colab using the badge above
2. All dependencies and demo data will be automatically set up
3. Run all cells to see the model in action

## Model Architecture
The project implements a production-grade CNN with:
- 4 convolutional blocks with increasing complexity (64→512 filters)
- Batch Normalization for training stability
- Strategic dropout layers for regularization
- Optimized for large-scale deployment (2000+ images)

## Results
- Demo Version: Limited performance due to small dataset
- Full Project: 90.45% validation accuracy on 2,176 images

## Dependencies
- TensorFlow
- NumPy
- Matplotlib

## Note
The demonstration version uses a small dataset for quick testing. The architecture is optimized for large-scale deployment and will improve performance with larger datasets.

## Author

