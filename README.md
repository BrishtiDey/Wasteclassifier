# WASTE CLASSIFIER
This repository contains code to classify waste.

We used a Deep Learning Keras model with 6 Convolutional Layers and 2 Dense Layers to achieve a 91% test accuracy.
use_model function can be used to predict on new data.

## DATASET

I scrapped the web for images on recyclable, general, and composite items

We trained the model with 22564 images, of which 12565 were of organic items and 9999 were of recyclable items.
For the test set, we had 1401 images for organic items and 1112 images of recyclable items making a total of 2513 items.

The dataset is available in Kaggle. The link is available below <br>
https://www.kaggle.com/techsash/waste-classification-data

Many hours of work have gone into collecting and cleaning the data. While the data is free, we expect attribution when the dataset is used. 

Also please contribute to the data if possible.

## DEPENDENCIES

1. Keras
2. Tensorflow
3. open-cv
5. cv zone


![types of wastes](https://github.com/BrishtiDey/Wasteclassifier/assets/97660357/ebd210e4-38f0-4f3a-b0f2-e67363baf2da)
