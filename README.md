# GAIN (Gamers for Artifical Intelligence and NLP)

[![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue)](https://huggingface.co/spaces/joonkim/bert-political-sentiment-analysis)

## Team members
Samvirit Srinath, Benjamin Johnson, Peter Gao, Calvin Nguyen, Skyler Goh, Joon Kim

## Project Summary

Our project will involve currently involves one model:
1. The first model will allow us to classify the political bias present in a sentence. This model will be trained on a data set containing sentences labeled liberal or conservative, and ultimately output a number on a scale of -1 to 1. We are using a transformer for this  model
2. The second model will perform a Text Style Transfer to convert a politically charged sentence into one that is much more neutral. This model will use the classification model to judge how well each Transfer performed using the classification model, essentially using it as a loss function. We plan on using a Recurrent Neural Network for the second model. (This will be for a future project)

## Dataset

We plan to use this dataset of posts from conservative and liberal subreddited labeled by the source (liberal/conservative). https://www.kaggle.com/datasets/neelgajare/liberals-vs-conservatives-on-reddit-13000-posts?resource=download
