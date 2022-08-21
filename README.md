# disaster_tweets

The notebook is a part of an actual competition hosted by Kaggle to get started with NLP (link: https://www.kaggle.com/competitions/nlp-getting-started).
Dataset used here: Kaggle "Disaster Tweets". 
Task to complete: Predict which Tweets are about real disasters and which ones are not.

This notebook includes various techniques that were applied to tackle this problem: 
1) Data-wise: 
- text cleaning and tokenization: spacy library;
- vocabulary reduction: custom functions;
- text vectorization: GloVe;
2) Model-wise:
- different base model: Linear Classifiers (+Stacking Ensemble), Multichannel Convolutional Neural Network;
- model regularization & training: 1Cycle Scheduling;

The resuts obtained from different models were compared and the best model was chosen to produce the submission file. 
