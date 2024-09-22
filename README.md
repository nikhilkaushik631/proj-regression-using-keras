# Regression Models with Keras

## Introduction
This project demonstrates how to use the Keras library to build a regression model. Despite the popularity of more powerful libraries like PyTorch and TensorFlow, their steep learning curve makes Keras a more accessible choice for beginners in deep learning. Keras is a high-level API that simplifies the process of building complex deep learning networks. With Keras, even sophisticated models can be implemented with just a few lines of code.

In this project, we will build a neural network to predict the compressive strength of different concrete samples based on the volumes of ingredients used.

## Objective
1. Learn how to use the Keras library to build a regression model.
2. Download and clean the dataset.
3. Build a neural network for regression.
4. Train and test the neural network.

## Dataset
The dataset contains information about the compressive strength of different concrete samples, based on the quantities of the following ingredients:
- Cement
- Blast Furnace Slag
- Fly Ash
- Water
- Superplasticizer
- Coarse Aggregate
- Fine Aggregate

The dataset can be found at:  
[Concrete Data CSV](https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/DL0101EN/labs/data/concrete_data.csv)

## Libraries Used
This project utilizes the Keras library for building the neural network, which runs on top of TensorFlow. The backend used for Keras will be explicitly shown upon import, ensuring TensorFlow is installed and working correctly.

## Instructions

### Import Keras
First, ensure that TensorFlow is installed since Keras operates on top of a low-level library like TensorFlow. In this project, TensorFlow is the backend used for Keras.

### Neural Network
- **Input Features**: The volumes of the seven ingredients.
- **Target**: The compressive strength of the concrete.
- **Architecture**: The neural network is built using Keras, with fully connected layers for regression.


