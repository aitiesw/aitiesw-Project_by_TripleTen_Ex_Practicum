
# Movie Review Sentiment Analysis

The Film Junky Union, a new edgy community for classic movie enthusiasts, is developing a system for filtering and categorizing movie reviews. The goal is to train a model to automatically detect negative reviews. You'll be using a dataset of IMBD movie reviews with polarity labelling to build a model for classifying positive and negative reviews. It will need to reach an F1 score of at least 0.85.


## Data:

Selected fields:

- `review`: the review text
- `pos`: the target, '0' for negative and '1' for positive
- `ds_part`: 'train'/'test' for the train/test part of dataset, correspondingly

## Goal:

- Learn to calculate TF-IDF values for texts
- Figure out how to create embeddings with a BERT model
- Build a classification model for texts

