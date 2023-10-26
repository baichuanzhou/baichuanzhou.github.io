---
layout: page
title: Intuitive Classification
description: Explain how neural networks classify in 2D space intuitively.
img: assets/img/projects/intuitive-classification/demo.png
importance: 1
category: 
---

[Interactive demo](https://baichuanzhou.github.io/Intuitive-Classification/). \
This project is partly inspired by [TensorFlow Playground](https://playground.tensorflow.org/)

<div class="row">
    <div class="col-12 mt-3 mt-md-0" style="display: flex; justify-content: center;">
        {% include figure.html path="assets/img/projects/intuitive-classification/demo.png" title="example dataset" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

# Background

I built this visualizer (interactive demo: [here](https://baichuanzhou.github.io/Intuitive-Classification/)) when I first learned about neural networks. I was (still am) absolutely amazed by how neural networks learn to transform representation space and shift input distribution. After playing with [TensorFlow Playground](https://playground.tensorflow.org/), I was a little perplexed as to how it works. (Backthen I don't know much about machine learning in general). After some exploring and digging, I finally got some ideas in regards to what those visualizations mean. I felt that a more intuitive way would be to directly see how the representation space is shifted and transformed after passing through each layer. I didn't find anything that can do this, so I built this visualizer with [React](https://react.dev/), and [TensorFlow.js](https://www.tensorflow.org/js). Code is available [here](https://github.com/baichuanzhou/Intuitive-Classification).

# Basic Usage

<div class="row">
    <div class="col-12 mt-3 mt-md-0" style="display: flex; justify-content: center;">
        {% include figure.html path="assets/img/projects/intuitive-classification/intro.gif" %}
    </div>
</div>

This visualizer is pretty self-explanatory.\
 On the top navigation, I designed some hyper-parameter tuning options. Compared to  [TensorFlow Playground](https://playground.tensorflow.org/), I added a few more options such as optimizer, normalization layer, initialization methods and which layer to visualize.\
 On the top right, users are allowed to define arbitrary number of layers with arbitrary number of neurons in each layer. Theorically, it supports up to one thousand neurons per layer (up to four layers).\
Two important visualizations here: the left one updates decision boundary in real time, the right one updates the output in the selected 2 dimensional space.

<div class="row">
    <div class="col-md-6 text-center">
        {% include figure.html path="assets/img/projects/intuitive-classification/decision-boundary.png" title="Decision Boundary" class="img-fluid rounded z-depth-1" %}
    <p class="caption">left visualization</p>
    </div>
    <div class="col-md-6 text-center">
        {% include figure.html path="assets/img/projects/intuitive-classification/output.png" title="Output" class="img-fluid rounded z-depth-1" %}
    <p class="caption">right visualization</p>
    </div>
</div>

# Interesting Properties

## 1. LayerNorm can act as a non-linear layer.

When I added the normalization methods to the navigation bar, I found that LayerNorm introduces non-linearality to the output distribution, which I did not expect.
## 2. Low dimension and XOR data


## 3. Shift and rescale of BatchNorm



