# This is a repository for various AI and ML Jupyter projects

## LINEAR REGRESSION (MACHINE LEARNING):
**Computer Hardware Performance:** This Dataset has info about hardware performance of various vendors and The goal of applying** linear regression** with these splits (80:20) and (90:10)  is to build a predictive model that can estimate hardware performance based on input features and then assess how well this model generalizes to new, unseen hardware configurations. The evaluation metrics used in both cases (e.g., mean squared error, R-squared) can help quantify the model's performance.

## KNN (MACHINE LEARNING):
**Heart Disease Dataset** The k-Nearest Neighbors algorithm is a supervised machine learning algorithm that can be used for both classification and regression tasks. In the context of a heart disease dataset, k-NN can be applied for classification, specifically to predict whether a patient has heart disease or not based on the provided attributes.
Heart disease dataset typically contains data related to various factors and attributes associated with heart disease, such as patient information, medical measurements, and possibly a target variable indicating whether a patient has heart disease or not. Some common attributes in these datasets might include age, sex, cholesterol levels, blood pressure, electrocardiogram (ECG) results, and more.

**Random Forest:** We have used ensemble algorithms to predict heart disease using the dataset and comparision is done with KNN algorithm.

## Iterative Deepening A Star Algorithm(ARTIFICIAL INTELLIGENCE):
**Maze Agent Problem** Given maze configuration, the task of the robot is to navigate in the maze and find the optimal path to reach the finish position. It can move to the north, south, west and east
direction. While navigating through the environment it has obstacles like walls. For each transition, a path cost of +3 is added in search. Assume that the robot’s vision sensors are sensitive to the exposure to the sunlight and whenever it tries to move towards the east direction resulting in incurring an additional penalty of +5 cost. Use Manhattan distance as a heuristic wherever necessary.

**Hill climbing** Hill climbing is a simple and intuitive optimization algorithm used in the field of artificial intelligence and optimization. It is a local search algorithm that starts with an arbitrary solution to a problem and iteratively makes small incremental changes to the solution, moving in the direction that improves the solution's quality. The goal of hill climbing is to find the best possible solution within a local neighborhood of the current solution. The maze problem is solved again using hill climbing local search and both approach are compared.

## Deep Feed Forward Networks (DEEP NEURAL NETWORKS):
**Fashion MNist Dataset** The Fashion MNIST dataset is a popular dataset used in machine learning for image classification tasks. It serves as a replacement for the traditional MNIST dataset, which contains handwritten digits (0-9). In the case of Fashion MNIST, the dataset consists of grayscale images of various fashion items, and the goal is to classify these items into specific categories.
Number of Classes: 10
Classes/Labels: Each class corresponds to a different fashion item, such as T-shirt/top, trouser, pullover, dress, coat, sandal, shirt, sneaker, bag, and ankle boot.
Image Size: The images are 28x28 pixels in size, grayscale (black and white).
Number of Samples: There are 60,000 training images and 10,000 test images.
To apply a Deep Feedforward Neural Network (DFFN) to the Fashion MNIST dataset for classification, I have used feedforward neural network (also known as a multi-layer perceptron) with three layers: an input layer that flattens the input images, two hidden layers with 128 neurons each, and an output layer with 10 neurons for classifying fashion items into one of 10 categories. ReLU is used as the activation function in the hidden layers, and softmax is used in the output layer for multiclass classification.
