# Edit dist. and Cosine dist. Report

In this project, I used editing distance (levenshtein) and semantic distance (cosine similarity) to automatically search for classification errors and redundant data in a knowledge corpus. Misclassification and designing similar intents are erros that often occur in the training process for chatbots that use NLU models (e.g. Watson Assistant and Dialog Flow), latter leading into model degradation and catastrophic failures.


# Used datasets

New of the Brazilian Newspaper
https://www.kaggle.com/marlesson/news-of-the-site-folhauol

Tweets about food, recipes and restaurants
https://developer.twitter.com/en/docs/tutorials/stream-tweets-in-real-time


# Chatbot training corpora

Bot restaurante - Watson Assistant
./data/corpus*.json