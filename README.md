# Language-Translation-RealTime-ML
## Language Translation with Machine Learning
Create a real-time machine learning language translator with TensorFlow

Savez-vous comment créer une application de traduction de langue?

Did you understand the above sentence?

Well after googling it, I found its meaning as:

Do you know how to create a language translator app?

We all know about Google Translate which allows us to convert from one language to another and it’s very useful for learning and understanding new languages.

## About Language Translator Project:
In this machine learning project, we will develop a Language Translator App using a many-to-many encoder-decoder sequence model. We will train our model using LSTM which will convert English to French language where English will be input text and French will be the target text. For this, we will be using English-French dataset.

### Project Prerequisites
This project requires you to have a good knowledge of Python, TensorFlow, and Keras.

Modules required for this project are tensorflow, pickle, and sklearn. You can install with the following command:
` pip install tensorflow , pickle , sklearn , numpy `

The versions which are used in this project for python and its corresponding modules are as follows:

- python: 3.8.5
- TensorFlow: 2.3.1 (Note: TensorFlow version should be 2.2 or higher in order to use keras or else install keras directly)
- Sklearn: 0.24.2
- Pickle: 4.0
- Numpy: 1.19.5

### Project file structure:
eng-french.txt: This is dataset for our project, contains English text and corresponding french texts.
langTraining.py: This file is used to create and train the model.
training_data.pkl: This file contains lists of characters, text of input, and target data in a binary format.
s2s: This directory contains optimizer, metrics, and weights of our trained model.
LangTransGui.py: Gui file of our project where we load the trained model and predict output for given text.

