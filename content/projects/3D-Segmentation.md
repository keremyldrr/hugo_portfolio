---
title: '3D Real-Time Instance Segmentation with LDLS-YOLACT'
date: 2020-07-04T23:30:14+02:00
---

In this project I've developed a 3D object detection and tracking pipeline for autonomous driving with Python and ROS without any labeled 3D data. Our hardware were only  a Livox mid-100 lidar sensor and a RealSense camera. After calibrating the sensors, the pipeline is as follows: 

- Get 2D instance segmentation of the current camera image using [YOLACT](https://arxiv.org/abs/1904.02689).
- Update the id numbers of the detected entitites using [SORT](https://arxiv.org/abs/1602.00763)
- Project the masks into 3D point cloud using [LDLS](https://arxiv.org/abs/1910.13955)
- Compute the 3D bounding boxes for the detected areas.

{{<youtube h26dd4iHiVg>}}

{{<youtube uLb_L60hxHc>}}

{{<youtube FFxR8pmEyY0>}}

Source code can be found  [here ](["https://github.com/keremyldrr/3D-Instance-Segmentation-with-LDLS-YOLACT"])page. For the implementation with ROS, please get in touch.
