# Class_Activation_Map (Tensorflow)
This project includes three scripts that describe how to extract "Activation Map" to explain the performance of the neural network

1. `Class_Activation_Map_MNIST.ipynb` uses [Fashion MNIST dataset](https://github.com/zalandoresearch/fashion-mnist) dataset.<br>
The model is built by several Conv blocks and the validation accuracy reaches 85% after a few epochs. The result:
<img src="./mnist.jpg">
where the darker areas in backgound imply more attention the neural network paid. 

2. `Class_Activation_Map_CatandDogs.ipynb` uses [Cats vs Dogs](https://www.tensorflow.org/datasets/catalog/cats_vs_dogs) in the tensorflow_datasets, which is a binary classification problem. <br>
The validation accuracy reaches 0.87 after 25 epochs and a sample result is shown as, 
<img src="./result.jpg">
The highlightened areas, such as eyes and nose, play a significant role for neural network to classify a object.
