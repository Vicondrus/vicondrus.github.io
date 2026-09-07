---
layout: page
title: UserAlign
description: Inference-time personalization from a few pairwise preference queries, evaluated with real users across text and image generation.
permalink: /projects/useralign/
img: assets/img/projects/useralign.png
github: https://github.com/machine-teaching-group/neurips2025-useralign/
importance: 4
---

UserAlign is an inference-time personalization method that aligns model outputs with individual user preferences using only a few pairwise comparisons.

The method formulates response selection as best-arm identification in logistic bandits. By exploiting consistency in user feedback, it progressively narrows the set of plausible preference models and identifies a preferred response from a fixed pool of generated candidates.

<img class="project-detail-image" src="/assets/img/projects/useralign.png" alt="UserAlign results figure" />

We evaluate UserAlign across personalized text and image generation, including experiments with 960 human participants. At matched interaction budgets, UserAlign consistently improves over the iidBest baseline, showing that lightweight preference elicitation can effectively personalize model outputs for real users.

You can access the NeurIPS paper on [OpenReview](https://openreview.net/pdf?id=irYb8GGDyh), read the preprint on [arXiv](https://arxiv.org/abs/2511.02966), view the implementation on [GitHub](https://github.com/machine-teaching-group/neurips2025-useralign/), and open the [poster PDF](/assets/pdf/useralign-poster.pdf).
