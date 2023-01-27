# Facial-Emotion-Recognition

## Problem statement
* Given images of people posing 7 emotions 'Angry','Disgust','Fear','Happy','Sad','Surprise','Neutral'.
* Build a model using CNN for classifying the emotions of face

## Dataset Description
* Given Image pixel values,emotions and usage of Data.Total Dataset contains 35887 images.
* Dataset contains images of training,PublicTest,Private Test

## Model Building
* Import Required Libraries
* Load the dataset
* Inference from dataset
  * Type of columns
  * Shape of dataset
  * Info about dataset
* Missing Values Check
* Data Distribution check
* Split the dataset into training,validation testing as per usage in Dataset
    * Training images : 28709
    * PublicTest images : 3589
    * PrivateTest images : 3589
* Convert labels into OneHotEncoding form
* Convert pixels into numpy array 
* Normalize the pixels
* Visualize the dataset
* Create Training ,Validation and Testing Data Generators using Keras ImageDataGenerator function
* Design a Convolutional Neural Network (CNN) Model
* Compile the Model using Adam optimizer, categorical_crossentropy loss function, and accuracy metric
* Print the Model summary
* Train the Model with batch_size = 64 & epochs = 100
* Evaluate the Model 
* Print a Classification Report and the accuracy score (classification accuracy)
* Display a Confusion Matrix to evaluate the performance of the model



