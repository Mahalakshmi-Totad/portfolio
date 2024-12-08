# Generative AI , AI & ML Portfolio
---
## EYE FOR BLIND
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/Mahalakshmi-Totad/EyeForBlind)

In this capstone project,goal is to create a deep learning model which can explain the contents of an image in the form of speech through caption generation with an attention mechanism. This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library. 

**The dataset:** Flickr8K
**Model:** Inception net V3
**Libraries Used :** tensorflow,  keras, nltk, numpy, pandas, sklearn, matplotlib, seaborn, gTTs
**Model Building:** This is the stage to create image captioning model by building **Encoder, Attention and Decoder model.**
**Model Evaluation:** Used **Greedy search** for evalution. **Achieved >60% BELU score** for most of the random images from test set.

## Fashion Search AI - a Generative Search System
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/Mahalakshmi-Totad/SemanticSpotterFashionSearchAI)
Fashion search AI is a Generative Search System capable of searching a plethora of product descriptions to find and recommend appropriate choices against a user query. Combine the power of **LangChain framework** to use large language models with data from Myntra dataset to generate relevant response for user serach.

**Model used: **
ChatOpenAI : gpt-3.5-turbo-0125
Langchain Chroma OpenAIEmbeddings
Langchain FAISS OpenAIEmbeddings

## HelpMate
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/Mahalakshmi-Totad/HelpMate)

HelpMate AI parses the filtered documents and provides answers to user's queries from a given policy document containing information about Life insurance

**Model used:** ChatOpenAI gpt-3.5-turbo-0125

### System Design:
1. The Embedding Layer : 
    - The PDF document needs to be effectively processed, cleaned, and chunked for the embeddings.
    - Using [pdfplumber](https://https://pypi.org/project/pdfplumber/) to read and process the PDF files.
      
2. The Search Layer
    - Design at least 3 queries against which to test the system.
    - Search  ChromaDB vector database against each of these queries. 
    - Semantic Search with Cache
    - Re-Ranking with a Cross Encoder

3. The Generation Layer
    - Retrieval Augmented Generation: Pass top search results to GPT 3.5 along with the user query and a well-engineered prompt to Generateanswer 
      
## Book Recommendation Chatbot 
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/Mahalakshmi-Totad/book_recommendation_chatbot_openai)
Book Recommendation Chatbot can be used to discover exciting books tailored to user preferences and interests. From different geners like thrilling mysteries, heartwarming romances, or thought-provoking non-fiction that combines the power of **large language models and rule-based functions to ensure relevant recommendations**.

**Model used: ** ChatGPT model gpt-3.5-turbo

<center><img src="img/SystemDesign.png"/></center>

