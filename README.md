# NLPlay with Transformers - Sentiment Analysis
The first phase of the project was to use Natural Language Processing for Sentiment Analysis. This required the knowledge of basic Machine Learning, which was covered in the first week. First we used a simple Feed Forward Neural Network using Bag of Words Vectorizaion to achieve this. Though this is not the most efficient method for sequential data processing, we we layed out here the basis for the preprocessing of our dataset and our evaluation metrics which we will be used to compare the performance of all the models implemented. 
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
