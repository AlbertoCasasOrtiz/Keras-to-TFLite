# Keras-to-TFLite
Colab notebook for converting a keras model into tflite.

Given a json file describing the structure of the keras model, and a h5 file containing the weights of the model, this script generates a h5 file containing both the model and the weights, and a **tflite** file.

Tested with FFN, CNN and LSTM.
