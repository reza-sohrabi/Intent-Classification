# Intent Classification
This repository explores the task of classifying short written commands into 7 different classes. The data is taken from this  [repository](https://github.com/snipsco/nlu-benchmark/tree/master/2017-06-custom-intent-engines "repository").
In my first attempt, I have tried RNNs as my first architecture and have achieved almost 99% accuracy on the validation and train data.  The architechture is shown in the picture below.

![](https://github.com/reza-sohrabi-ucr/Intent-Classification/blob/master/images/arch2.PNG)

-----------------------------------------------------------------
I added the convolutional architecture as shown in the figure below and achieved similar results.

![](https://github.com/reza-sohrabi-ucr/Intent-Classification/blob/master/images/arch4.PNG)

-----------------------------------------------------------------
This is a work in progress, and I will explore other architectures, too.