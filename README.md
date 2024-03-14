# Emotion-Classification

In this assignment you will use the recurrent n/w representations
to classify tweets into six emotions anger, fear, joy, love, sadness and surprise. The data set is available
here: (https://www.kaggle.com/datasets/nelgiriyewithana/emotions)

Use representations obtained from 
a) RNN
b) LSTM
c) GRU
d) bi-LSTM
e) bi-GRU.
  
You can make use of any Python libraries of your choice that have implementations of the above n/ws.
Two possible choices are:
- The Pytorch library.
- The TensorFlow-Keras library. Keras 3 can work with Pytorch, TensorFlow or Jax as the backend.
  
**Notes**

- The data set is not balanced and has 6 classes so you will have to use a multiclass classifier. Use
the same classifier for all representations.
- Pick the representation from assignment 1 that worked best for you and run it on this data set
and use it as a comparison representation for the representations in this assignment.
