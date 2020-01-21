
## Convolutional Neural Network for Image Recognition
## MNIST Digit Recognition:
### Network Architecture
- Input -->Block1[Conv1 -->Relu --> Pool1]-->Block2[Conv2 -->Relu --> Pool2]-->Block3[Conv3 -->Relu --> Pool3]-->Block4 -->[FC1--Relu] >Block5[FC2 --> Relu]-->Softmax
- Learning rate = 0.00010.0001

- Epochs = 100
- Minibatch size = 16
- Cost of training data after epoch 95: 0.016345
- Train Accuracy: 0.999059999999965
- Validation Accuracy: 0.9814
- Test Accuracy: 0.9835
- Learning Curve

![result](./1-MNIST_source/Learning%20Curve%20after%20adding%20L2.png)


- Showing correctly classified and miss classified Images

![result](./1-MNIST_source/miss_classfied%20after%20adding%20L2.png)


- Displaying feature maps of Digit 6

![result](./1-MNIST_source/featuremap1-6.png)




- Histogram of Output layer weights before and after L2 Regularizaation

![result](./1-MNIST_source/Histogram%20of%20output.png)

- Effect of L2 Regularization: 

![result](./1-MNIST_source/Histogram%20of%20output%20after%20adding%20L2.png)

