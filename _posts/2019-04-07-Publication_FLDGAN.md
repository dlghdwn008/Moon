---
layout: post
title:  "Lightweight and Effective Facial Landmark Detection using Adversarial Learning with Face Geometric Map Generative Network"
date:   2019-04-07
excerpt: "IEEE Transactions on Circuits and Systems for Video Technology"
publication: true
tag:
- Facial Landmark Detection
- Geometric Prior-Generative Adversarial Network
- Face Geometric Map
comments: true
---
{% capture images %}
   
{% endcapture %}
{% include gallery images=images cols=1 %}

## Abstract
Facial landmark detection plays an important role in face analysis tasks. Moreover, it is used as a prerequisite in many facial related applications, the simplicity as well as effectiveness is essential in the facial landmark detection. In this paper, we propose an effective facial landmark detection network and associated learning framework with the geometric prior-generative adversarial network. The geometric priorgenerative adversarial network consists of one generator and two discriminators. The generator consists of encoder and two decoders. The encoder predicts facial landmark points. The decoders generate facial inner and contour geometric map from predicted landmark points. Generating face geometric maps from predicted landmark points helps the predicted landmark points represent the face geometric information including shape and configuration. The discriminators determine that the given geometric maps are generated from actual landmark points or estimated landmark points. Our proposed network is end-to-end trainable and only the encoder part is used simply as the facial landmark detector in the testing stage. To verify the effectiveness of the proposed method, we have conducted comprehensive experiments with benchmark data sets. The results have shown that the proposed method achieves comparable performances over recently proposed facial landmark detection methods with simple and effective facial landmark detection network.
* Full paper can see in [Here](https://ieeexplore.ieee.org/document/8633862)
