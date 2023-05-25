# AI_CHATBOT
This repository contains code for a chatbot with intent recognition. The chatbot is built using the Keras library and trained on a dataset of intents defined in a JSON file. It utilizes natural language processing techniques and a neural network model to understand user input and provide appropriate responses based on the predicted intent.

Features:

The chatbot is capable of understanding and responding to a variety of intents defined in the intents.json file.
It uses a bag-of-words approach to convert user input into a numerical representation.
The neural network model, implemented using the Keras library, is trained on the dataset of intents to classify user input into different intent categories.
The code includes functions to clean up user sentences, create bag-of-words representations, predict intents, and retrieve random responses associated with predicted intents.
The model and necessary data files (words.pkl, classes.pkl) are loaded during runtime to enable intent recognition.
