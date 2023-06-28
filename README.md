# URL Phishing Detection Model
This repository contains an implementation of a phishing detection model using a combination of 1D CNN and LSTM. The model is trained to classify URLs as either legitimate or phishing based on various features of the dataset.

## Dataset
The dataset was collected from Kaggle and contains 89 features, with 11,430 instances.

## Model Architecture
The model architecture consists of a combination of a 1D Convolutional Neural Network (CNN) and a Long Short-Term Memory (LSTM) layer. The CNN layer acts like a filter, searching for important patterns in the input data. It focuses on small sections at a time and captures specific details in the data. The LSTM layer is like a memory that remembers important recurring patterns in the sequence of data.

## Accuracy
The training accuracy for the model is around 97%, and the test accuracy is 95.65%.

##
Please note that this README provides an overview of the implementation and model architecture without diving into technical details. For further information and code execution, please refer to the provided Jupyter Notebook (".ipynb") file.