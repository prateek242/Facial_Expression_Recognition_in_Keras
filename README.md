# Facial_Expression_Recognition_in_Keras
In this task I have created a model that will be recognising human emotion based on the dataset that is given. Here we have a list of emotions that includes "Angry" , "Disgust", "Fear", "Happy", "Neutral", "Sad" and "Surprise".








Add alt text
No alt text provided for this image
I have divided the dataset into training and testing and this will be helping at the time of prediction.

The most important part of the project is creating layers of Convolutional Neural Network. CNNs are regularized versions of multilayer percetrons. Multilayer perceptrons usually mean fully connected networks, that is, each neuron in one layer is connected to all neurons in the next layer. 








Add alt text
No alt text provided for this image
First we have created a Convolutional layer. Convolutional layers convolve the input and pass its result to the next layer. To increase the stability of a neural network, I have used batch normalization that normalizes the output of a previous activation layer.

I have used 'relu'. ReLU stands for rectified linear unit, and is a type of activation function. Pooling layers reduce the dimensions of the data by combining the outputs of neuron clusters at one layer into a single neuron in the next layer. Dropout is used for regularization.

I have added two fully connected layers as well. The input to the fully connected layer is the output from the final Pooling or Convolutional Layer, which is flattened and then fed into the fully connected layer.








Add alt text
No alt text provided for this image
In the end we fit the model. We are training it for 15 complete cycle or epochs. We have set the learning rate at 0.00001 as it is a configurable hyperparameter used in training of neural network.








Add alt text
No alt text provided for this image
From the graph it is clearly shown that as the number of epochs increases the loss is reduced and the accuracy is increased.








Add alt text
No alt text provided for this image
