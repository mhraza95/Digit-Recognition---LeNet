# Digit-Recognition-LeNet
Digit Recognition using LeNet – Convolutional Neural Network in Python
## The LeNet architecture
<img src="https://github.com/mhraza95/Digit-Recognition-LeNet/blob/master/lenet_architecture-768x226.png" />

The LeNet architecture is an excellent “first architecture” for Convolutional Neural Networks (especially when trained on the MNIST dataset, an image dataset for handwritten digit recognition).

LeNet is small and easy to understand — yet large enough to provide interesting results. Furthermore, the combination of LeNet + MNIST is able to run on the CPU, making it easy for beginners to take their first step in Deep Learning and Convolutional Neural Networks.

In many ways, LeNet + MNIST is the “Hello, World” equivalent of Deep Learning for image classification.

The LeNet architecture consists of the following layers:
LeNet - Convolutional Neural Network in Python

INPUT => CONV => RELU => POOL => CONV => RELU => POOL => FC => RELU => FC

## Creating the LeNet driver script

Now that we have implemented the LeNet Convolutional Neural Network architecture using Python + Keras, it’s time to define the lenet_mnist.py
  driver script which will handle:

    Loading the MNIST dataset.
    Partitioning MNIST into training and testing splits.
    Loading and compiling the LeNet architecture.
    Training the network.
    Optionally saving the serialized network weights to disk so that it can be reused (without having to re-train the network).
    Displaying visual examples of the network output to demonstrate that our implementaiton is indeed working properly.


## Training LeNet with Python and Keras

you can train LeNet on MNIST by executing the following command:

LeNet - Convolutional Neural Network in Python

<code> $ python lenet_mnist.py --save-model 1 --weights output/lenet_weights.hdf5 </code>

<img src="https://github.com/mhraza95/Digit-Recognition-LeNet/blob/master/Capture%2001.PNG" />
<img src="https://github.com/mhraza95/Digit-Recognition-LeNet/blob/master/Capture%2002.PNG" />
<img src="https://github.com/mhraza95/Digit-Recognition-LeNet/blob/master/Capture%2003.PNG" />


