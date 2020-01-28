# Project: Machine Translation

In this notebook, I've built a deep neural network that functions as part of an end-to-end machine translation pipeline. The completed pipeline accepts English text as input and returns the French translation.

This process is divided in 3 steps:

* **Preprocessing** - convert text to sequence of integers.
* **Modeling** - create models which accept a sequence of integers as input and return a probability distribution over possible translations. After learning about the basic types of neural networks that are often used for machine translation, I have conducted some investigations and designed my own model.
* **Predicting** - run the model on English text and provide the French translation.

Part of the code was made available as a template. My task was to add some new functionality to the sections identified with  **'IMPLEMENTATION'** in the header.

This project was developed in the context of **Udacity's Natural Language Processing nanodegree**.