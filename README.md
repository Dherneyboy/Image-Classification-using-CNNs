# CIFAR-10 Image Classification using Convolutional Neural Networks (CNNs)

## Overview
This project aims to develop a model to classify images from the CIFAR-10 dataset into one of ten categories. The dataset includes images of airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks.

## Process Outline

### Data Collection and Preparation:

•	The CIFAR-10 dataset is collected and loaded.

•	Each image is 32x32 pixels with RGB channels.

•	The dataset is divided into 50,000 training images and 10,000 testing images.

### Exploratory Data Analysis (EDA):

Visualize sample images and their corresponding labels to understand the dataset’s structure and distribution.

### Data Preprocessing:

•	Normalize pixel values to a range of 0 to 1.

•	Convert class labels into one-hot encoded format.

### Model Architecture:

### Design a CNN with:

•	Convolutional layers to extract features.

•	Pooling layers to reduce dimensionality.

•	Dense layers for classification.

•	Dropout layers to prevent overfitting.

### Model Training:

•	Compile and train the model using the training dataset.

•	Use categorical cross-entropy loss and RMSprop optimizer1.

## Tools Used

#### Programming Language: Python

#### Libraries: Pandas, Numpy, Matplotlib, Sklearn, seaborn, TensorFlow, and Keras.

#### Processes: Exploratory Data Analysis (EDA), one hot encoding, Scaling, Machine Learning, Convolutional Neural Network (CNN)

## Model Evaluation and Result

A Convolutional Neural Network was used to classify images into 10 categories. The data below shows the classification report from the model.

![image](https://github.com/Dherneyboy/Image-Classification-using-CNNs/assets/148950017/82198a42-6764-41b2-aa10-26b77bc3504c)



 <img width="482" alt="image" src="https://github.com/Dherneyboy/Image-Classification-using-CNNs/assets/148950017/c7890f07-94a9-4fd4-9c28-05b6a0b22c2d">

 
## Conclusion

This study employed a Convolutional Neural Network (CNN) to classify images into 10 categories. With an accuracy of approximately 70%, our model demonstrates promising performance.


