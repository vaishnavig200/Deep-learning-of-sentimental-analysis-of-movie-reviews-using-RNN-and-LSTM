# Deep-Learning-of-Sentimental-Analysis-of-Movie-Reviews-using-RNN-and-LSTM
Analyzing the sentiments of customers based on movie reviews, using Natural language processing(NLP). 
We have taken a dataset that consists of 50,000 rows, where each row has two columns(text: which is the review, and label: which is the sentiment i.e., either 0 or 1).
Firstly, performed preprocessing steps on the dataset to make it suitable for the machine learning models.
We then split the data into train and test data.
We performed Word2Vec embedding to increase the performance and efficiency of the models we implemented.
We then implemented the LSTM (Long Short-term Memory), RNN (Recurrent Neural Network), and models and computed the accuracies of each.
LSTM is very effective in capturing the long-term dependencies in sequential data accounting for the higher performance over all other models.
RNNs struggle to capture long-term dependencies due to vanishing/exploding gradient problems and a lack of advanced memory mechanisms, making it hard to deal with long-range dependencies, and impacting their ability to analyze the sentiments of the reviews correctly.


