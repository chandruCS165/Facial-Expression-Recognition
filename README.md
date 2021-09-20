# Facial-Expression-Recognition

The data consists of 48x48 pixel grayscale images of faces. The objective is to classify each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). You will use OpenCV to automatically detect faces in images and draw bounding boxes around them. Once you have trained, saved, and exported the CNN, you will directly serve the trained model to a web interface and perform real-time facial expression recognition on video and image data. 

# Project Structure
The hands on project on Facial Expression Recognition is divided into following tasks:

# Task 1: Introduction and Overview
Introduction to the data and and overview of the project.

See a demo of the final product you will build by the end of this project.

Introduction to the Rhyme interface.

Import essential modules and helper functions from NumPy, Matplotlib, and Keras.

# Task 2: Explore the Dataset
Display some images from every expression type in the Emotion FER dataset.

Check for class imbalance problems in the training data.

# Task 3: Generate Training and Validation Batches
Generate batches of tensor image data with real-time data augmentation.

Specify paths to training and validation image directories and generates batches of augmented data.

# Task 4: Create a Convolutional Neural Network (CNN) Model
Design a convolutional neural network with 4 convolution layers and 2 fully connected layers to predict 7 types of facial expressions.

Use Adam as the optimizer, categorical crossentropy as the loss function, and accuracy as the evaluation metric.

# Task 5: Train and Evaluate Model
Train the CNN by invoking the model.fit() method.

Observe live training loss and accuracy  plots in Jupyter Notebook for Keras.
