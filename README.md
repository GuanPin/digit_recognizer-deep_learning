# Digit Recognizer by Deep Learning

## Data
The data source is from [kaggle](https://www.kaggle.com/c/digit-recognizer).\ The first column of training set is the label of each image, and the corresbonding columns are the pixel values of each image. The testing set is almost the same as training set, but the testing set is without the label column. Therefore, we need to train a neural network to predict these label and conclude the predicted ability of the model.

## Analysis
Because the data is already transformed (from image to pixel values), we can directly use the data to conduct analysis without data processing. In the beginning, we normalized the pixels to make the values between 0 and 1. Then, we train a normal fully connected neural network (DNN) and a convolutional neural network (CNN).
