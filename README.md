# Fruit and Veg Classifier

## Overview
This project creates an image classifier for 36 different categories of fruits and vegetables by implementing a Convolutional Neural Network (CNN).

## Data Pre-Processing
Images are resized to 200x200 pixels for uniformity, dataset is shuffled, and pixel values are normalised.

## Training
A CNN model is trained which is made up of 3 convolutional layers of 32, 64, 128 filters respectively, each followed by a pooling layer, then a flatten layer, dropout layer, and 2 fully connected layers to finish. The padding is set to 'same' so the output image has the same dimensions as the input image to ensure no information is lost at the edges. The batch size, epoch size, and dropout rate are 32, 20, and 0.25, respectively.

## Evaluation
On unseen test data, the model has an accuracy of 96% and an F1 score of 0.97.

## Conclusion
The classifier demonstrates very high accuracy and robustness in classifying fruits and vegetables and therefore offers effective contribution towards the field of automated agriculture.
