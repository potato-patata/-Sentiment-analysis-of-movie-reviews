# Sentiment analysis of movie reviews
The core of this project is based around a simple task - performing sentiment analysis with the IMDB dataset
1. The first sub-section performed was to compare performance on the classification task across Recurrent Network Variants. Specifically, compared single/multi layer LSTM vs Basic RNN models, single LSTM layer network vs multiple LSTM layer network.
2. Compared classification between Embeddings learned on the fly to any pre-trained word embedding available from the TensorFlow Hub or google's Word2Vec.
3. Investigating the use of CNNs with multiple and heterogeneous kernel sizes both as an alternative to LSTM solution, and as an additional layer before a LSTM solution.
4. Evaluating the results from each of the models to determine which of the models gives the best results and saving the "h5 file"
5. Using the saved model to perform transfer learning on manually web scrapped data to compare performance.
Best model: Multi – Layer LSTM network with distributed embedding (Word2Vec) input layer
Best model performance: 86.83% accuracy
## Dataset
IMDB dataset having 50K movie reviews was used for natural language processing or Text analytics. This is a dataset for binary sentiment classification containing substantially more data than previous benchmark datasets. They provide a set of 25,000 highly polar movie reviews for training and 25,000 for testing.

https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
