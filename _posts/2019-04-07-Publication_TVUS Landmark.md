---
layout: post
title:  "Region-guided adversarial learning for anatomical landmark detection in uterus ultrasound image"
date:   2019-04-07
excerpt: "SPIE Medical Imaging 2019"
publication: true
tag:
- Adversarial Learning
- Transvarginal Ultrasound
- Landmark Detection
comments: true
---
{% capture images %}
   https://www.spiedigitallibrary.org/ContentImages/Proceedings/10949/1094937/FigureImages/00192_PSISDG10949_1094937_page_2_1.jpg
{% endcapture %}
{% include gallery images=images cols=1 %}

## Abstract
The length and thickness of the uterus and endometrium are morphology characteristics as important measures for uterine diagnosis. In diagnosing uterine, doctors mark anatomical landmark points of uterus and endometrium in order to measure their length and thickness. However, it is difficult to reliably detect the landmarks of the uterus and endometrium due to the ambiguous boundaries and heterogeneous textures of uterus transvaginal ultrasound image. In this paper, we propose a novel region-guided adversarial learning framework for anatomical landmark detection in transvaginal ultrasound image, aiming at automatically detecting the landmark points of uterus and endometrium of transvaginal ultrasound image to a diagnostical precision. In the proposed adversarial learning scheme, the proposed framework consists of a landmark predictor and two discriminators for the uterus and endometrium. The proposed landmark predictor is to detect the desired landmarks of both uterus and endometrium regions from transvaginal ultrasound image. The discriminator is to determine whether the predicted landmarks of uterus and endometrium are related with their regions or not (i.e., whether the predicted landmark points are on the region boundaries or not.). By adversarial learning between the predictor and the discriminators with uterus and endometrium region images, the performance of the landmark predictor can be improved. In testing, with the trained predictor only, uterus and endometrium landmarks are predicted. Experimental results demonstrated that the proposed method achieved a high accuracy in detecting landmarks of the uterus and endometrium in the ultrasound image.
* Full paper can see in [Here](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10949/2512731/Region-guided-adversarial-learning-for-anatomical-landmark-detection-in-uterus/10.1117/12.2512731.full?SSO=1&tab=ArticleLink)
