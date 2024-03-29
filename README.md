# Emotion Detection Using OpenCV and Keras


## Objective
Trained Convolution Neural Network Model from scratch using Keras for emotion detection using the live camera feed of our system . 

## Data Description

The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The task is to categorize each face based on the emotion shown in the facial expression in to one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

train.csv contains two columns, "emotion" and "pixels". The "emotion" column contains a numeric code ranging from 0 to 6, inclusive, for the emotion that is present in the image. The "pixels" column contains a string surrounded in quotes for each image. The contents of this string a space-separated pixel values in row major order. test.csv contains only the "pixels" column and your task is to predict the emotion column.

The training set consists of 28,709 examples. The public test set used for the leaderboard consists of 3,589 examples. The final test set, which was used to determine the winner of the competition, consists of another 3,589 examples.

This dataset was prepared by Pierre-Luc Carrier and Aaron Courville, as part of an ongoing research project. They have graciously provided the workshop organizers with a preliminary version of their dataset to use for this contest.

### i used kaggle kernel GPU 

The dataset can be downloaded from [this link](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)

## The output : 

![](images/1.JPG)

![](images/2.JPG)

![](images/3.JPG)

![](images/4.JPG)

![](images/5.JPG)

