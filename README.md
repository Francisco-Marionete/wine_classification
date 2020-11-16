# wine_classification
In this challenge we have to predict which grape type is a wine made of based on a review that has details about the wine, the reviewer and also a small text description column. This is a simple multi-class classification problem, however it contains 2 specific details:

- Imbalanced dataset: This can lead the model to predict with accuracy the most frequent classes but fail to predict the most rare ones. I'll use imb-learn to apply under-sampling and over-sampling techniques to make the dataset balanced without losing relevant information.
- Small text data: Since ML models only 'see' numbers, in order to leverage this information to increase the ML model performance we need to use NLP techniques such as tokenization+lemmatization and TF-IDF.
