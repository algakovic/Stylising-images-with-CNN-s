# Artistic Stylisation Using CNN and VGG19

## Executive Summary
This project uses Convolutional Neural Networks (CNN's) and a pre-trained CNN for style transfer aka a Visual Geometry Group(VGG-19)
An Image and a styling image are provided to the model, which in turn produces a new image, a merge of the image and the style.

The VGG is a CNN model proposed by K.Simonyan and A.Zisserman in their paper "Very Deep Convolutional Networks for Large-Scale Image Recognition"
VGG-19 uses sixteen convolutional layers with ReLU non-linearity. Five pooling layers are interweaved between the convolutional layers and the model culminates in three fully connected layers.

The content and style of the resulting image can be extracted from the various layers in this network.

## Contents
1. Importing libraries and Modules
2. Preparation of images for VGG19 neural network