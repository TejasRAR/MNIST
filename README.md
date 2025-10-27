USING THE CLASSIC DATASET OF MNIST FOR HANDWRITTEN NUMBERS, I HAVE BUILT A DEEP NEURAL NETWORK WITH RELU (HIDDEN LAYERS) AND SOFTMAX (OUTPUT LAYER) AS ACTIVATION FUNCTIONS:

1.  97.04 % of Test Accuracy and 97.94 % of Train Accuracy has been obtained on the model, which is in the range of healthy to mildly overfit due to the 0.9% gap in Train and Test accuracy.

2.  This is a model built from scratch using Numpy and Tensorflow has been used only for the purpose of 'One-Hot Encoding'.

3.  Only L2 Regularization and HE weight initialisation has been implemented as of yet.

Yet to implement:
    1. Mini-Batch Gradient Descent
    2. Adam Optimisation Algorithm
    3. Dropout (Based on performance from options 1 & 2)
    4. Early Stopping (Based on performance from options 1 & 2)
    5. Learning Rate Scheduling (Based on performance from options 1 & 2)

Hopefully after the due implementations, i will get to observe a bump of 0.4 % - 0.8 % in the Test Accuracy, ~ 98 %.

Goal: Test Accuracy equal to or GREATER THAN 98 %
UPDATE: AS OF TODAY MY BEST ATTEMPT IS 97.57% Test Accuracy with L2 + HE
