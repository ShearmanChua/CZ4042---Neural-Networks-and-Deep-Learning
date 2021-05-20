# CZ4042 Neural Networks and Deep Learning Car Make Recognition Group Project

## Introduction

Automated car model analysis, especially fine-grained car categorization and verification, can be used for multitudinous purposes in intelligent transportation systems, including vehicle regulation, description, and indexing. For instance, fine-grained car categorization can be exploited to inexpensively automate and expedite paying tolls from the lanes, based on different rates for different types of vehicles.
For this project, we will be working on the Comprehensive Cars (CompCars) Dataset from http://mmlab.ie.cuhk.edu.hk/datasets/comp_cars/index.html for our car image categorization task. The Comprehensive Cars (CompCars) dataset contains data from two scenarios, including images from web-nature and surveillance-nature. The web-nature data contains 163 car makes with 1,716 car models. There is a total of 136,726 images capturing the entire cars and 27,618 images capturing the car parts. The full car images are labelled with bounding boxes and viewpoints. Each car model is labelled with five attributes, including maximum speed, displacement, number of doors, number of seats, and type of car. The surveillance-nature data contains 50,000 car images captured in the front view.
The goal of this project is to design a neural network to classify a given image into one of the 163 car makes. After which consider a multi-task learning framework that classifies not only car makes, but also car models and the corresponding attributes. Some of the other sub-tasks include varying the network depth, tuning the network parameters to improve validation accuracy and validation loss. We will then observe the effects of utilizing a more advanced loss function on the neural network, to see if it improves the overall classification accuracy of the neural network.

## Project Scope
For our team, we decided to narrow the scope of the project down to designing a multi-task learning framework that classifies a given image into one of the 163 car makes, as well as one of the car models.
Also, we will be varying the network depth, tuning the network parameters to try to improve the validation accuracy and validation loss of the neural network. We will then observe the effects of utilizing a more advanced loss function on the neural network, to see if it improves the overall classification accuracy as well as model loss of the neural network.
After discussing amongst our team, the finalized scope of our project is defined by:
1. Design a neural network that builds upon a previously published architecture for the purpose of car image categorization
2. Modify the hyperparameters of the network architecture by using a model selection search method (e.g. Grid Search,Random Search, Hyperband)
3. Design a multi-task learning framework that classifies not only car makes, but also car models
4. Try a more advanced loss function such as triplet loss for the neural network and compare the results with that of the neural network with a baseline loss function

## Resources Used for Project
For this Project, our group will be building and training the neural network on the Google Colaboratory platform. The neural network will be coded in Python programming language. The reason behind this is that Python has many libraries that can be used to easily build neural networks. Also, by using the Google Colaboratory platform, we can utilize Tensor Processing Units (TPUs) developed by Google to allow our neural network to be trained faster.
