 # Machine-Learning-Classifiers

Welcome to my Machine Learning projects! The work in this repository is split into two main projects: Project 1, and Project 2. Below you can find information about each project.


## Project 1: Bayesian / KNN Classification

In this project, I used MATLAB to implement classifiers given input data in the form of images. Below are the steps taken:

1. I split the data into test and training data, then trained a Bayesian and K-nearest neighbor classifier on the training data
    - Before training the classifiers, the data was projected into a different dimension using PCA and LDA/MDA
2. The test data was then run using the Bayesian classifier and K-nearest neighbor classifier, then accuracy was measured by comparing the test classification to the image's true classification.
    - For Bayesian classification, accuracy ranged from 82-97% on various runs. 

## Project 2: SVM / Neural Network Classification
 
In this project, I used Python/Jupyter Notebook to classify the MNIST dataset through SVM and a convolutional neural network. I used sklearn and tensorflow to implement/train the support vector machine and the convolutional neural network. For the neural network, these are the steps taken:

1. First, the CNN was created using two convolutional layers, each with a hyperbolic tangent activation function.
2. The CNN was then given a fully-connected neural network as the final layer, again with a hyperbolic activation function.
3. Next, the CNN was trained over 2 epochs with a batch size of 256 and used the Adam optimization method along with the cross entropy loss function. 

Both the SVM and CNN have accuracy consistently between 95 and 98 percent, demonstrating their correctness. 