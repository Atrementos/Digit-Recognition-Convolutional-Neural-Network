## Convolutional Neural Network for Digit Recognition

- Uses only numpy and matplotlib libraries
- Expects input of shape (N, 28, 28)
- Adam optimizer is used for faster convergence and minimal hyperparameter tweaking
- Saliency via occlusion is performed on some examples to determine the most important parts of input images

#### Architecture

1. Convolution layer with 8 filters of size 3x3, no padding.
2. ReLU activation.
3. Max pooling layer with 2x2 filter and stride 2.
4. Flatten layer.
5. Dense Layer with 1352 units.
6. Softmax activation

#### Dataset

[MNIST handwritten digit database](yann.lecun.com/exdb/mnist/) was used for training.
