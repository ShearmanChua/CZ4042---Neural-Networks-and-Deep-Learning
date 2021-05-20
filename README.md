# CZ4042---Neural-Networks-and-Deep-Learning

Python Notebooks for Assignment 1 & Assignment 2 of NTU Com Sci CZ4042 - Neural Networks and Deep Learning. As well as the Python Notebooks for group assignment.

## Assignment 1

### Part A: Classification Problem

This project aims at building neural networks to classify the Cardiotocography dataset containing measurements of fetal heart rate (FHR) and uterine contraction (UC) features on 2126 cardiotocograms classified by expert obstetricians. The dataset can be obtained from: https://archive.ics.uci.edu/ml/datasets/Cardiotocography.

### Part B: Regression Problem

This assignment uses the data from the Graduate Admissions Predication. The dataset contains several parameters like GRE score (out of 340), TOEFL score (out of 120), university Rating (out of 5), strengths of Statement of Purpose and Letter of Recommendation (out of 5), undergraduate GPA (out of 10), research experience (either 0 or 1), that are considered important during the application for Master Programs. The predicted parameter is the chance of getting an admit (ranging from 0 to 1). You can obtain the data from:
https://www.kaggle.com/mohansacharya/graduate-admissions or from file ‘admission_predict.csv’.

## Assignment 2

### Part A: Object Recognition

The project uses a sample of the CIFAR-10 dataset: https://www.cs.toronto.edu/~kriz/cifar.html
The dataset contains RGB color images of size 32x32 and their corresponding labels from 0 to
9. You will be using the batch_1 of the dataset, which contains 10,000 training samples.
Testing is done on 2,000 test samples. The training data and testing data are provided in files
‘data_batch_1’ and ‘test_batch_trim’, respectively.

### Part B: Text classification

The dataset used in this project contains the first paragraphs collected from Wikipage entries
and the corresponding labels about their category. You will implement CNN and RNN layers
at the word and character levels for the classification of texts in the paragraphs. The output
layer of the networks is a softmax layer.
The training and test datasets will be read from ‘train_medium.csv’ and ‘test_medium.csv’
files. The training dataset contains 5600 entries and test dataset contains 700 entries. The
label of an entry is one of the 15 categories such as people, company, schools, etc.
The input data is in text, which should be converted to character/word IDs to feed to the
networks.

## Group Assignment

### Introduction

Automated car model analysis, especially fine-grained car categorization and verification, can be used for multitudinous purposes in intelligent transportation systems, including vehicle regulation, description, and indexing. For instance, fine-grained car categorization can be exploited to inexpensively automate and expedite paying tolls from the lanes, based on different rates for different types of vehicles.
For this project, we will be working on the Comprehensive Cars (CompCars) Dataset from http://mmlab.ie.cuhk.edu.hk/datasets/comp_cars/index.html for our car image categorization task. The Comprehensive Cars (CompCars) dataset contains data from two scenarios, including images from web-nature and surveillance-nature. The web-nature data contains 163 car makes with 1,716 car models. There is a total of 136,726 images capturing the entire cars and 27,618 images capturing the car parts. The full car images are labelled with bounding boxes and viewpoints. Each car model is labelled with five attributes, including maximum speed, displacement, number of doors, number of seats, and type of car. The surveillance-nature data contains 50,000 car images captured in the front view.
The goal of this project is to design a neural network to classify a given image into one of the 163 car makes. After which consider a multi-task learning framework that classifies not only car makes, but also car models and the corresponding attributes. Some of the other sub-tasks include varying the network depth, tuning the network parameters to improve validation accuracy and validation loss. We will then observe the effects of utilizing a more advanced loss function on the neural network, to see if it improves the overall classification accuracy of the neural network.

