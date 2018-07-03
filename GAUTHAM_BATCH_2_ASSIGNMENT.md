**GAUTHAM_BATCH_2_ASSIGNMENT 1**

#### Convolution:

Convolutions are one of the most critical , fundamental building blocks in image processing. In terms of deep learning an image convolution is 
an element-wise multiplication of two matrices(image and kernel)

The main use of convolution in the deep learning is to extract significant features from the input image with the help of kernels


#### Kernel:

A kernel is a small matrix(usually 3x3) that slides from left to right and top to bottom across a larger image to produce feature maps.

* Kernels are also called as Filters.
* Filters acts as feature detectors from the original input image
* Different values of filters produce different feature maps for the same input image
* We can perform operations such as edge detection , sharpening , blur,... just by changing the numeric values of the filter matrix



*Example:*
Consider an image as a matrix of pixel values,below is an image of 5x5 pixels and a 3x3 kernel sliding on the image from left to right,top to bottom
![Kernel running on a 5x5 px image](images/convolution.gif)


In the below example , a 3x3 Kernel is sliding on a 5x5 image and a 3x3 feature map is generated
![5x5 convolution](images/5x5%20convolution.gif)



## GIT HUB:
Signup for a Github account in www.github.com 

Download Github client from https://desktop.github.com

After installing it ,you can open and signup for a new account or login to your existing account,then you need to configure(to identify the commits you create) Git. 

To create a new project click on **Create new repository**(or click **Add local repository** in **File** menu)  and give the name,description and set the path of the repository.

Then click on Publish repository to publish your project.