# Word Prediction Models
This repository contains Python scripts for implementing word prediction models using different n-gram approaches. Three main scripts are provided:

## 1. Next Word Prediction - Uni-gram
This implements a word prediction model based on uni-gram (single word) sequences. It creates word pairs from a given text corpus and calculates the occurrence probabilities of each pair. The model can predict the next word based on a given word sequence.

## 2. Next Word Prediction - Bi-gram Tri-gram N-gram
This extends the word prediction model to use n-gram sequences, where n denotes the number of words in a sequence. It generates n-grams from the text corpus and calculates the occurrence probabilities of each n-gram. The model can predict the next word based on a given n-gram sequence.

## 3. Context Word Prediction

This implements a context-based word prediction model. It creates pairs of words along with their context (words before and after) from a given text corpus. The model predicts the next word based on the context words provided.
