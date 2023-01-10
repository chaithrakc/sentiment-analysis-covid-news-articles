# Sentiment Analysis of COVID News Stories

This project aims to analyze the sentiment polarity of news articles related to COVID-19 from various countries, specifically the UK, India, Japan, and South Korea. The dataset used in this project was collected from IEEE data port and comprises of 10,000 news articles.

The initial step in this project was data cleaning, pre-processing, and exploratory analysis. These processes were carried out to ensure the quality and consistency of the data.

After pre-processing the dataset, the textual data was transformed into numeric vectors using word vectorization techniques. These techniques included the Bag of Words (BOW) model, BERT word embedding, and XLNet embedding, which were used to convert the text data into numerical representations that can be fed into machine learning algorithms.

The sentiment polarity of each news article was predicted using two different models. The Naïve Bayes classifier and BiLSTM (Bidirectional Long Short-Term Memory) neural network were used to classify the news articles into one of three categories: Negative, Positive, and Neutral. The BiLSTM model achieved an accuracy of 64%, whereas the Naive Bayes algorithm with 10-fold cross-validation had an accuracy of 78%. The results showed that the Naive Bayes algorithm performed better on this dataset than the BiLSTM neural network.
