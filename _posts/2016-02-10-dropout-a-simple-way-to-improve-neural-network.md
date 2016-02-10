---
layout: post
title:  "Dropout - A simple way to improve Neural Network ?"
date:   2016-02-10 11:42:36
categories: ml
tags: ml
crosspost_to_medium: true
image: /assets/article_images/desktop.jpg
---

Dropout technique by [Hindon](https://www.cs.toronto.edu/~hinton/) is among recent pioneers in the field of neural network. The main objective
behind using Dropout is to tackle the problem of [overfitting](https://en.wikipedia.org/wiki/Overfitting). Dropout achieves this by selectively
turning off (dropping out) some of the activations in a layer during forward propagation and backpropagating through all activations turned on.

### Further readings

+ [Dropout: A Simple Way to Prevent Neural Networks from Overfitting][paper-link]
+ [How do you implement a dropout in neural network](quora-link)
+ [Udacity Deep Learning - Dropout](udacity-link)

[quora-link]: https://www.quora.com/How-do-you-implement-a-dropout-in-deep-neural-networks
[paper-link]: https://www.cs.toronto.edu/~hinton/absps/JMLRdropout.pdf
[udacity-link]: https://www.udacity.com/course/viewer#!/c-ud730/l-6379031992/m-6392358586
