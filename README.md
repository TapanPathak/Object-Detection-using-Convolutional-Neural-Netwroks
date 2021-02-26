# Deep Learning Based Object Detection Using Convolutional Neural Netwroks

This project is small implementation of **On-Device DL-based Techniques** discussed in State Of The Art in the paper <https://arxiv.org/abs/2009.09065> 

***
**Aim:** Here we adopt On-Device Deep Learning-based approach for Object Detection ( A Use Case of Smart Doorbell). This approach employs various
model reduction techniques (e.g., model compression, parameter pruning) to enable its deployment on IoT devices, while maintaining a reasonably good object detection accuracy. The current implementation uses DenseNets, which is a family of computer vision models for TensorFlow, designed for resource-constrained devices such as mobile phones and embedded devices.
***
**Technologies/Concepts/Librabries Used :**
1. Fine Tuning 
2. Transfer Learning
3. CNN
4. TensorFlow
5. TensorFlow Lite
6. Keras
7. OpenCv
8. Numpy, Matplotlib

***
**Why Use TensorFlow Lite ?**

TensorFlow Lite is a set of tools to help developers run TensorFlow models on mobile, embedded, and IoT devices. It enables on-device machine learning inference with low latency and a small binary size. TensorFlow Lite is designed to make it easy to perform machine learning on devices, "at the edge" of the network, instead of sending data back and forth from a server.
***

**Dataset**

We have used our custom Dog and Cat dataset to train DenseNet TensorFlow Model. Dataset can be found here <http://temp.endeavourindustries.in/Dataset.zip>

***
**Working**

**Objective :** Given an input image. Identify whether it is a Cat or a Dog using Deep Learning.

1. We load pre-trained DenseNet Model.
2. Then using Fine Tuning and Transfer Learning, we train the model with our own dataset.
3. After Training, we measure the accuracy for TensorFlow Model.
4. We then convert Tensorflow Model to Tensorflow Lite Model.
5. Measure the accuracy for TensorFlow Lite Model.

***
**How to Run?**

Download or Import the [Colab](https://github.com/TapanPathak/Object-Detection-using-Convolutional-Neural-Netwroks/blob/main/Deep_Learning_Based_Object_Detection_Using_Convolutional_Neural_Networks.ipynb) and run it in Google Colab Only.
