# MobileNets and ShuffleNets

This is to train MobileNet v2 model on custom dataset of flying obects consisting of small quadcopters, large quadcopters, Winged drones and flying birds. The model is trained by transfer learning. Also, the trained model is deployed on AWS Lambda.

**Run Results** - 

## Model parameters and hyperparameters

Optimizer : SGD
* Loss function: Cross Entropy loss
* Batch size = 32
* Epochs = 16
* L2 Regularization = 0.01

One Cycle Policy

* min LR = 0.001
* max LR = 0.01
* div_factor = 100
* Epochs to reach max LR = 8


