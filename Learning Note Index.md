# Learning Note of Convolutional Neural Networks

## Abstract

### Background

* Growth in the amount of the annotated data(标注数据)
* Great improvements in the strengths of graphics processor units(图形处理单元GPU)

### Aspects

* Layer design
* activation function
* loss function
* regularization
* optimization
* fast computation

### Appications

* Computer vision
* Speech
* Natural language processing

## Introduction

### CNN History

Scientists inspired by the cells in animal visual cortex and proposed the neocognitron which be regarded as the predecessor of CNN

LeCun and others established the modern frameworl of CNN, and developed a multi-layer artificial neural network(ANN 人工神经网络) called LeNet-5 followed.

It's advantage is that it can obtain effective representations of original image. So with little-to-none preprocessing, it is possible to recognize visual patterns(视觉形态) from raw pixels directly.

It's disadvantage is that it had difficulty dealing with lack of large training data in that low computing power background.

There are more and more Net were proposed and the depth is also increasing. By this, the network has better feature representations and can better approximate the target function. But ensued it increases the complexity of the network and make it more difficult to optimize and easier to get overfitting.

So various methods have been proposed to deal with thest problems.

![0](./Hierarchically-structured.png '描述')

### Basic CNN Components

#### Three type of layers

* convolutional layer
* pooling layer
* fully-connected layer

### Improvements on CNNs

#### aspects

* convolutional layer
* pooling layer
* activation function
* loss function
* regularization
* optimization

#### Convolution layer

* Tiled Convolution
* Transposed Convolution
* Dilated Convolution
* Network in Network
* Inception Module

