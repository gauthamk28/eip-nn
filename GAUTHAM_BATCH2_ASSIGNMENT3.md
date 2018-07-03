## Assignment 3

### Pointwise or 1x1 Convolutions:

1x1 convolution reduces the dimensions of the previous layer for faster computation.1x1 convoltuion does element wise product between the previous layer input and the filter and apply ReLU.Inorder to alter the height and width of the input layer , Max Pooling is used whereas **1x1 convolution is used to alter the depth of the input layer**

1x1 convolutions are added inorder to get a non-linearity layer , this can be achieved by adding the filters in the 1x1 with the same number of the depth of input layer.

1x1 convolution is used in inception network to **reduce the computation cost** of the network by reducing the depth.

![1x1 convolution](https://raw.githubusercontent.com/gauthamk28/eip-nn/master/1x1%20convolution.gif)

## Dilated Convolution

Dilated convolutions are convolutions which are applied to the input layer with defined gaps.Dilated convolution is used to **increase global receptive field** of the network exponentially and linear parameter accretion.

Dilated convolution is good for detecting the boundaries of objects. For example the images sent by Satellites to NASA,ISRO will be very huge , inorder to detect boundaries of forests , rivers,... Dilated convolutions can be used.

Dilated convolutions is used for edge detection.

With the help of dilated convolutions , we can train our neural network to compress JPG,PNG images.

![dilated convolution](https://raw.githubusercontent.com/gauthamk28/eip-nn/master/dilated%20convolutions.gif)

## Depthwise Separable Convolution

Standard convolution operation is slow to perform inorder to speed this up , Depthwise Separable convolution is used.Depthwise Separable Convolution **decreases the computation and number of parameters** when compared to standard.

Depthwise convolution process has 2 stages - filtering stage(convolution is applied to single input channel whereas convolution is applied to all input channels in regular convolution) and combining stage(pointwise convolution)

Depthwise convolutions have few parameters when compared to regular convolutions.As there are only few parameters , they reduce the computation and hence they are cheaper and faster.

It is used in **Multi model networks , Xception,MobileNet**.