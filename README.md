# Homework7

When the convnet is modified to use Fashion-MNIST instead of MNIST, the model still performs well, but its accuracy is lower. On MNIST, the model typically reaches about 99% accuracy, while on Fashion-MNIST it is usually closer to 90–93%. The training times are nearly the same because both datasets have the same image size and number of samples. Overall, Fashion-MNIST is more difficult because clothing categories are visually more similar than handwritten digits.

If you add another Dense layer with 4096 neurons in Exercise 16.4, the model becomes much larger and more computationally expensive. That usually makes training and prediction slower, because there are far more weights to learn. Accuracy may improve a little, stay about the same, or even get worse if the model starts overfitting.

