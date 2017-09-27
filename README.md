# Welcome to data shmiggler page!

### [Welcome to R shmiggler](R/main.md)
### welcome to Python shmiggler!
### welcome to Machine Learning shmiggler!

PyTorch: computational graph framework
=
The Supervised Learning Paradigm: the ground truth for the targets (what’s being predicted) are available for the observations (inputs).
Targets: Targets are labels. Following standard traditions in ML/DL, we will use y to refer to these.? Sometimes, this is known as ground truth.
Observations: Observations, also called inputs, are items we want to predict something about. We will use x to refer to these.
Model: A model is a mathematical expression or a function that takes an observation x and predict the value of its target label.
Parameters: Sometimes also called weights, these parameterize the model.? It is standard to use the notation w (for weights) or ?.?  
Predictions: Predictions, also called estimates, are the values of the targets guessed by the model, given the observations. We will denote these with a “hat”. So, the prediction of a target y is denoted as .
Loss function: A loss function is a function that compares how off a prediction is from its target for observations in the training data. Given a target and its prediction, the loss function assigns a scalar real value called the loss. Lower the value of the loss, the better the model is at predicting the target. We will use L to denote the loss function.


Name Entity Classification:
=
**reference** :https://blog.booking.com/on-diversity.html
3 approaches

1. Structural SVM

2. Recurrent Neural Networks with Word Embeddings 

3. Learning2Search

Goal: To recognize the following labels in textual strings:

destinations (dest)
property types (prop_type)
facilities (fac)


Use Case: The model should be able to process queries like the one above and place labels to the word they consist of. For instance, in the query “hotels amsterdam wifi” we would like to have the following labeling:
hotels:property type
Amsterdam:destination
wifi:facility

1. Structural SVM

First thing first, learn svm quickly in the following website:
https://www.analyticsvidhya.com/blog/2017/09/understaing-support-vector-machine-example-code/



This page is for data shmiggler!
