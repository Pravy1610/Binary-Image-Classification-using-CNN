# Binary-Image-Classification-using-CNN
Program Outline:    
The Binary Image Classification is a computer vision project aiming to build a machine-learning model to classify images into two distinct classes.
With the help of the effective use of Neural Networks (Deep Learning Models), binary classification problems can be solved fairly.
For this project, I use Convolution Neural Network(CNN). It is a class of Neural networks that have proven very effective in areas of image recognition, processing,
and classification. The CNN model requires training data for training weights and validation to check its performance.
We use Food101 dataset for this project. It is a collection of 101 different categories of 101,000 (1000 images per category) real-world images of food dishes. 
For each class, 250 manually reviewed test images are provided as well as 750 training images. In this project, I use two of the categories, pizza and steak, and 
build a binary image classifier using CNN.   


Program Structure:
1. Data Collection and Preprocessing-->
   Obtain a dataset of binary labelled images. Here data preparation and preprocessing steps such as , moving the images into different subset folders, have been done
   in the dataset.
2. Exploratory Data Analysis-->
   Perform data exploration to understand the characteristics of the dataset. The file has been divided into train set and test set. The train set contains all of the images in the training dataset with subdirectories each named after a certain class containing images of that class. The test set also has a same struture as that of train set. Visualizing some sample random images from each class to gain insights into the data. Here we find that  we have a collection of 750 training images and 250 testing images of pizza and steak in this dataset.
3. Model Selection --> For this data I choose Convolutional Neural Networks(CNNs) machine learning algorithms.
   Architecture of a CNN
   (i) Input images from which we draw patterns from
   (ii) Input layer which takes in input images and preprocesses them for further layers
   (iii) Convolution layer which extract the important features from the input images
   (iv) Hidden activation-- this adds non-linearity to the learned features usually ReLU
   (v) Pooling layer	which reduces the dimensionality of learned image features
   (vi)	Fully connected layer-- This further refines learned features from convolution layers
   (vii) Output layer--Takes learned features and outputs them in shape of target labels
   (viii) Output activation -- Adds non-linearities to output layer
    
4. Build the model --> Fine-tune hyperparameters to improve model performance.
5. Evaluate the model --> Evaluate the model on the testing data to measure its accuracy and other relevant metrics. 
6. Model Optimization-->If the model performance is not satisfactory, consider strategies for model optimization, such as data augmentation, transfer learning, or regularization techniques.
Data Augmentation was done to prevent overfitting of the model. Data augmentation is the process of altering our training data, leading to it having more diversity and in turn, allowing the model to learn more generalizable patterns. Altering might mean adjusting the rotation of an image, flipping it or cropping it. Data augmentation is usually only performed on the training data.
7. Conclusion--> Acheived 76% accuracy on data.

