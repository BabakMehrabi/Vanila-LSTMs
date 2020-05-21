# Vanila-LSTMs

In this jupyter notebook, I showcase how Vanila LSTMs can be used for two important sequence prediction problems. The goal is an
introduction modelling with LSTMs and their nuances:

**Echo Sequence Prediction problem:**

In this problem, a random sequence of numbers is given, and the model is supposed to learn to always output a certain index of the 
sequence, for instance the third element. If an LSTM can learn that, we have proved that LSMT are capable of memorizing certain parts
of a sequence.

**Predicting alphabet:**

We show how LSTMs can learn the whole alphabet and predict the next letter based on the sequence they are given. It will be shown 
how adding an embedding layer to the network can improve the results drastically, especially for those sequence learning problems
where there is no number (ordinal) relationshop between elements, such as predicting the next letter in the alphabet. However, 
applying an embedding layer to time-series problems is not recommended because here there is already an ordinal relationship between
the elements, and there is no need to learn an encoding for the elements.
Basically, embedding layers are not only used for NLP applications. They can be used in such use-cases as well.

