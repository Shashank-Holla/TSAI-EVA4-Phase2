# Neural Style Transfer

This is to implement Neural Style transfer which allows an image to be reproduced with new artistic style. The model is deployed on AWS Lambda as well.

The algorithm takes three images, an input image, a content-image, and a style-image, and changes the input to resemble the content of the content-image and the artistic style of the style-image.

## Model Hyperparameters

* Optimizer : L-BFGS
* Loss function : Content Loss + Style Loss 

## Model Architecture

### Loss Functions

**Content Loss** - 

**Style Loss** - 

### Optimizer : L-BFGS

L-BFGS as a way of finding a (local) minimum of an objective function, making use of objective function values and the gradient of the objective function. Like the original BFGS, L-BFGS uses an estimate of the inverse Hessian matrix to steer its search through variable space, but where BFGS stores a dense nxn approximation to the inverse Hessian (n being the number of variables in the problem), L-BFGS stores only a few vectors that represent the approximation implicitly.

Unlike training a network, we want to train the input image in order to minimise the content/style losses. 
