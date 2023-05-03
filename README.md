<h1> Testing beers</h2>
<h2>Explore the sentiment in Machine Learning</h2>

Sentiment analysis, also known as opinion mining, is a subfield of natural language processing (NLP) that involves analyzing the sentiment or emotion expressed in a piece of text. Sentiment analysis is widely used in applications such as social media monitoring, customer feedback analysis, and market research.

Sentiment analysis can be performed at different levels, ranging from individual words and phrases to entire documents or conversations. The simplest approach to sentiment analysis is to use a lexicon-based method, where a set of words or phrases with known sentiment polarities (positive or negative) is used to determine the overall sentiment of a piece of text. However, lexicon-based methods can be limited in their accuracy and applicability, as they often fail to capture the context and nuances of language.

A more sophisticated approach to sentiment analysis involves machine learning techniques, such as supervised or unsupervised learning, which can learn from labeled data and generalize to new data. In supervised learning, a model is trained on a labeled dataset of text and corresponding sentiment polarities, and can then be used to predict the sentiment of new text. In unsupervised learning, the model learns patterns and clusters in the data without the use of labeled data.

In this notebook, we will focus on building a sentiment analysis model using Pytorch and the supervised learning approach. Specifically, we will build a model to predict the sentiment polarity of beer reviews, using a dataset of beer reviews with corresponding positive or negative labels. We will use an LSTM-based neural network to learn from the text data, and evaluate the performance of the model using various metrics.
