# GAIN (Gamers for Artifical Intelligence and NLP)

## Team members
Samvirit Srinath, Benjamin Johnson, Peter Gao, Calvin Nguyen, Skyler Goh, Joon Kim

## Project summary

Our project will involve making two separate models:
1. The first model will allow us to classify the political bias present in a sentence. This model will be trained on a data set containing sentences labeled liberal or conservative, and ultimately output a number on a scale of -1 to 1.
2. The second model will perform a Text Style Transfer to convert a politically charged sentence into one that is much more neutral. This model will use the classification model to judge how well each Transfer performed using the classification model, essentially using it as a loss function. We plan on using a Recurrent Neural Network for the second model.

## Dataset

We plan to use this dataset of sentences from news articles labeled by the source (liberal/conservative) they came from: https://github.com/JerryWei03/NewB
