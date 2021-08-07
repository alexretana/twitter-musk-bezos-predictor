# Tweet Poster Classifier

This is a basic Natrual Langaue Processing (NLP) and Supervised Machine Learning (ML) example using real tweets from Elon Musk and Jeff Bezos to demonstrate the capabilities of common classification models and their application to unstructured text data.


There are two main phases of this demo, Data Collection and Predictor

## Data Collection

The first step in this project is to collect data in the form of tweets by Jeff Bezos and Elon Musk. To accomplish this, the [Tweepy](https://docs.tweepy.org/en/stable/index.html) package, managed by [Harmon758](https://github.com/Harmon758), is going to be utilized.

## Predictor

The second step in this project is to develop a predictor model to determine if a random tweet from one of the two twitter users can classified as belonging to one of them. This requires cleaning the text data, in which used the [Natural Lanague Toolkit (or NLTK)](https://www.nltk.org/), and then vectorizing, splitting the data and then training and evalutating the results, which is all done using the highly popular [Scikit Learn library](https://scikit-learn.org/stable/)

### Note:

To run the cells in your environment, the requirements will be to have conda installed and to have a developer's account on Twitter to receive API keys.

If conda is installed, to create an environment with the necessary packages run in the root folder:

`<conda env create --file environment.yml>`

The API keys should be placed in a file named t_creds.py and the variables named accordingly:
 - CONSUMER_KEY
 - CONSUMER_SECRET
 - ACCESS_TOKEN_KEY
 - ACCESS_TOKEN_SECRET