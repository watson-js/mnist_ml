# Hand-Written Digit Classification in Python
The MNIST dataset is a publicly available dataset for handwritten digits. The provided program uses python and existing frameworks to define a model that can predict handwritten digits with 99.3% accuracy.\



## Description
Strided-convolutional layers are used instead of pooling layers.  All convolutional layers are strided, but in this case, a special approach is taken. Springenberg, et al. experimented with the strided-convolutional method and found that "when pooling is replaced by an additional convolution layer with stride r = 2 performance stabilizes and even improves on the base model". After carefully researching options for the strided-convolutional approach, a model that incorporates batch normalization and dropout was selected.\
\
Springenberg, Jost T., et al., _Striving for Simplicity: The All Convolutional Net_, Cornell University, April 2015, [https://arxiv.org/abs/1412.6806](https://arxiv.org/abs/1412.6806), accessed 10/06/2021

