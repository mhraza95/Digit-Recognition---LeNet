# Digit-Recognition-LeNet
Digit Recognition using LeNet – Convolutional Neural Network in Python
## The LeNet architecture 😍

<img src="https://github.com/mhraza95/Digit-Recognition-LeNet/blob/master/lenet_architecture-768x226.png" />

The LeNet architecture is an excellent “first architecture” for Convolutional Neural Networks (especially when trained on the MNIST dataset, an image dataset for handwritten digit recognition).

LeNet is small and easy to understand — yet large enough to provide interesting results. Furthermore, the combination of LeNet + MNIST is able to run on the CPU, making it easy for beginners to take their first step in Deep Learning and Convolutional Neural Networks.

In many ways, LeNet + MNIST is the “Hello, World” equivalent of Deep Learning for image classification.

The LeNet architecture consists of the following layers:
LeNet - Convolutional Neural Network in Python

INPUT => CONV => RELU => POOL => CONV => RELU => POOL => FC => RELU => FC

## Creating the LeNet driver script 👇

Now that we have implemented the LeNet Convolutional Neural Network architecture using Python + Keras, it’s time to define the lenet_mnist.py
  driver script which will handle:

    1. Loading the MNIST dataset.
    
    2. Partitioning MNIST into training and testing splits.
    
    3. Loading and compiling the LeNet architecture.
    
    4. Training the network.
    
    Optionally saving the serialized network weights to disk so that it can be reused (without having to re-train the network).
    Displaying visual examples of the network output to demonstrate that our implementaiton is indeed working properly.

Three optional command line arguments, each of which are detailed below: 👇

    --save-model
     : An indicator variable, used to specify whether or not we should save our model to disk after training LeNet.
     
    --load-model
     : Another indicator variable, this time specifying whether or not we should load a pre-trained model from disk.
     
    --weights
     : In the case that --save-model
      is supplied, the --weights-path
      should point to where we want to save the serialized model. And in the case that --load-model
      is supplied, the --weights
      should point to where the pre-existing weights file lives on our system.


## Training LeNet with Python and Keras 🤗

you can train LeNet on MNIST by executing the following command:

LeNet - Convolutional Neural Network in Python

<code> $ python lenet_mnist.py --save-model 1 --weights output/lenet_weights.hdf5 </code>

## Training Model Screenshot 💻

<img src="https://github.com/mhraza95/Digit-Recognition-LeNet/blob/master/Capture%2001.PNG" />
<img src="https://github.com/mhraza95/Digit-Recognition-LeNet/blob/master/Capture%2002.PNG" />

## Digit Prediction Screenshot 💻

<img src="https://github.com/mhraza95/Digit-Recognition-LeNet/blob/master/Capture%2003.PNG" />

## Recommended Reading

<a target="_blank" href="https://coderzpy.com/cnn-architectures-lenet-alexnet-vgg-googlenet-resnet-and-more/"> CNN Architectures </a>

## Follow Me ❤😊

If you like my post please follow me to read my latest post on programming and technology.

<a target="_blank" href="https://coderzpy.com/"> coderzpy.com </a>

<a target="_blank" href="https://www.instagram.com/coderz.py/"> Instagram </a>

<a target="_blank" href="https://www.facebook.com/coderz.py"> Facebook </a>
