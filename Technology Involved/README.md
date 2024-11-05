# 1. Drone: Phantom 3 quadcopter

A drone, or an unmanned aerial vehicle (UAV), is an aircraft which is remotely piloted. Drones are originally developed for military purpose. However, nowadays consumer market is also quickly growing for variety fields such as medical, meteorology, science, art, and so on. Phantom 3 fits into your life and makes flying remarkably intuitive and easy. From takeoff to landing, it's completely under your control, responding to your commands while automatically handling the most complex aspects of safe, stable flight. 

![](https://github.com/aamirjarda/Drone-based-Garbage-monitoring-system-for-Swachh-Bharat-/blob/main/Technology%20Involved/Phantom%20Drone.png)

We know that IOT has made the leap from conceptual to actual applications. Drones are rapidly expanding their capabilities beyond military surveillance applications. UAVs are being developed for parcel delivery to the customer’s doorstep, internet provision, disaster surveillance and assistance, and a whole range of hobbyist activities. They play a role in the Internet of Things because they are critically dependent on sensors, antennas and embedded software to provide two way communications for remote control and monitoring.

# 2. Tensorflow

TensorFlow™ is an open source software library for high performance numerical computation. Its flexible architecture allows easy deployment of computation across a variety of platforms (CPUs, GPUs, TPUs), and from desktops to clusters of servers to mobile and edge devices. Originally developed by researchers and engineers from the Google Brain team within Google’s AI organization, it comes with strong support for machine learning and deep learning and the flexible numerical computation core is used across many other scientific domains.

![](https://github.com/aamirjarda/Drone-based-Garbage-monitoring-system-for-Swachh-Bharat-/blob/main/Technology%20Involved/TensorFlow.png)

Companies who uses Tensorflow are Airbnb, AMD, NVIDIA, UBER, SAP, kakao, DeepMind, DropBox, ebay, Google, intel, CocaCola, MI, Qualcomm, twitter, 3DR, ARM, CastBOx, and much more. 

# 3. Machine Learning

Machine learning is the science of getting computers to act without being explicitly programmed. In the past decade, machine learning has given us self-driving cars, practical speech recognition, effective web search, and a vastly improved understanding of the human genome. Machine learning is so pervasive today that you probably use it dozens of times a day without knowing it. Many researchers also think it is the best way to make progress towards human-level AI.

![](https://github.com/aamirjarda/Drone-based-Garbage-monitoring-system-for-Swachh-Bharat-/blob/main/Technology%20Involved/Machine%20Learning.png)

# 4. Deep Learning

Deep Learning is a subfield of machine learning concerned with algorithms inspired by the structure and function of the brain called artificial neural networks. On the off chance that you are simply beginning in the field of Deep learning or you had some involvement with neural systems sometime prior, you might be confused. I know I was confused at first as were a significant number of my partners and companions who learned and utilized neural systems in the 1990s and mid2000s. The pioneers and specialists in the field have thoughts of what Deep learning is and these particular and nuanced viewpoints shed a great deal of light on what Deep learning is about. Deep learning models are vaguely inspired by information processing and communication patterns in biological nervous systems yet have various differences from the structural and functional properties of biological brains, which make them incompatible with neuroscience evidences.

![](https://github.com/aamirjarda/Drone-based-Garbage-monitoring-system-for-Swachh-Bharat-/blob/main/Technology%20Involved/Machine%20Learning%20and%20Deep%20Learning.png)

# 5. Google Inception Model (Google Net)

* A Convolutional Neural Network (CNN, or ConvNet) are a special kind of multi-layer neural networks, designed to recognize visual patterns directly from pixel images with minimal preprocessing GoogleNet has 22 layer, less than Alexnet and much more accurate. Google net Is Convolutional neural network simply trying to learn after train itself from the images, it has stacked CNN layers. Google has train this model with 10m images consists of 1000 different categories, main idea of this model is transfer learning: Transfer learning is a machine learning method where a model developed for a task is reused as the starting point for a model on a second task. The idea of the inception layer is to cover a bigger area, but also keep a fine resolution for small information on the images. So the idea is to convolve in parallel different sizes from the most accurate detailing (1x1) to a bigger one (5x5). Below are the layers of GoogleNet model consists of CNN layers. 

## Convolution Layer

Convolution is a mathematical operation that does the integral of the product of 2 functions(signals), with one of the signals flipped. Convolution basically used in signal processing where different filters are applied like edge detection, blurring and feature extraction. Convolution basically applies on 3-d, 2-d images and is the heart of CNN.

![](https://github.com/aamirjarda/Drone-based-Garbage-monitoring-system-for-Swachh-Bharat-/blob/main/Technology%20Involved/Convolution.png)

Basically google net uses 1*1 convolution model instead of bigger, It helps reduce the cost: Suppose we apply 32 filters (5*5 convolution) in 28*28*192(3d image) then the total operation would be 28*28*32*5*5*192=120m operation and if we apply 1*1 convolution before 5*5 convolution 28*28*192->>>conv(1*1*16)->>>conv(5*5*132)->>>28*28*132, so total calculation would be 28*28*192*16=24m. So Google uses 1*1 convolution instead of much bigger size so that operational cost would be less.

## Pooling

To make images small that computation cost would be less, there are 2 types of pooling MaxPool and Average Pool, example is given below, so it takes 8 from the matrix and discard all other values, so reduces the cost.

![](https://github.com/aamirjarda/Drone-based-Garbage-monitoring-system-for-Swachh-Bharat-/blob/main/Technology%20Involved/Pooling%20Layer.png)

## Fully Connected Layer

It tries all the possibilities before giving the result, basically is Global Feature Extraction.

![](https://github.com/aamirjarda/Drone-based-Garbage-monitoring-system-for-Swachh-Bharat-/blob/main/Technology%20Involved/Fully%20Connected%20Layer.png)

## Relu Layer (Activation Function)

![](https://github.com/aamirjarda/Drone-based-Garbage-monitoring-system-for-Swachh-Bharat-/blob/main/Technology%20Involved/All%20Negative%20values%20become%20zero.png)

From the picture above, observe that all positive elements remain unchanged while the negatives become zero. Also the spatial information and depth are the same. Thinking about neural networks, it's just a new type of Activation function, but with the following features:

1.  Easy to compute (forward/backward propagation).
2.  Suffer much less from vanishing gradient on deep models.
3.  A bad point is that they can irreversibly die if you use a big learning rate.

![](https://github.com/aamirjarda/Drone-based-Garbage-monitoring-system-for-Swachh-Bharat-/blob/main/Technology%20Involved/Inception%20Modules.png)

# References

* [1] https://us.tomonews.net
* [2] https://www.dji.com/phantom-3-pro 
* [3] https://www.tensorflow.org/ 
* [4] https://www.toptal.com/machine-learning/tensorflow-python-tutorial 
* [5] https://evrythng.com/machine-learning-and-the-digital-supply-chain/ 
* [6] https://semiengineering.com/deep-learning-spreads/ 
* [7] https://en.wikipedia.org/wiki/Convolutional_neural_network 
* [8] https://www.slideshare.net/ckmarkohchang/applied-deep-learning-1103-convolutional neural-networks 
* [9] https://leonardoaraujosantos.gitbooks.io/artificial-inteligence/content/relu_layer.html 
* [10] https://medium.com/@siddharthdas_32104/cnns-architectures-lenet-alexnet-vgg-googlenet resnet-and-more-666091488df5 


