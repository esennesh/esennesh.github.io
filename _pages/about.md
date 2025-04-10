---
permalink: /
title: "The brain as a probabilistic feedback controller"
excerpt: "The brain as a probabilistic feedback controller"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

What gets you out of bed in the morning? Everything we do in life has a cost to
our [body budget](https://news.northeastern.edu/2020/12/01/your-brain-is-the-worlds-most-proficient-accountant-heres-how/),
and yet we do so much more with our lives than survive as minimally as possible.
Our situations change moment to moment, and ensuring our
well-being across those changes requires [*predictive regulation*: allostasis](https://www.sciencedirect.com/science/article/pii/S0301051121002350).

In every moment, our brains need to infer, from nothing but experience and sensorimotor
data: who am I, how do I feel, what's going on, and what can I do about it? Solving
this problem requires the brain to simulate your body and sensorium, and infer how
to control the body by [predictive coding](https://proceedings.neurips.cc/paper_files/paper/2024/hash/572a6f16ec44f794fb3e0f8a310acbc6-Abstract-Conference.html).

I am a Postdoctoral Research Fellow in applied deep learning at Vanderbilt University.
I work in the [Bastos Lab](https://www.bastoslabvu.com) with the titular Andre Bastos,
after finishing my PhD in the [Probabilistic Modeling Lab](https://jwvdm.github.io/)
with Jan-Willem van de Meent and the [Interdisciplinary Affective Science Lab](https://affective-science.org)
with Lisa Feldman Barrett and Karen Quigley.

Check out the equation that makes it happen!
$$\varepsilon_{z} := \nabla_{z} \log \gamma_{\theta}(z \mid \mathbf{z}_{\setminus z}) = \nabla_{z} \log p_{\theta}(z \mid \mathrm{Pa}(z)) + \sum_{v \in \mathrm{Ch}(z)} \nabla_{z} \log p_{\theta}(v \mid \mathrm{Pa}(v))$$
