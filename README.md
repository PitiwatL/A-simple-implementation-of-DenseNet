# A-simple-implementation-of-DenseNet121

This is a very simple implementation of DenseNet121 where one could modify some layers. To make sure that this implementation is correct, I try to test the result on CIFAR10.
The result for the first 5 epochs of training:

| Model  | Result (%) |
| ------------- | ------------- |
| Original DenseNet121 without ImageNet weights (20 epochs)  | 16.17  |
| Original DenseNet121 with the fixed ImageNet weights  | 61.15  |
| Original DenseNet121 with the adjustable ImageNet weights  | 82.06  |
| Implemented DenseNet121 without ImageNet weights (20 epochs) | ...  |
| Implemented DenseNet121 with the adjustable ImageNet weights  | ...  |
| Custom DenseNet121 witout ImageNet weights  | ...  |


A dense block:
![Dense Block](https://user-images.githubusercontent.com/81637352/212792833-f42d417c-e9f4-429e-b00d-dbf2e7be8a05.jpg)

The ImageNet weights of a pre-trained DenseNet 121 can be downloaded using the keras-team's link:
https://github.com/keras-team/keras-applications/releases/download/densenet/densenet121_weights_tf_dim_ordering_tf_kernels_notop.h5
