# ENDB2 SESSION 1

This contains solution to END Batch 2 Seesion 1

## OBJECTIVE 

### CREATE A NEURAL NETWORK  FOR XOR FUNCTIONALITY 

1.remove the last activation function

2.make sure there are in total 44 parameters

3.run it for 2001 epochs

### COLAB LINK 

<a href="https://colab.research.google.com/github/jitendramishra1024/ENDB2/blob/main/END2_0_Session_1.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

### QUESTION AND ANSWERS  :

#### What is a neural network neuron?

Neural network consist of 3 parts 
 
 a. INPUT b. WEIGHTS c. ACTIVATION FUNCTION d . OUTPUT 
 
 First all inputs are multiplied by weight matrix and bias is added .
 The result is passed through an activation function and that result will be output .
 

#### What is the use of the learning rate?
learning rate defines step size while updating weights .
if LR is high then convergence will be quick but we will miss minima 
If LR is small it will tak long time to converge 

### How are weights initialized?

There are many ways weight can be initialized .

a.zeros b.ones c.random d. Uniform  e. Normal f. He distribution g.Xavier distibution 


#### What is "loss" in a neural network?

Loss can be defined as how our prediction is different from actual output 

Loss can be of several type 

a.L1 loss  b. L2 loss c.NLL Loss d. Cross entropy loss

### What is the "chain rule" in gradient flow?

The chain rule comes into play when we need the derivative of an expression composed of
nested subexpressions. It helps to solve problems by breaking complicated expressions into
subexpression whose derivatives are easy to compute.
