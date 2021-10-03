# NLPlay with Transformers - Sentiment Analysis
## Mentored by Tezan Sahu
Natural Language Processing (NLP) is a field of AI that gives the machines the ability to read, understand and derive meaning from human languages. The field is quickly developing with many breakthroughs happening in the past few years. The current state-ofthe-art are RNNs like LSTMS, GRUs and Transformer models. 

<!-- The first phase of the project was to use Natural Language Processing for Sentiment Analysis. This required the knowledge of basic Machine Learning, which was covered in the first week. First we used a simple Feed Forward Neural Network using Bag of Words Vectorizaion to achieve this. Though this is not the most efficient method for sequential data processing, we we layed out here the basis for the preprocessing of our dataset and our evaluation metrics which we will be used to compare the performance of all the models implemented.  -->
This is a learning project on NLP and is divided into 3 phases:
<hr>

##  Phase-1 - Preliminaries
- Introduction to python libraries <\code>NumPy<\code>, pandas, matplotlib and pytorch.
- Covered resources for basics of python, supervised learning and neural networks.
- Covered resources on Natural language processing. Introduced to its thoretical aspects.
- Covered NLTK, a basic library for processing text.
- Intoduced to google Colab.
- Created a neural network model for digit classification on MNIST dataset.
- Created a Feed Forward Neural Network for sentiment Analysis on he IMDB review dataset consisting of 50,000 reviews. 
- Created RNN, LSTM and GRU models for sentiment Analysis
<hr>

## Phase-2 - Transformer for Sentiment Analysis
- Introduction to concept of Attention and Transformer model architecture.
- Studued the evolution of the state-of-the-art, and various transformer models.
- Introduction to Hugging Face Library
- Implemented BERT base and BERT large for sentiment analyis.

## Phase-3 - Transformer for text generation
- Introduction to Transfer Learning for language modelling
- Learnt about the GPT-2 and T5 models usd for sequence to sequence language processing. 
- Imlemeted GPT-2 and T-5 for text generation on a dataset consisting of various reearch articles, financial articles and Entertainment based Aricles.
- Used GPT-2 and T5 for text generation and calculate the BLEU score for the models ver this dataset.



<!-- ### Neural network for classifying positive and negative reviews trained on an IMDB Dataset consisting of 50,0000 reviews
- Removed noise(stop words, html tags) from raw data and preprocessed using nltk
- Divided data file into 70% training data and 30% data for testing 
- Used bag of words vectorization
- Implemented a feed forward neural network consisting of 2 hidden layers of 500 neurons each.
- Used ReLU as activation function, cross entropy for loss function and Stochastic Gradient Descent with various batch sizes and learning rates
- Achieved a maximum accuracy of 87.68 % -->
