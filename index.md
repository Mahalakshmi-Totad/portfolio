# Generative AI , AI & ML Portfolio
---
## EYE FOR BLIND
[Github link](https://github.com/Mahalakshmi-Totad/EyeForBlind).

**Problem statement**: In this capstone project,goal is to create a deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism. This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library. 

**The dataset is Flickr8K**
**Model : Inception net V3**
**Libraries Used : tensorflow,  keras, nltk, numpy, pandas, sklearn, matplotlib, seaborn, gTTs**
  
**The major steps to perform can be briefly summarised in the following four steps:**

- **Data Understanding:**  load the data and understand the representation - Successfully created the dataset according as required by Inception net V3 
- **Data Preprocessing:** In this step, process both images and captions to the desired format.
- **Train-Test Split:** Combine both images and captions to create the train and test dataset.
  - Used the pretrained Imagenet weights of Inception net V3 
  - Trained the model for 15 epochs and was able to reduce the loss to 0.420
- **Model Building:** This is the stage to create image captioning model by building Encoder, Attention and Decoder model.
- **Model Evaluation:** Evaluate the models using greedy search and BLEU score.
  -> Used Greedy search for evalution
  -> Achieved >60% BELU score for most of the random images from test set on which model was tested

## Semantic Spotter - Project - Fashion search AI - a Generative Search System
[Github link](https://github.com/Mahalakshmi-Totad/SemanticSpotterFashionSearchAI).
**Project's goals:**  Fashion search AI is a Generative Search System capable of searching a plethora of product descriptions to find and recommend appropriate choices against a user query. Combine the power of LangChain framework to use large language models with data from myntra dataset to generate relevant response for user serachs and demonstrate the knowledge of Langchain framework and it's components.

**Model used: **
ChatOpenAI : gpt-3.5-turbo-0125
Langchain Chroma OpenAIEmbeddings
Langchain FAISS OpenAIEmbeddings



