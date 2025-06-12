TASK-1: UNDERSATNDING SEARCH ALGORITHMS: 

This task demonstrates how to perform Breadth-First Search (BFS) and Depth-First Search (DFS) on an undirected graph, including disconnected components. It uses a class-based Python implementation for clarity and scalability.

Key Features:

Graph is implemented using an adjacency list with defaultdict(list) 

Supports adding edges 

Includes: 

bfs(start_node): Iterative BFS from a given start node 

dfs(start_node): Recursive DFS from a given start node 

bfs_full(): BFS traversal of the entire graph (even if disconnected) 

dfs_full(): DFS traversal of the entire graph (even if disconnected) 

BFS (Breadth-First Search) explores neighbors level by level using a queue. 

DFS (Depth-First Search) explores as far as possible down each path using recursion (or a stack).

Task 2: Image Classification using a Pre-Trained Model from TensorFlow Hub

In this task, a pre-trained image classification model is utilized from TensorFlow Hub to classify various images. The objective is to understand how to apply transfer learning using pre-trained models rather than training from scratch.

The notebook demonstrates how to load an image dataset.

It uses EfficientNet, a powerful pre-trained model, to predict the contents of input images.

The images are resized and normalized to match model input requirements.

It highlights the simplicity and efficiency of using TensorFlow Hub for quick deployment of advanced ML models in real-world applications.

This task emphasizes the power of transfer learning, reducing training time while achieving high accuracy.

This project is ideal for anyone exploring computer vision applications using modern deep learning models.

Task 3: Digit Recognition Using Neural Network (Keras + MNIST CSV)

This task builds a neural network using TensorFlow/Keras to recognize handwritten digits (0–9) from the MNIST dataset, provided in CSV format.

What the Program Does

Loads the training and testing data using Pandas

Normalizes pixel values (0–255 → 0–1)

Reshapes data to match image format (28x28)

Builds a simple neural network

Input layer: Flatten 28×28 image

Hidden layer: 128 neurons (ReLU)

Output layer: 10 neurons (Softmax for 0–9 digits)

Trains the model using training data

Evaluates it on test data

Displays predictions with actual digits using matplotlib
