# Homework 5

## Part 1
Define a neural network and training algorithm "from scratch." Use numpy to define the weights, gradients, and updates. You may use any other libraries you wish to perform the analysis. 

If you wish, you may use another similar language like Lua.

Your code should be in a python .py file, or an .ipynb file if you want to combine it with your analysis.

Details:
- The output neuron should use a logistic function.
- The loss should be the cross entropy function.
- Hidden neurons should use the ReLU activation function.
- You should have at least two hidden layers in your neural network.
- You should use matrix operations to compute the forward and backward pass.

## Part 2
An important part of drug discovery is predicting whether potential drugs will be toxic. The Tox21 data set is a large data set created by the NIH to aggregate information about which molecules are toxic to which receptors in the body. Here we will look at one type of toxicity in the Tox21 data set. More info here: https://www.bioinf.jku.at/publications/2016/fenvs-03-00080.pdf

Train and test your model on the Tox21 data set starting from the given example in tox21.ipynb. The task is to predict whether molecular compounds are toxic to the Nuclear Receptor Androgen Receptor, given 801 features derived from the molecular structure. The data is already split up into a train set of 12,060 training examples and 647 test examples. 

Your analysis should be in a .ipynb file.
