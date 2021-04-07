# Deep Learning Assignment-4_part_1_2
MNIST Classifier Using Numpy and Keras

# Part1 - NN MNIST Using Numpy 
1. Neural Nets MNIST 3 layer Model with Normalization prior Training
Training MNIST - Error and Accuracy Without Mini-Batch and dropout with Learning rate(0.005), Iterations ( 350 )
I:349 Train-Error:0.108 Train-Accuracy:1.0
Test-Error:0.653, Test-Accuracy:0.7073

2. Adding Dropout
The test accuracy improved from 0.7073 ~ 0.8065
Epoch:299 Training-Error:0.342-> Training-Accuracy:0.883, Test-Error:0.413 -> Test-Accuracy:0.8065

3. Adding Minibatch Gradient Descent (minibatch=64, lr=0.005) and experimented learning rate from 0.001 to 0.005 

First run (minibatch =128, lr=0.001):
Epoch:299 Training-Error:0.712-> Training-Accuracy:0.46, Test-Error:0.652 -> Test-Accuracy:0.6435

Second run (minibatch =64, lr=0.001):
Epoch:299 Training-Error:0.625-> Training-Accuracy:0.611, Test-Error:0.575 -> Test-Accuracy:0.7148

Third run (minibatch=64, lr=0.005):
Epoch:299 Training-Error:0.453-> Training-Accuracy:0.747, Test-Error:0.441 -> Test-Accuracy:0.8012

4. Adding Data Augmentation

First run (minibatch =64, lr=0.001):
Epoch:299 Training-Error:0.625-> Training-Accuracy:0.611, Test-Error:0.575 -> Test-Accuracy:0.7148

Second run (minibatch =64, lr=0.005):
Epoch:299 Training-Error:0.453-> Training-Accuracy:0.747, Test-Error:0.441 -> Test-Accuracy:0.8012

Third run (minibatch =100, lr=0.005):
Epoch:299 Training-Error:0.512-> Training-Accuracy:0.75, Test-Error:0.472 -> Test-Accuracy:0.7804

5. Plot the results and Confusion Matrix

# Part2 - NN MNIST Using Keras



