# Real-or-Not-NLP-with-Disaster-Tweets
Classifying whether a disaster tweet is real or not using LSTM and GloVe word embeddings.
The model gave an accuracy of 80% on both train and validation data set with learning rate 5e-5, predicting whether a given tweet is about a real disaster or not. If so, predicted as 1. If not, predicted as 0. The datasets have been taken from <a href=https://www.kaggle.com/c/nlp-getting-started/data>Kaggle Data sets</a>


The kaggle notebook can be viewed <a href='https://www.kaggle.com/naureenmohammad/nlp-on-disaster-tweet-final'>here </a>


> Each sample in the train and test set has the information about the text of a tweet, A keyword from that tweet (although this may be blank!) and The location the tweet was sent from (may also be blank)

> CSV data set has Columns as:
>
>> id - a unique identifier for each tweet
>> text - the text of the tweet
>> location - the location the tweet was sent from (may be blank)
>> keyword - a particular keyword from the tweet (may be blank)
>> target - in train.csv only, this denotes whether a tweet is about a real disaster (1) or not (0)


### EDA performed on data sets are 

> <a href='https://github.com/naureen20/Real-or-Not-NLP-with-Disaster-Tweets/blob/master/nlp-on-disaster-tweet.ipynb'>1. Data processing </a>

  >> 1.1 Handling Misspelled data
  
  >> 1.2 Handling Contractions
  
  >> 1.3 Replacing Abbreviations
  
  >> 1.4 Visualizing length of tweets
  
  >> 1.5 Visualizing word count in each tweet
  
  >> 1.6 Collecting all words
  
  
> <a href='https://github.com/naureen20/Real-or-Not-NLP-with-Disaster-Tweets/blob/master/nlp-on-disaster-tweet.ipynb'>2. Visualizing and data attributes  </a>

  >> 2.1 Viewing most common stop words used in tweets
  
  >> 2.2 Viewing Punctuations in tweets
  
  >> 2.3 Viewing Common words in tweets
  
  >> 2.4 N-gram analysis
  
  
>  <a href='https://github.com/naureen20/Real-or-Not-NLP-with-Disaster-Tweets/blob/master/nlp-on-disaster-tweet.ipynb'>3. Data cleaning </a>

  >> 3.1 Cleaning URLs and HTML tags
  
  >> 3.2 Cleaning Punctuations and emojis
  
  >> 3.3 Cleaning stop words
  
  3.4 Using Glo-Ve for word embeddings
  
  3.5 Train-Test split
  
  
><a href='https://github.com/naureen20/Real-or-Not-NLP-with-Disaster-Tweets/blob/master/nlp-on-disaster-tweet.ipynb'> 4. Creating Model</a>

  >> 4.1 LSTM Model with Glove Embeddings
  
  >> 4.2 Plotting accuracy and loss curves
  
  <img src="https://github.com/naureen20/Real-or-Not-NLP-with-Disaster-Tweets/blob/master/loss_acc_plot.png">
  
