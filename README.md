# CatDog Classification Using CNN

## 1 Environment:

In this experiment, Google Colab is used to utilize GPU acceleration and achieve better training results in a shorter time. 

The source code is in notebook format and can be directly opened on the Google Colab platform by running each code block sequentially.

## 2 Program Workflow

**(1) Data Processing**

First, training and testing sets are compressed and uploaded to Google Drive (compression speeds up the upload process), and are then extracted.

Next, separate a portion of the training set as the validation set, with the training set to validation set ratio being 4:1. 

Then, define some data augmentation operations, such as cropping and rotation. 

Finally, extract the labels and put all the data into a dataloader.

**(2) Model Building**

The model consists of three convolutional layers and two fully connected layers.

**(3) Model Training**

The loss function is cross-entropy, and the Adam optimizer is used.

**(4) Model Testing**

Finally, the submission.csv is generated for testing.
