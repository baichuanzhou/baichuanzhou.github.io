---
layout: page
title: Intuitive Classification
description: Explain how neural networks classify in 2D space intuitively.
img: assets/img/intuitive-classification.png
importance: 1
category: 
---

This project is partly inspired by [Tensorflow Playground](https://playground.tensorflow.org/)

<div class="row">
    <div>
        {% include figure.html path="assets/img/intuitive-classification.png" title="example dataset" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

# Background

I built this visualizer when I first learned about neural networks. (Interactive demo: [here](https://baichuanzhou.github.io/Intuitive-Classification/)). I was (still am) absolutely amazed by how neural networks learn to transform representation space and shift input distribution. After playing with [Tensorflow Playground](https://playground.tensorflow.org/), I felt that if I could somehow show these 2D datapoints are shifted after passing through each hidden layers, some interesting properties of neural networks might pop up. And so I built this visualizer with React, Javascript and tensorflow.js.

