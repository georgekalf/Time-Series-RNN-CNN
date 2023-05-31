![banner image](https://user-images.githubusercontent.com/61338647/170028290-c2b58093-8cf4-4ee9-b08b-77d0cc21e3f8.jpg)

# Time Series prediction with RNN and CNN models

The above models are designed to predict future faults in a time series based on past values. The models are composed of two main components: the Recurrent Neural Network (RNN) and the Convolutional Neural Network (CNN). 

The RNN is designed to learn temporal patterns and dependencies in the time series. Specifically, it takes input sequences and processes them sequentially while retaining a state that represents information from previous inputs. This allows the model to remember important patterns and dependencies in the data that are relevant for predicting future values. 

The CNN, on the other hand, is designed to learn spatial patterns in the time series. Specifically, it takes input sequences and applies a series of convolutional filters to detect and extract important features in the data. This allows the model to learn more complex patterns and dependencies that may be difficult to capture with a simple RNN architecture.

To implement this model, the time series data is first preprocessed by dividing it into input sequences and associated output sequences. These sequences are then fed into the model, which consists of a stack of convolutional layers, followed by a stack of RNN layers, followed by a stack of dense layers with a final output layer for prediction.

During training, the model minimizes the loss function between the predicted and actual output sequences using backpropagation and gradient descent. The model is trained to make accurate predictions by adjusting the weights of the various layers based on the errors in the predicted output.
