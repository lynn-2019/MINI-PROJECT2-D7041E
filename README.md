# MINI-PROJECT2-D7041E

## Datasets

In our mini-project, we have dealt with two data sets and two algorithms.

The first dataset we want to use is an "ISIC Challenge" dataset from the Department of Dermatology at the Medical University of Vienna. This contains a test and a training dataset with images of skin lesions and a csv file for the training data. We use the Task 3 dataset from 2018. The goal is to classify the images into 7 classes. Unfortunately, the images were too large to save in Git, so you will have to download them yourself.
https://challenge.isic-archive.com/data/#2018

The second dataset is from the uci machine learning repository and contains data for 1593 handwritten digits. The digits have the range from 0 to 9 and the goal is to classify them. 
https://archive.ics.uci.edu/dataset/178/semeion+handwritten+digit

## Algorithms

We use MLP and CNN as algrithms

A multilayer perceptron (MLP) is a type of artificial neural network that consists of at least three layers: an input layer, at least one hidden layer, and an output layer. In an MLP, neurons are connected in successive layers, and each connection has an associated weight. The network learns to recognize patterns and relationships in the data by adjusting the weights during the training process.

A Convolutional Neural Network (CNN) is a special type of neural network that is particularly suitable for processing images. It uses convolutional layers to extract local features of an image and pooling layers to reduce dimensionality. CNNs are often used in image recognition tasks and have achieved great success due to their feature extraction capability at different levels.

For each dataset, we apply both algorithms and tune their hyperparameters by testing several combinations of hyperparameters using random and grid search and evaluating their performance on the validation dataset. At the end, the best model is tested and the metrics Accuracy and F1 Score are calculated and the Confusion Matrix is plotted.

## Replication of the results

If you want to reproduce the results, we recommend using the second dataset, as all the data is available in GitHub and the first data set was unfortunately too large to be uploaded to this repository. If you decide to do so, you can simply run the Jupyter Notebook files.
However, if you also want to test the first data set, you will need to download the training and test data as well as their ground truth from the linked website under Task 3.  The training images must be saved in the folder "FirstDataset-ISIC" and its subfolder "ISIC2018_Task3_Training_Input" and the test images in the subfolder "ISIC2018_Task3_Test_Input". The ground truth csv files are only saved in the "FirstDataset-ISIC" folder. The validation dataset does not need to be downloaded, as we create it from the training data using cross fold. After those steps, you should be able to execute the Jupyter Notebook files.

## Links & Contacts

You Tube:
https://youtu.be/8128hGU7jig

Authors: Lynn Habermann (lynhab-3@student.ltu.se) & Conrad Reintjes (conrei-3@student.ltu.se)
