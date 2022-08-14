# Functional Api

## Introduction
The Keras functional API is a way to create models that are more flexible than the tf.keras.Sequential API. The functional API can handle models with non-linear topology, shared layers, and even multiple inputs or outputs.

## Data 
MNIST

## Tool
Keras

## Note
This notebook is a bit complicated than the notebook of sequential model. Since, we add validation part after the first fit.o keep an eye on how the model does on new data, it’s standard practice to reserve a subset of the training data as validation data: you won’t be training the model on this data, but you will use it to compute a loss value and metrics value. You do this by using the validation_data argument in fit(). Like the training data, the valida- tion data could be passed as NumPy arrays or as a TensorFlow Dataset object.
