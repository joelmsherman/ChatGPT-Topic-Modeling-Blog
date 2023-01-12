# Topic Modeling ChatGPT Tweets with a Latent Dirichlet Allocation NLP Model

## Project Overview
ChatGPT has been taking the world by storm, and if you haven't heard of it yet, you will soon.  A type of Generative Pre-trained Transformer (GPT), ChatGPT is a language model trained to generate human-like text by predicting the next word in a sequence of words.

ChatGPT has been prominent in the Twitersphere, with thousands of tweets and counting on a variety of different topics.  But what do Twitter users say about this impressive new OpenAI model? This project aims to train a Latent Dirichlet Allocation model on Tweets about #ChatGPT to answer this question, and deploy the model in Microsoft Power BI for exploration and interaction.  

## Latent Dirichlet Allocation
Latent Dirichlet Allocation (LDA) is a type of statistical model that is used to uncover the hidden topics that are present in a collection of documents, in this case, Tweets about #ChatGPT. It does this by identifying the words that are most strongly associated with each topic, and using those words to represent the topic.

LDA assumes that each document in the collection is a mixture of a small number of latent topics, and that each word in the document is generated from one of these topics. The goal of LDA is to uncover the set of topics that are present in the documents and to estimate the proportion of each topic present in each document.

To do this, LDA uses a probabilistic model to estimate the likelihood that each word in each document is generated from each of the latent topics. It then uses this information to infer the most likely set of topics present in the documents and to estimate the proportion of each topic present in each document.

## Dataset Acknowledgement
The initial dataset is prepared by Konrad Banachewicz, updated daily, and available [here](https://www.kaggle.com/datasets/konradb/chatgpt-the-tweets) under the CC0: Public Domain license.

## Project Methodology

### Dataset Cleanup, Profiling & EDA
See [this]() notebook.  The dataset contains 60,504 unique tweets (simple retweets have been removed) referencing the hashtag #ChatGPT from 35,748 different users over the period December 5, 2022 through January 2, 2023.    

### Tweet Pre-processing, Modeling Training, Assignment and Evaluation
Talk about
* pycaret
* evaluating lda models are difficult and often need iterating
  
#### Iteration 1
See [this]() notebook.
#### Iteration 2
See [this]() notebook.

### Deploying Assigned Model to a Power BI application
See application [here]()
