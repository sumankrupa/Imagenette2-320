# Image Classification with Deep Learning

## Overview
This project focuses on **image classification** using deep learning models implemented in **PyTorch**. The models are trained on the **Imagenette dataset**, a smaller subset of ImageNet, to classify images into 10 categories.

## Models Used
We evaluate multiple deep learning architectures:
- **VGG-16**: A deep convolutional neural network (CNN) with 16 layers.
- **ResNet-34**: A residual neural network with skip connections to prevent vanishing gradients.
- **MobileNet**: A lightweight CNN optimized for mobile and embedded devices.
- **DenseNet-121**: A densely connected CNN that improves parameter efficiency.

## Dataset
- **Source**: Imagenette (subset of ImageNet)
- **Classes**: 10 categories, including:
  - Tench
  - English Springer
  - Cassette Player
  - Chainsaw
  - Church
  - French Horn
  - Garbage Truck
  - Gas Pump
  - Golf Ball
  - Parachute
- **Preprocessing**:
  - Resized images to **256x256** pixels
  - Converted to tensors using `torchvision.transforms`
  - Split into **training, validation, and test sets**



Metrics include:
- **Accuracy**
- **Loss curves**
- **Confusion matrix**
- **ROC curve**

## Results
The project compares multiple architectures in terms of:
- **Training and validation accuracy**
- **Loss trends over epochs**
- **Performance on test data**
