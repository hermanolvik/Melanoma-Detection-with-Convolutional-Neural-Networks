# Melanoma Detection with Convolutional Neural Networks

## Overview
This project explores the use of **Convolutional Neural Networks (CNNs)** for detecting melanoma, a dangerous type of skin cancer. The study evaluates **custom CNN architectures** and a **pre-trained ResNet-18 model**, using the **2018 ISIC dataset**. The aim is to assess different deep learning techniques such as:
- Layer normalization
- Data augmentation
- Residual connections
- Transfer learning (ResNet-18)

The project was conducted as part of the **DAT341 - Applied Machine Learning** course at **Chalmers University of Technology**. Read the full report in the PDF in this repo.

## Results
- **Layer Normalization** significantly improved accuracy.
- **Residual connections** had a smaller-than-expected impact.
- **ResNet-18 outperformed all custom models**, likely due to its pre-trained weights and built-in normalization techniques.
- **Dataset bias** (favoring fair-skinned individuals) may impact generalizability.

## Limitations
- **Limited computational resources**: Training was performed on student laptops, requiring optimizations like lower image resolutions (128×128 instead of 224×224).
- **Time constraints**: Only one week for training and evaluation.
- **Dataset bias**: The ISIC dataset lacks diversity, which may reduce effectiveness on darker skin tones.

## Project requirements/dependencies
- Python 3.8+
- Jupyter Notebook
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- OpenCV (for image processing)

### Contact
- Herman Olvik: olvik@chalmers.se
- Cornelia Swartling: corswa@chalmers.se

## References
- ISIC 2018 Dataset: [challenge.isic-archive.com](https://challenge.isic-archive.com/data/2018)
- PyTorch ResNet-18: [pytorch.org](https://pytorch.org/vision/main/models/generated/torchvision.models.resnet18.html)
