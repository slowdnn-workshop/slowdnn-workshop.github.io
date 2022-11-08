---
layout: home
title: Home
permalink: index.html
nav_order: 0
---

{% include splash.html %}

**Join Us in Abu Dhabi from 3-7 January 2023!**
{: .text-center .fs-7 }

[Register here](https://docs.google.com/forms/d/e/1FAIpQLScMqcyVsrldFpZPwjajr2hcYz9aKx5V3riFNAEUQ7vswlrw7g/viewform) for in-person and remote participation.
{: .text-center .fs-6 }

See [the call for papers]({{site.base}}/submission) for guidelines and
more details about submitting.  
{: .text-center .fs-5 }

[Travel grants]({{site.base}}/travel) are available for authors of accepted
papers.
{: .text-center .fs-5 }


## Key Dates and Deadlines

- Workshop dates: **3rd - 7th January, 2023**; in person at
  [MBZUAI](https://mbzuai.ac.ae/), Abu Dhabi 
- Submission portal opens: **October 1st, 2022**
- Paper submission deadline: **November 6th, 2022**
- Acceptance and travel grant notification: **November 14th, 2022**

The top accepted papers will
be recommended for inclusion in a future special issue of the IEEE Journal of
Selected Topics in Signal Processing.


# Workshop Themes

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

{% include sponsors.html %}

