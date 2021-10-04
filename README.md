# NLPlay with Transformers - Sentiment Analysis
## Mentored by Tezan Sahu
Natural Language Processing (NLP) is a field of AI that gives the machines the ability to read, understand and derive meaning from human languages. The field is quickly developing with many breakthroughs happening in the past few years. The current state-ofthe-art are RNNs like LSTMS, GRUs and Transformer models. 

<!-- The first phase of the project was to use Natural Language Processing for Sentiment Analysis. This required the knowledge of basic Machine Learning, which was covered in the first week. First we used a simple Feed Forward Neural Network using Bag of Words Vectorizaion to achieve this. Though this is not the most efficient method for sequential data processing, we we layed out here the basis for the preprocessing of our dataset and our evaluation metrics which we will be used to compare the performance of all the models implemented.  -->
This is a learning project on NLP.  The machine learning algorithms and concepts used for Natural Language Processing are studied through two different examples: **_Sentiment Analysis_** and **_Text Generation_**.

The project is divided into 3 phases:
<hr>

##  Phase-1: Preliminaries
- Introduction to machine learning, basic machine learning tools and libraries.
- Introduction to `pytorch`.
- Introduction to NLP.
- Introduction to `NLTK`, a basic library for processing text.
- Creating a Feed Forward Neural Network for Sentiment Analysis.
- Creating `RNN`, `LSTM` and `GRU` models for Sentiment Analysis.
<hr>

## Phase-2: Transformer for Sentiment Analysis
- Introduction to concept of Attention and Transformer model architecture.
- Studied the evolution of the state-of-the-art through models `BERT`, `RoBERTa`, `XLNet` & `DistilBERT`.
- Introduction to `HuggingFace` Library
- Implemented BERT base and BERT large for sentiment analysis.
<hr>

## Phase-3: Transformer for Text Generation
- Introduction to Transfer Learning for language modelling.
- Introduction to `GPT-2` and `T5` models for sequence to sequence language processing. 
- Imlemeted GPT-2 and T-5 for text generation on a custom made dataset.
- Used GPT-2 and T5 for text generation and compared their `BLEU` scores for the models on this dataset.
<hr>


<!-- ### Neural network for classifying positive and negative reviews trained on an IMDB Dataset consisting of 50,0000 reviews
- Removed noise(stop words, html tags) from raw data and preprocessed using nltk
- Divided data file into 70% training data and 30% data for testing 
- Used bag of words vectorization
- Implemented a feed forward neural network consisting of 2 hidden layers of 500 neurons each.
- Used ReLU as activation function, cross entropy for loss function and Stochastic Gradient Descent with various batch sizes and learning rates
- Achieved a maximum accuracy of 87.68 % -->
