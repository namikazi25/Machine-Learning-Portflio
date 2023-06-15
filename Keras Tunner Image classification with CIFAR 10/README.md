<h1> CIFAR-10 Keras Tuner Model</h1> 
<p> In this project, I explore how to use the Keras Tuner library to search for the best hyperparameters for a CNN model on the CIFAR-10 image classification dataset. The goal is to build a model that can accurately classify images into ten different categories. I preprocessed the data by scaling the pixel values and one-hot encoding the class labels.

To search for the best hyperparameters, I used a RandomSearch algorithm to explore the hyperparameter space, including the optimal number of convolutional layers, the number of filters in each convolutional layer, the dropout rate, and the number of units in the dense layer. I then evaluated each candidate model using the validation accuracy metric.

After completing the search, I retrieved the best model(s) and evaluated its performance on the test set. I also provided an example of how to use the trained model to predict the label of a test image and display the image along with its predicted label.

I implemented the project in a Jupyter notebook using Python 3, Keras, TensorFlow, and Keras Tuner. The code is well-documented and easy to understand, making it a great starting point for exploring hyperparameter tuning for CNNs on image classification tasks.

This project can be further extended by using other tuning algorithms, exploring different architectures or optimization algorithms, or applying transfer learning techniques to improve the accuracy of the model. I believe this project can be a great addition to my portfolio, showcasing my ability to work with CNNs, hyperparameter tuning, and image classification tasks.</p>
