Mobile Price Classification with Neural Network
This project implements a Neural Network using TensorFlow and Keras to classify mobile prices into different categories based on various features.

Project Overview
The dataset used in this project contains mobile specifications as features and the corresponding price range as labels. The goal is to predict the price range of a mobile based on its specifications using a fully connected neural network.

Installation
To run this project, you need to have Python installed with the following packages:

TensorFlow
Keras
pandas
scikit-learn
NumPy
You can install these dependencies using pip:

pip install tensorflow keras pandas scikit-learn numpy
Usage
Load the dataset: The dataset is loaded from a CSV file containing mobile specifications and their price range.
Preprocess the data: Features are standardized using StandardScaler, and data is split into training and testing sets.
Build and train the model: A simple neural network model is defined, compiled, and trained on the training set.
Evaluate the model: The model's accuracy is evaluated on the test set using accuracy score.
To run the script:

Results
After training for 100 epochs, the model achieves an accuracy score of approximately 91% on the test set. Model performance can be improved by tuning hyperparameters or changing the model architecture.

