# IACAH (India Academia Connect AI Hackathon) 

Date - October 4-13, 2021

Artificial intelligence will be an enormous part of the future workforce. It’s expected to generate 2 million net job gains versus losses by 2025. India Academia Connect AI Hackathon will help the participants from leading research institutions with the opportunity to learn and implement the latest AI technology, preparing them for a future AI-powered economy, with a large research and developer base.

## Problem Statement

The challenge is to identify the presence of a character in images using Convolutional Neural Networks.

## Dataset

The dataset will contain the following:

- Train Dataset: Consists of sample reference sets which can be used by participants to train the Convolution Neural Network. The participants are recommended to use their own training dataset if required.

- Test Dataset: The test dataset will contain the images to be classified and results to be submitted in the form of a JSON file. More details on the JSON format and a sample provided as part of the dataset.

- You can download the dataset from this [Drive Link](https://drive.google.com/drive/folders/1O8TT0s4zMyiI6zR-biVRoiLiAUy-W1H0?usp=sharing). The dataset consists of a README file.

## Solution

- CustomDataGenerator created to load images and labels
- Used VGG16 to fine tune the model for dataset
- created function for tensorflow training loop 
- Create model evalutoion to function to test the model accuracy
