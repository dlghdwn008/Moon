---
layout: post
title:  "Mode Variational LSTM Robust to Unseen Modes of Variation: Application to Facial Expression Recognition"
date:   2019-04-07
excerpt: "AAAI 2019"
deeplearning: true
tag:
- LSTM
- Mode Variational LSTM
- Facial Expression Recognition
comments: true
---
{% capture images %}
  https://www.google.com/url?sa=i&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwiKgtvlm77hAhULvbwKHbDGBh8QjRx6BAgBEAU&url=https%3A%2F%2Fwww.semanticscholar.org%2Fpaper%2FMode-Variational-LSTM-Robust-to-Unseen-Modes-of-to-Baddar-Ro%2F7262219bcf91084d5c3a058fc2968363680d372a&psig=AOvVaw2HuFm8SvJ-QcyyC3QJFt8p&ust=1554734567640342
{% endcapture %}
{% include gallery images=images cols=1 %}

## Abstract
Spatio-temporal feature encoding is essential for encoding
the dynamics in video sequences. Recurrent neural networks,
particularly long short-term memory (LSTM) units, have
been popular as an efficient tool for encoding spatio-temporal
features in sequences. In this work, we investigate the effect
of mode variations on the encoded spatio-temporal features
using LSTMs. We show that the LSTM retains information
related to the mode variation in the sequence, which is irrelevant to the task at hand (e.g. classification facial expressions).
Actually, the LSTM forget mechanism is not robust enough
to mode variations and preserves information that could negatively affect the encoded spatio-temporal features. We propose the mode variational LSTM to encode spatio-temporal
features robust to unseen modes of variation. The mode variational LSTM modifies the original LSTM structure by adding
an additional cell state that focuses on encoding the mode
variation in the input sequence. To efficiently regulate what
features should be stored in the additional cell state, additional gating functionality is also introduced. The effectiveness of the proposed mode variational LSTM is verified using the facial expression recognition task. Comparative experiments on publicly available datasets verified that the proposed mode variational LSTM outperforms existing methods.
Moreover, a new dynamic facial expression dataset with different modes of variation, including various modes like pose
and illumination variations, was collected to comprehensively
evaluate the proposed mode variational LSTM. Experimental results verified that the proposed mode variational LSTM
encodes spatio-temporal features robust to unseen modes of
variation.
* Full paper can see in [Here](https://arxiv.org/pdf/1811.06937.pdf)
