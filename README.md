# IACAH (India Academia Connect AI Hackathon) 

Date - October 4-13, 2021

Artificial intelligence will be an enormous part of the future workforce. It’s expected to generate 2 million net job gains versus losses by 2025. India Academia Connect AI Hackathon will help the participants from leading research institutions with the opportunity to learn and implement the latest AI technology, preparing them for a future AI-powered economy, with a large research and developer base.

## Event Format

This Hackathon will be hosted online with all times Indian Standard Time (IST). All communication will be done through Zoom, Slack and email.

## Problem Statement

The challenge is to identify the presence of a character in images using Convolutional Neural Networks.

The dataset will contain the following:

- Train Dataset: Consists of sample reference sets which can be used by participants to train the Convolution Neural Network. The participants are recommended to use their own training dataset if required.

- Test Dataset: The test dataset will contain the images to be classified and results to be submitted in the form of a JSON file. More details on the JSON format and a sample provided as part of the dataset.

Submissions are evaluated on Accuracy Score between the predicted and the actual labels on the test dataset

- You can download the dataset from this [Drive Link](https://drive.google.com/drive/folders/1O8TT0s4zMyiI6zR-biVRoiLiAUy-W1H0?usp=sharing). The dataset consists of a README file.

## Solution

Created custom data pipeline to load data into batches and trained the Model using custom traning loop used VGG16 as feature extractor and used Dropout to avoid overfitting. we used some Data augmentation technique to make model more robust and better. we are using MODELCHECKPOINT and EARLYSTOPPING function to get the best model possible.
