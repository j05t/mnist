# MNIST digit recognizer
 
## Results of this model on MNIST test data:
1. 0.22% test error rate with ensemble of 10 CNNs
2. 0.21% test error rate with ensemble of 6 selected CNNs
3. 0.26% test error rate for best single model

## Source code
See https://github.com/j05t/mnist/blob/master/mnist.ipynb. Models have been created and trained using the Theano Backend. The script has been adapted to work with the TensorFlow backend, but saving/loading training histories seem to be broken right now. Best model weights have been uploaded.

## Incorrect predictions
0.21% test error rate gives us a total of 21 incorrect predictions on the MNIST testing dataset of 10,000 images: 
![incorrect predictions](incorrect_predictions.png)
