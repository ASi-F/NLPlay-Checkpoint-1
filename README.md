# NLPlay with Transformers
## I - Sentiment Analysis
The objective of the first checkpoint was to Implement Sentiment Analysis using Feedforward Network in PyTorch.
<hr>

##  Week-1 progress
- Covered basics libraries for mashine learning like numpy, pandas, matplotlib and pytorch.
- Covered resources for basics of python, supervised learning and neural networks.
- Covered resources on Natural language processing. Introduced to its thoretical aspects.
- Covered NLTK, a basic library for processing text.
- Intoduced to google Colab.
<hr>

## Week-2 progress
- Dived deeper into natural language processing
- Learnt about word embeddings and its different types
- Created a basic Feed Forward Neural Network for semtiment classification.

### Neural network for classifying positive and negative reviews trained on an IMDB Dataset consisting of 50,0000 reviews
- Removed noise(stop words, html tags) from raw data and preprocessed using nltk
- Divided data file into 70% training data and 30% data for testing 
- Used bag of words vectorization
- Implemented a feed forward neural network consisting of 2 hidden layers of 500 neurons each.
- Used ReLU as activation function, cross entropy for loss function and Stochastic Gradient Descent with various batch sizes and learning rates
- Achieved a maximum accuracy of 87.68 %
