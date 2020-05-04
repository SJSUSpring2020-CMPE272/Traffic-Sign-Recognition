## Traffic Sign Recognition using Convolutional Neural Network

#### Convolutional Neural Networks

The image processing in CNNs is done by processing input images through following layers:

#### Convolutional Layer 
The convolutional layer is the key component of convolutional neural networks and the first layer. Its primary purpose is to detect the presence of a set of features in the images received as input. Each feature is identified as a filter. Hence, the convolutional layer receives several images as input, and calculates the convolution of each of them with each filter.

#### Pooling layer 
This layer is placed between two layers of convolution. The pooling operation consists of reducing the size of the images while preserving their important characteristics. The pooling layer reduces the number of parameters and calculations in the network. This improves the efficiency of the network and avoids over-learning.

#### ReLU correction layer 
ReLU (Rectified Linear Units) indicates real non-linear function defined by ReLU(x)=max(0,x). The ReLU correction layer replaces all negative values received as inputs by zeros. It acts as an activation function.

#### Fully-Connected layer
The fully-connected layer is always the last layer of a neural network. This layer receives an input vector and produces a new output vector. In order to perform this operation, it applies a linear combination and then possibly an activation function to the input values received. The fully-connected layer classifies the image as an input to the network. It returns a vector of size N, where N is the number of classes in our image classification problem. Each element of the vector indicates the probability for the input image to belong to a class.

#### Abstract
There are several different types of traffic signs like speed limits, no entry, traffic signals, turn left or right, children crossing, no passing of heavy vehicles, etc. Traffic signs classification is the process of identifying which class a traffic sign belongs to and building a deep neural network model that can classify traffic signs present in the image into different categories. 

In our model, the datasets containing images of different classes are used to train the algorithm. The model is used to test the data for accuracy and is saved. This model is used to predict the class of the image. The user sends the image through a frontend interface through a REST API POST request. The request is directed to the server and processed. The class of the image is predicted and displayed to the user on the dashboard. With this model, we are able to read and understand traffic signs which are a very important task for all autonomous vehicles.

#### Goal
Detecting and recognizing emerging traffic signs for the smooth functioning of autonomous vehicles

#### Architecture Diagram:
![CNN Architecture Diagram](https://github.com/SJSUSpring2020-CMPE272/Traffic-Sign-Recognition/blob/master/images/arch1.jpeg)

![Architecture Diagram](https://github.com/SJSUSpring2020-CMPE272/Traffic-Sign-Recognition/blob/master/images/arch2.jpeg)


#### Technology Stack
1. Frontend : React
2. Backend  : Flask, Python
3. Machine Learning Model : Convolutional Neural Networks
4. Libraries : Tensorflow, Keras, Scikit-Learn, Pandas, Numpy




