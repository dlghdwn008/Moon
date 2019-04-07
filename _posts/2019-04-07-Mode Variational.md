---
layout: post
title:  "Object Bounding Box Critic Networks for Occlusion-robust Object Detection in Road Scene"
date:   2019-02-01
excerpt: "IEEE International Conference on Image Processing (ICIP2018)"
deeplearning: true
tag:
- Object detection
- Adversarial learning
- Actor-critic network
comments: true
---
{% capture images %}
   http://ivylabprev.kaist.ac.kr/research_results/Object%20Bounding%20Box-Critic%20Networks%20for%20Occlusion-Robust%20Object%20Detection%20in%20Road%20Scene_thum.png
{% endcapture %}
{% include gallery images=images cols=1 %}

## Abstract
Object detection in a road scene has received a significant
attention from research fields of developing autonomous
vehicle and automatic road monitoring systems. However,
object occlusion problems frequently occur in generic road
scenes. Due to such occlusion problems, previous object
detection methods have limitations of not being able to detect objects accurately. In this paper, we propose a novel
object detection network which is robust in occlusions. For
effective object detection even with occlusion, the proposed
network mainly consists of two parts; 1) Object detection
framework, 2) Multiple object bounding box (OBB)-Critic
network for predicting a BB map which estimates both object region and occlusion region. Comprehensive experimental results on a KITTI Vision Benchmark Suite dataset
showed that the proposed object detection network outperformed the state-of-the-art methods.
* Full paper can see in [Here](https://ieeexplore.ieee.org/document/8451034)
