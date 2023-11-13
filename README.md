# Neural-Nets---Keras-CIFAR10-CLassification

Project 01-  Build an ANN to Recognize Images using TensorFlow and Keras 

CONCEPT

In this project, we will be building a Keras model from scratch to do some image classification. We're going to train our model and formulate our research question. Our goal is to build our image classifier, and it's going to classify ten different things. It will differentiate among dogs, ships, horses, frogs, deer, cats, trucks, cars, planes, and birds. In total, we're going to have ten different classes. And the simple model that we will use artificial neural network called Multi-layer Perceptron. It's one of the simplest kinds of neural networks. So we gather our data, clean our data process our data, explore and visualize some of the data. And then we're going to train our neural network on our local machine. And finally, we're going to evaluate how we're doing.

Data
The image data set that we'll be using in this module is called CIFAR10. It contains 60,000 images from ten different classes, including things like ships, horses, and trucks. It's a data set that's commonly used to train image recognition models, and that's exactly what we’ll do to get the data. The dataset is divided into five training batches and one test batch, each with 10000 images. The test batch contains exactly 1000 randomly selected images from each class. The training batches contain the remaining images in random order, but some training batches may contain more images from one class than another. Between them, the training batches contain exactly 5000 images from each class.


PROCESS

To build an ANN model to recognize images we followed the process that looks at images using the following steps: 

GATHER DATA: We used the CIFAR10 dataset from Keras. Downloading data from Keras https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz

 EXPLORE AND CLEAN DATA: We've set out to classify images according to ten different categories or classes. Then we should have to split into training and testing data. After splitting our data our task is to this data cleaning, preprocessing, and exploration stage.
Reshaping the train and test data.
Then we split our training data into two datasets. The validation dataset is also part of the training dataset. 
MODEL BUILD: We will follow a three-step process to build and construct your model. The first step is defining our model. So we have to set out the structure of the model. Step two is compiling the model, and that means telling TensorFlow in advance how we measure the loss, and what kind of calculations should run to adjust the weights. And the Final step in how we fit our model. During this step, TensorFlow will crunch through the data and do all the calculations.
Balance model overfitting or model and under fitting. We used Regularization techniques like early stopping and dropout to solve this problem. 
MODEL PREDICTION: in model prediction, we tried to predict the actual image and the predicted image for the first 10 images in the valuation dataset.
EVALUATION: Now we evaluate our model. We use 3 classifiers one Recall Score, the second is Precession, and the Final is F1 Score. Finally, we plot a concussion matrix.
