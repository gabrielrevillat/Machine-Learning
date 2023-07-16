# Introduction

## What is *machine learning*?

* It is a branch of artificial intelligence
* It allows us to create prediction, estimation and control systems (*intelligent agents*)
* It allows us to find patterns in data sets or organize data sets

## Advantages and disadvantages

### Advantages

* It allows the creation of solid models with a clear mathematical methodology
* It has a growing interest in modern society
* AI is the future
* It uses beautiful branches of maths

### Disadvantages

* All models will be as good as the input data
* Garbage in, Garbage Out (GIGO)
* "It uses beautiful branches of maths"

## Building stages

* Analyze the type of problem
    * What features does it have?
    * What are we trying to achieve?
* Analyze the data
    * What data do we have?
    * What patterns does it have?
* Implement a model
* Evaluate the model
* Refine the implemented model

## Types of learning

* **Supervised learning**: Learning by using examples
* **Unsupervised learning**: Learning interesting patterns and behaviours from a data set
* **Reinforcement learning**: Learning how to behave in an environment, receiving feedback from the system

### Example

Suppose there is a function *f(x) = y*

* **Supervised learning**: We know *(x, y)* and try to find *f* (actually an approximation of *P(x | y)*)
* **Unsupervised learning**: We know *x* and try to find an "interesting" *f* and *y*
* **Reinforcement learning**: We know *f* and try to maximize *y* by choosing *x*

## Instance and model based learning

* **Instance-based learning**: Training data is an integral part of the model
    * Training data is required as a part of the final model (e.g. the *k*-neighbours algorithm)
* **Model-based learning**: Training data is used for train the model, but is then discarded
    * The final result is the predicting model itself (e.g. the resulting neural network after training)

## Supervised learning

* We give the algorithm a set of *x*'s with their respective *y*'s and it finds a general connection between them
* The learned function is not simple memory (Rote learning), but it allows to estimate *x* values never seen before
* By allowing to estimate, allows us to extrapolate from the original data set

### Who are *x* and *y*?

* Our *x* is not necessarily a unique value
    * It may be a vector (an input data set)
* Function *f* receives the vector *x* and produces a result *y*
* It allows us to perform operations on them such as addition, substraction, multiplication by scalar and the most important: dot product

## Vectors, matrices and tensors

* **Vector**: In a simplified way, an ordered list of numbers
* **Matrix**: In a simplified way, a 2D grid of numbers
    * We can represent a matrix as a vector by "flattening" the matrix.
* **Tensor**: It allows us to represent objects in higher dimensions
    * 10 000 images of 28x28 pixels in a gray scale would be a tensor of 10000x28x28
    * At a memory level, tensors store data continously (*nested array*)