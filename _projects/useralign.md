---
layout: page
title: UserAlign
description: Inference-time personalized alignment with a few user preference queries.
permalink: /projects/useralign/
img: assets/img/projects/useralign.png
github: https://github.com/machine-teaching-group/neurips2025-useralign/
importance: 1
---

UserAlign is an inference-time personalization method that aligns model responses with individual user preferences using only a few pairwise feedback queries.

The method is built on best-arm identification in logistic bandits and selects a personalized response from a fixed candidate pool. A key practical insight is that the original loss-based confidence set can shrink too slowly in practice, which increases query requirements. To address this, UserAlign treats observed preference feedback as consistent/noise-free and refines the confidence region using a consistent half-space set, updating the confidence set with version-space elimination. This tighter practical set enables faster identification of near-optimal personalized responses with fewer queries.

<img class="project-detail-image" src="/assets/img/projects/useralign.png" alt="UserAlign results figure" />

Across text and image generation tasks, UserAlign achieves effective personalization with low query budgets, showing that lightweight preference elicitation can be both practical and useful for deployment-oriented systems.

You can access the NeurIPS paper on [OpenReview](https://openreview.net/pdf?id=irYb8GGDyh), read the preprint on [arXiv](https://arxiv.org/abs/2511.02966), view the implementation on [GitHub](https://github.com/machine-teaching-group/neurips2025-useralign/), and open the [poster PDF](/assets/pdf/useralign-poster.pdf).
