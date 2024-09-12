# ConvNets-with-Keras
In this project we design and evaluate Convolutional Neural Networks using Keras. The goal of this project is to implement a CNN to classify the images of CIFAR-10 dataset. This dataset consists of 60,000 colour images of 32x32 pixels that are classified into 10 classes: airplane, automobile, bird, cat, deerm dog, frog, horse, ship and truck. 

## Exercise 1: Implement a VGG-16 CNN to perform the clssification
We implement the VGG-16 CNN varying the number of images used and the learning rate. 

## Exercise 2: Introduce a ResNet-like approach to VGG-16
- For each convolutional block after the firts Max-Pooling, include a residual connection within each convolutional block that adds the result of the first Conv2D with the last Conv2D of that block without activation function.
- Apply the activation funtion to the previous sum.
- To analyze the performance of this network consider two datasets for training. During training we will use different learning rates.

