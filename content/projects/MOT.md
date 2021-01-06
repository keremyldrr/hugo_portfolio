---
title: "Multiple Object Tracking with Tracktor"
date: 2020-06-10
draft: false

---

Implemented vanilla [Tracktor](https://arxiv.org/pdf/1903.05625.pdf) with [Faster-RCNN](https://arxiv.org/abs/1506.01497) using PyTorch. Added a basic motion model and also a reidentificaiton network as the paper suggested for Tracktor++ .  Developed using the [MOT16](https://arxiv.org/abs/1603.00831) benchmark and achieved following results on the training set.

{{<image  frame= "true" src= "img/mot.jpg"  caption="My results">}}

{{<image  frame= "true" src= "img/tracktor.jpg"  caption= "State of the art Tracktor++ results">}}



Source code can be found [here][1]



[1]:  https://github.com/keremyldrr/Multiple-Object-Tracking-with-Tracktor
