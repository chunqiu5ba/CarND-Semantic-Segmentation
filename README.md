# Semantic Segmentation
### Introduction
In this project, you'll label the pixels of a road in images using a Fully Convolutional Network (FCN).

Based on the paper [Fully Convolutional Networks for Semantic Segmentation](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf)

![FCN](./results/FCN.PNG)

* 1- Encoder: Pre-trained VGG16 neural network
* 2- 1 x 1 convolution
* 3- Decoder: Transposed convolutions and skip connections

### Hyper-parameters
The following Hyper-parameters were used in training the FCN

| Parameter                        | Value   | 
|:--------------------------------:|:-------:| 
| Keep Probability                 | 0.5     | 
| Batch Size                       | 1       |
| Epochs                           | 20      |
| Learning Rate                    | 0.0001  |

Loss after 20 Epochs

![Loss](./results/loss.PNG)

### Samples

Below are a few sample images from the output of the fully convolutional network

![sample1](./results/1520555910.1116054/um_000003.png)
![sample2](./results/1520555910.1116054/um_000008.png)
![sample3](./results/1520555910.1116054/um_000013.png)
![sample4](./results/1520555910.1116054/um_000032.png)
![sample5](./results/1520555910.1116054/umm_000024.png)
![sample6](./results/1520555910.1116054/umm_000038.png)
![sample7](./results/1520555910.1116054/uu_000001.png)
![sample8](./results/1520555910.1116054/uu_000010.png)

### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)

### Run
Run the following command to run the project:
```
python main.py
```


 
