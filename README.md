# Dogs vs Cats - Kaggle competition
https://www.kaggle.com/competitions/dogs-vs-cats/overview

This repository contains the notebook I used to attend the related Kaggle competition. The objective is to classify the content of a given image as a dog or a cat.

## Structure
The notebook starts with a short description of the problem.

It then proceeds to create directories suitable for using the ImageDataGenerator from tensorflow (this easily allows us to both stream data to the model and to augment it using various transformations).

The model I created is a Convolutional Neural Network with 4 convolutional layers (with increasing number of kernals), each with MaxPooling, on top of which I stacked a dense layer with 512 units. All of the activation functions are 'ReLU'.

## Results
The best test accuracy I obtained was 87% (80/213 participants ~ Top 37%)

**A detailed article that contains the insights and the explanations of the strategy used can be found on my Medium page: [Link Medium Page - To be updated]**
