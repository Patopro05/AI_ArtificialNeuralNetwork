# AI_ArtificialNeuralNetwork
## Goal.-  To train a Feedforward Neural Network model.
## Homework for the Course Artificial Intelligence.
-----------------------------------------
Team members: 

*Fernando Patricio Gutiérrez González 2010356*

*Axel Muñoz Baca 2132103*

*Ulises Castillo Díaz 2050354*

*Pablo Daniel Contreras Obregón 2055281*

This README.md contains the following instructions provided by the professor M. Sc. Daniel Isaias López Páez:
Instructions.-

The student will train a Feedforward Neural Network model in Google Colab using the Python programming language. This model will use the MNIST dataset; this dataset contains low-resolution images with handwritten digits from 0 to 9. The dataset is part of the Keras library. More information about this dataset: https://keras.io/api/datasets/mnist/

During data preprocessing, the "load_data()" function from the Keras library will be used to load the dataset and generate the training (train_data, train_labels) and test (test_data, test_label) datasets. The default data split provided by this function can be used.

A feedforward artificial neural network will be trained with the training data using the "fit" function from the scikit-learn library. The student will propose a structure for the feedforward artificial neural network. The activation function in the output layer should be softmax.

The type of loss function and optimizer to be used will be established. The metric to evaluate the training process will be accuracy.

Use the "evaluate" function to display the prediction accuracy of the model with the test dataset (test_data).

Perform 5 different predictions with the test dataset (test_data). In the result, display the prediction and the actual value.
