---
layout: home
title: Homepage
nav_exclude: true
permalink: index.html
---

{% include splash.html %}

# Join Us in Abu Dhabi from 3-7 January 2023!

[Submit your work](https://openreview.net/group?id=mbzuai.ac.ae/SLowDNN/2023/Workshop) by
10/30/2022 on [OpenReview](https://openreview.net/group?id=mbzuai.ac.ae/SLowDNN/2023/Workshop).

See [the call for papers]({{site.base}}/submission.html) for guidelines and
more details about submitting.

Each accepted paper will receive a travel grant to attend the workshop.  See
[the travel page]({{site.base}}/travel.html) for more details.

## Key Dates and Deadlines

- Workshop dates: **3rd - 7th January, 2023**; in person at
  [MBZUAI](https://mbzuai.ac.ae/), Abu Dhabi 
- Abstract submission deadline: **October 30th, 2022**
- Acceptance notification: **November 7th, 2022**

# Workshop Abstract

In the past decade, deep learning has demonstrated unprecedented performance
across many different domains. Modern neural networks learn high-performing
nonlinear representations for complex multi-modal data (e.g. text and image)
*without labels*; they generate near-photorealistic high-resolution images from
random noise; and they efficiently reconstruct data from compressive, corrupted
measurements in various imaging and structural prediction tasks.

However, despite recent endeavors, the underlying principles behind their
success remain shrouded in mystery. At a fundamental level, each of these
successes, and numerous others in scientific and engineering applications, stem
from the low-dimensional structure present both in the training data and in the
networks themselves. This presents a significant opportunity to bring insights
from better-understood low-dimensional models to the setting of deep learning,
where models are notoriously plagued by issues of poor resource and data
efficiency, robustness, and generalization.

Given these exciting but relatively less-exploited connections, this workshop
aims to bring together experts in machine learning, applied mathematics, signal
processing, and optimization, to share recent progress and foster
collaborations on the mathematical foundations of deep learning. As the
community continues to embrace the power of deep learning, with unprecedented
new challenges in terms of modeling and interpretability, we hope to stimulate
vibrant discussions towards bridging the gap between the theory and practice of
deep learning, with low-dimensionality as a unifying focus.

{% include speakers.html %}

# Tentative Schedule

{% for module in site.modules %}
{{ module }}
{% endfor %}


# Organizers

{% include organizers.html %}

