## Self Driving Car

In this project I worked on a temporal dataset of images taken by the front camera of a car, and the corresponding angles of the steering. I tried to predict the angle of the steering according to the forecam image with a Convolutional Neural Network (CNN) architecture. This is a regression problem.

**Test and Training Set Division of the dataset**

I worked on the [Dataset 1](https://github.com/SullyChen/driving-datasets), which originally contains approximately 45,500 images, sizes up 2.2GB. 30,000 out of 45,000+ data points are used to train and test the model. 24,000 data points are used for training and 6,000 for testing the model.

**Network Architecture** 

The network architecture used in the proposed approach is inspired by [NVIDIA Corporation](https://arxiv.org/pdf/1604.07316.pdf).

![alt text](https://github.com/tintin85/Self-Driving-Car/blob/master/nividia%20cnn.png)

**Experimental Setup**

Experiments are conducted with Python3 with the help of certain libraries like Keras, OpenCV, NumPy, Matplotlib, Pandas. Program is written on Jupyter Notebook with Tensorflow back-end on an HP laptop with 64-bit Ubuntu 16.04 LTS operating system, Intel Core i3-5005U CPU @ 2.00GHz × 4, 8 GB of RAM.

**Result**

The model predicts the steering angles for the test images taken by the front camera of the car. A CSV file is generated to store the original test angles (in degree) and the corresponding predicted angles (in degree).

