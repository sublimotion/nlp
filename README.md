# Notebooks and recipes for creating custom entity recognizer for Amazon comprehend.

First notebook walks through the creation of a training dataset using customer support tweets.

Notebook: "AWS Comprehend - Custom Entities"

Second example uses blazingText to train a word2vec model using the customer support tweets.
This allows for creation of keywords that share contextual and semantic proximity.

Notebook: "blazingtext_word2vec_telco_tweets"


In the following notebook, we are using semantic similar words to "frustrated" to let us derive a list of keywords that will then be used in our custom entity recognizer around negativity.

This allows us not only to let us create normal NER (Named entity Recognition) but also sentiment and intent recognizer. 

Notebook: "AWS Comprehend - Custom Entities - Negative"

