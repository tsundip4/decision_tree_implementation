Overview:
This project implements a Decision Tree classifier from scratch using Python, without relying on machine learning libraries like scikit-learn.
The tree is built recursively, selecting the best feature at each node based on Information Gain (Entropy) and 
splitting the dataset until a stopping condition is met.

Objective:
The main objective is to understand how decision tree works under the hood. This code shows how features are choose to divide the training sample.
A good way to learn entropy, information gain, recursive function, and data splitting.

How the Decision Tree Works
-Start with all training data at the root node
-Calculate entropy of the current node
-Compute information gain for each feature
-Select the feature with the highest information gain
-Split the data into left and right nodes
-Recursively repeat the process for each child node
Stop recursion when:
  max depth reached
  All labels are the same, or
  No features remain, or
  No data remains


technologies Used: I have used following technologies here:
  Python
  NumPy
  Google colab



