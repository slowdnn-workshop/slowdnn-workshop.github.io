---
layout: home
title: Homepage
nav_exclude: true
permalink: index.html
---

# Third Workshop on Seeking Low-Dimensionality in Deep Neural Networks (SLowDNN)
### January 2023,&nbsp;[MBZUAI](https://mbzuai.ac.ae/), Abu Dhabi

We are currently in the midst of a data
revolution. Massive and ever-growing datasets, arising in science, health, or
even everyday life, are impacting many areas of society. Many of these
datasets are not only large -- they are high-dimensional, in the sense that each
data point may consist of millions or even billions of numbers. A basic
challenge spanning signal processing, statistics, and optimization is to
leverage lower-dimensional structures in high-dimensional datasets.
Low-dimensional signal modeling has driven developments both in theory and in
applications to a vast array of areas, from medical and scientific imaging, to
low-power sensors, to the modeling and interpretation of bioinformatics data
sets, just to name a few. However, massive modern datasets pose an additional
challenge: as datasets grow, data collection techniques become increasingly
uncontrolled, and it is common to encounter gross errors or malicious
corruptions, and nonlinearity. Classical techniques break down completely in
this setting, and new theories and algorithms are needed. 

To meet those challenges, there have been explosive developments in the study
of low-dimensional structures in high-dimensional spaces over the past two
decades. To a large extent, the geometric and statistical properties of
representative low-dimensional models (such as sparse and low-rank and their
variants and extensions) are now well understood. Many highly efficient and
scalable algorithms have been developed for recovering such low-dimensional
models from high-dimensional data. The working conditions and data and
computational complexities of these algorithms have also been thoroughly and
precisely characterized. These theoretical results and algorithms have
already revolutionized the practice of data science and signal processing, and
have had significant impacts on sensing, imaging, and information processing.
On the other hand, recently strong connections between deep neural networks and
low-dimensional models have emerged at multiple levels, in terms of learning
representations, network architectures, and optimization strategies. Such
connections do not only help explain many intriguing phenomena in deep
learning, but also provide new guiding principles for better network design,
optimization, robustness, and generalization of deep networks in both
supervised and unsupervised scenarios.

Given these exciting and less-exploited connections, this workshop aims to
bring together experts in machine learning, applied mathematics, signal
processing, and optimization, to share recent progress and foster
collaborations on the mathematical foundations of deep learning. As the
community begins to embrace the power of deep learning, with unprecedented new
challenges in terms of modeling and interpretability, we hope to stimulate
vibrate discussions towards bridging the gap between the theory and practice of
deep learning. 

# Key Dates

- Workshop dates: 3rd - 6th January, 2023; in person at
  [MBZUAI](https://mbzuai.ac.ae/), Abu Dhabi 
- Abstract submission deadline: TBA
- Acceptance notification: TBA

# Tentative Schedule

{% for module in site.modules %}
{{ module }}
{% endfor %}


# Organization Team

{% for staffer in site.staffers %}
{{ staffer }}
{% endfor %}

# Contact

For inquiries about the workshop or this website, please contact
[slowdnn.workshop@gmail.com](mailto:slowdnn.workshop@gmail.com).

