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
    <div style="text-align:center">
        {% include figure.html path="assets/img/intuitive-classification.png" title="example dataset" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

# Background

I built this visualizer (interactive demo: [here](https://baichuanzhou.github.io/Intuitive-Classification/)) when I first learned about neural networks. . I was (still am) absolutely amazed by how neural networks learn to transform representation space and shift input distribution. After playing with [Tensorflow Playground](https://playground.tensorflow.org/), I was a little perplexed as to how it works. (Backthen I don't know much about machine learning in general). After some exploring and digging, I finally got some idea in regards to what each visualization means. I felt that a more intuitive way would be to directly see how the representation space is shifted and transformed after passing through each layer.  And so I built this visualizer with [React](), and [tensorflow.js](). I simply borrowed some ideas from the playgroud, and I ended up implementing the visualizer from the ground up. Code is available [here](https://github.com/baichuanzhou/Intuitive-Classification)

