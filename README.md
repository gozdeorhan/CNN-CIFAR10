# CIFAR-10 Image Dataset Multiclass Clasification          

This work consists of a deep learning model for the well-known color image classification problem, **CIFAR-10.**, utilizing convolutional neural networks.

As an initial work, a simple deep learning model is built and through building more advanced models by *adding layers, tuning size's of layers, use of regularizers, utilizing dropout and batch normalization*, the boundary of overfitting is aimed. The model aims to predict the classes of images with high accuracy while maintaining a low loss value. 

## Problem Definition and Dataset

The model is concerned with a well-known deep learning problem of classifying colour images. It is trying to predict the classes of colored images. One of the available datasets for this model is named CIFAR-10 which consists of:

- 60000 32x32 colour images 
- in 10 classes, 
- with 6000 images per class. 

There are **50000 training images** and **10000 test images**. Since there are 10 classes and and a single label to be used for each image, CIFAR-10 is considered to be a **multiclass classification problem.**
