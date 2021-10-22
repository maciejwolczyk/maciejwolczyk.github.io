---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Zero Time Waste
====
![Scheme of the Zero Time Waste model](/images/ztw.png)


**Abstract:** The problem of reducing processing time of large deep learning models is a fundamental challenge in many real-world applications. Early exit methods strive towards this goal by attaching additional Internal Classifiers (ICs) to intermediate layers of a neural network. ICs can quickly return predictions for easy examples and, as a result, reduce the average inference time of the whole model. However, if a particular IC does not decide to return an answer early, its predictions are discarded, with its computations effectively being wasted. To solve this issue, we introduce Zero Time Waste (ZTW), a novel approach in which each IC reuses predictions returned by its predecessors by (1) adding direct connections between ICs and (2) combining previous outputs in an ensemble-like manner. We conduct extensive experiments across various datasets and architectures to demonstrate that ZTW achieves a significantly better accuracy vs. inference time trade-off than other recently proposed early exit methods.
**Paper:** [Link](https://arxiv.org/abs/2106.05409)
**Code:** [Link](https://github.com/gmum/Zero-Time-Waste)



Continual World
====
![CW20 from Continual World](/images/continual_world.png)


**Abstract:** Continual learning (CL) --- the ability to continuously learn, building on previously acquired knowledge --- is a natural requirement for long-lived autonomous reinforcement learning (RL) agents. While building such agents, one needs to balance opposing desiderata, such as constraints on capacity and compute, the ability to not catastrophically forget, and to exhibit positive transfer on new tasks. Understanding the right trade-off is conceptually and computationally challenging, which we argue has led the community to overly focus on catastrophic forgetting.  In response to these issues, we advocate for the need to prioritize forward transfer and propose Continual World, a benchmark consisting of realistic and meaningfully diverse robotic tasks built on top of Meta-World as a testbed. Following an in-depth empirical evaluation of existing CL methods, we pinpoint their limitations and highlight unique algorithmic challenges in the RL setting. Our benchmark aims to provide a meaningful and computationally inexpensive challenge for the community and thus help better understand existing and future solutions.
**Paper:** [Link](https://arxiv.org/abs/2105.10919)
**Code:** [Link](https://github.com/awarelab/continual_world)

