---
layout: page
title: Benchmark-CT
description: Benchmarking generative models on computational thinking tasks in elementary visual programming.
permalink: /projects/benchmarking-ct/
img: assets/img/projects/benchmarking-ct.png
github: https://github.com/machine-teaching-group/neurips2024-benchmark-ct
importance: 0
---

Benchmark-CT studies how well generative models solve computational thinking tasks in elementary visual programming settings.

We built this benchmark because strong performance on common LLM benchmarks does not necessarily transfer to elementary computational thinking tests. Our synthetic data covers both target skills, such as solution synthesis and multi-choice reasoning, and fine-grained skills, such as domain basics, code tracing, and grid synthesis. Each answer is paired with symbolic explanations derived from code execution.

<img class="project-detail-image" src="/assets/img/projects/benchmarking-ct.png" alt="Benchmark-CT evaluation figure" />

Using more than 100,000 generated tasks, we fine-tuned Llama-3.1-8B-Instruct and obtained LlamaCT. We observe substantial gains, especially when combining fine-grained tasks with symbolic explanations. At the same time, models still struggle to jointly reason about spatial, logical, and programming aspects, which motivates future work on symbolically informed fine-tuning for multimodal generative models.

You can read the paper in the [NeurIPS Datasets and Benchmarks track](https://papers.nips.cc/paper_files/paper/2024/hash/6d5e00006b65fcc55c3c1798da821663-Abstract-Datasets_and_Benchmarks_Track.html), access the preprint on [arXiv](https://arxiv.org/abs/2406.09891), and view the implementation on [GitHub](https://github.com/machine-teaching-group/neurips2024-benchmark-ct).
