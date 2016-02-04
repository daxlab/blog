---
layout: post
title:  "What is Adagrad ?"
date:   2016-02-04 09:42:36
categories: ml 
tags: [Coursera mooc ml]
crosspost_to_medium: false
image: /assets/article_images/desktop.jpg
---

Adaptive Gradient Algorithm or Adagrad for short, is a general algorithm for choosing learning rate of a model by dynamically adapting to the dataset.
It calculates different learning rate for every feature of model.

Adagrad takes into account the distribution of data and makes it such that features that are more sparse in the data have a higher learning rate which translates into a larger update for that feature.

+ [Adagrad Journal paper][paper-link]
+ [Deep Learning optimization][dpo]


[dpo]: https://www.youtube.com/watch?v=0qUAb94CpOw
[paper-link]: http://www.jmlr.org/papers/volume12/duchi11a/duchi11a.pdf