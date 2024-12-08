---
layout: default
---

# Project 1

 ### EYE FOR BLIND
[Github link to EYE FOR BLIND PROJECT](https://github.com/Mahalakshmi-Totad/EyeForBlind).
**Problem statement**: In this capstone project,goal is to create a deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism. This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library. 

**The dataset** is Flickr8K, it is taken from the Kaggle website and it consists of sentence-based image descriptions having a list of 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events of the image.

**The major steps to perform can be briefly summarised in the following four steps:**

- **Data Understanding:**  load the data and understand the representation.
- **Data Preprocessing:** In this step, process both images and captions to the desired format.
- **Train-Test Split:** Combine both images and captions to create the train and test dataset.
- **Model Building:** This is the stage to create image captioning model by building Encoder, Attention and Decoder model.
- **Model Evaluation:** Evaluate the models using greedy search and BLEU score.

** Model : Inception net V3 **
**Libraries Used : tensorflow,  keras, nltk, numpy, pandas, sklearn, matplotlib, seaborn, gTTs**
  
- Successfully created the dataset according as required by Inception net V3 
- Used the pretrained Imagenet weights of Inception net V3
- Trained the model for 15 epochs and was able to reduce the loss to 0.420
- Used Greedy search for evalution
- Achieved >60% BELU score for most of the random images from test set on which model was tested

  
## Project 2

Target Reliability Systems

