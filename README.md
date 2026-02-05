# Introduction
In this project, our focus will be on analyzing hotel reviews and corresponding ratings derived from customer experiences. We will delve into feature engineering and develop a deep-learning model to forecast ratings based on the reviews. Additionally, we will leverage NLP tools for extracting features and preparing the data for optimal utilization in deep learning models.

# A brief on TripAdvisor
TripAdvisor, Inc. is a U.S.-based online travel company that manages a website and mobile app featuring user-generated content and a comparison-shopping platform. The company facilitates online reservations and bookings for hotels, transportation, lodging, travel experiences, and restaurants. Its headquarters are located in Needham, Massachusetts. https://en.wikipedia.org/wiki/Tripadvisor

# Pip List
1. pip install nltk
2. pip install vaderSentiment
3. pip install wordcloud
4. pip install pandas_profiling[notebook,html]
5. pip install ydata_profiling
6. pip install pillow
7. pip install skimage
8. pip install rake_nltk
9. pip install counter

# Datasets
1. TripAdvisor Hotel Review Dataset (zenodo.org)
2. 515K Hotel Reviews Data in Europe | Kaggle

# Recurrent Neural Network
Recurrent Neural Network (RNN) is a type of Neural Network where the output from the previous step is fed as input to the current step. This is a short-term memory to process Sequential data(Speech data, Music, Sequence of words in a text). Here is a sample architecture diagram. U, V, and W are the weights of the hidden layer, the output layer, and the hidden state, respectively. xt and ot are the input vector and output result at time t, respectively

![image](https://github.com/sreya-kambhatla/Masters-Project/assets/145293962/824c0e17-6b21-4dee-99b2-7cffccb2af54)


# Long Short-Term Memory Model

Long Short-Term Memory (LSTM) is like a special kind of memory in a computer program that's good at remembering things for a long time, especially when dealing with a bunch of information coming in a sequence, like words in a sentence.
So, if a computer program needs to understand the meaning of a sentence or remember information for a long time, LSTM is like the brainy part that helps it do that job effectively.

![image](https://github.com/sreya-kambhatla/Masters-Project/assets/145293962/8131230e-6c6d-4afd-a781-c27a7223e854)

# BiLSTM Model

The Bidirectional Long Short-Term Memory (BiLSTM) model is like a clever reader that not only understands the context of a sentence by reading it forward but also pays attention to what comes later by reading it backward.

So, a BiLSTM is like having two brains working together to capture the full meaning of a sequence of words, which can be especially useful in tasks like understanding the sentiment of a sentence or predicting the next word in a sequence.

![image](https://github.com/sreya-kambhatla/Masters-Project/assets/145293962/ecf2fd88-8eca-448f-8522-629c4c2d6a78)

![image](https://github.com/sreya-kambhatla/Masters-Project/assets/145293962/cbad72fc-af52-4de7-9de6-9ee4dac2ad21)






