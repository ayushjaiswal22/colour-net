# colour-net
Colour Black and White images using Convolutional Neural Networks
A Neural Network For Automatic Image Colorization

This project is a PyTorch version of the [ColorNet](http://hi.cs.waseda.ac.jp/~iizuka/projects/colorization/en/) issued on SIGGRAPH 2016. Please check out the original website for the details.

## Overview
* Net model
![...](https://github.com/ayushjaiswal22/colour-net/blob/master/images/model.png)

* Development Environment  
Python 3.5.1  
CUDA 8.0  

## Result
I just train this model for 10 epochs， so I think it will work better if train it more.

* Results  
![...](https://github.com/ayushjaiswal22/colour-net/tree/master/images/coloured/7.jpg)  
![...](https://github.com/ayushjaiswal22/colour-net/blob/master/images/b%26w/7.jpg)  
![...](https://github.com/ayushjaiswal22/colour-net/tree/master/images/coloured/4.jpg)  
![...](https://github.com/ayushjaiswal22/colour-net/blob/master/images/b%26w/4.jpg)  

For this network is trained by landscape image database, it's work well for scenery pictures. So if you use this network to color  images of other types, maybe you can't get a satisfying output.

