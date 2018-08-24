---
layout: post
title: Activation functions
---

Activation function is used to determine the output of neural network like yes or no. It maps the
resulting values in between 0 to 1 or -1 to 1 etc. (depending upon the function).

### Sigmoid or Logistic Activation Function

Sigmoid function is used when we need to predict the probability as an output.

![_config.yml]({{ site.baseurl }}/images/sigmoid.png)

### Tanh Activation Function

This is like sigmoid but values ranges from -1 to 1.

`tanh(z) = (exp(z) - exp(-z)) / (exp(z) + exp(-z))`

![_config.yml]({{ site.baseurl }}/images/tanh.png)

### ReLU (Rectified Linear Unit) Activation Function

This function make value 0 for negative values and z for values(z) more than or equal to 0.

![_config.yml]({{ site.baseurl }}/images/ReLU.png)

### Leaky ReLU (Rectified Linear Unit) Activation Function

This does not make z 0 when it isnegative rather keep it as very small negative value

![_config.yml]({{ site.baseurl }}/images/Leaky-ReLU.jpeg)
