## Recognising Traffic Signs using Convolutional Neural Network
---
[![](https://img.shields.io/badge/keras-1.1.1-blue.svg)](#) [![](https://img.shields.io/badge/numpy-1.11.3-blue.svg)](#) [![](https://img.shields.io/badge/pandas-0.20.1-blue.svg)](#) [![](https://img.shields.io/badge/matplotlib-2.0.2-blue.svg)](#) 
<br />
Recognise the traffic signs from the images into 43 different category.

#### Model:
 - 3 Convolutional block with 32, 64 and 128 filters of 3x3 kernel size
 - Activation function used ReLu
 - Optimiser used Stochastic Gradient Descent (SGD)
 - Loss is Categorical Crossentropy


#### Dataset:
 - Link: [GTRSB](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset#Downloads)
 - 43 classes
 - More than 50,000 images in total
 - Large, lifelike database
 - Physical traffic sign instances are unique within the dataset 