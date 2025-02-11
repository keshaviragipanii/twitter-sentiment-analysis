# Twitter-Sentiment-Analysis




This a project of twitter sentiment analysis using machine learning(Support Vector Machines,Naive Bayes), deep learning(LSTM), Transformer(BERT).

Goal:
-----

Our goal is to check the sentiment of a tweet over a topic. It can massively be used to check the sentiment of a new product. There are 3 results over the sentiment analysis. The sentiment can be positive, negative, neutral. Based on that result we can analyse the transparency of the new product.


DATASET:
----
The dataset is based on the tweet of Indian Prime Minister Narendra Modi. By using this dataset we will identify the sentiment of common people. Here the number of the tweet is 1,62,981.

"Twitter US Airline Sentiment" Analyze how travelers in February 2015 expressed their feelings on Twitter. Here the number of the tweet is 14,000.

Approach:
----
**_Here there are 3 type of approach._**

├──  **Machine Learning** |-- **SVM , Naive Bayes**

├── **Deep Learning** |-- **LSTM**

├── **Transformer** |-- **BERT**


Results
-----

|              Algorithm             |                  Accuracy                  |              Dataset Size         |
| -----------------------------------| ------------------------------------------ |-----------------------------------|
|                 SVM                |                   85.47                    |               1,62,981            |
|             Naive Bayes            |                   74.25                    |               1,62,981            |
|            LSTM (20 epochs)        |                   83.71                    |                14,000             |
|           BERT (3 epochs)          |                   97.61                    |               1,62,981            |


Conclusion:
----

Bert's result is very dependable. Other side SVM Naive Bayes and LSTM is quite good and fast to training.

Next Steps:
----

Exploring with other transformers model like RoBertA etc...
