---
layout: page
title: Benchmark-CT / LlamaCT
description: Multimodal LLM evaluation, symbolic synthetic-data generation, and model fine-tuning for computational reasoning in visual programming.
permalink: /projects/benchmarking-ct/
img: assets/img/projects/benchmarking-ct.png
github: https://github.com/machine-teaching-group/neurips2024-benchmark-ct
importance: 3
---

Benchmark-CT studies how well generative models solve computational-thinking tasks grounded in elementary visual programming. We compare open and closed generative models with school-student performance across synthesis and reasoning tasks.

To improve open models, we developed a symbolic synthetic-data pipeline covering solution synthesis, multiple-choice reasoning, domain basics, program tracing, and grid synthesis. From this pipeline, we selected 111,861 training examples with symbolic explanations derived from program execution.

<img class="project-detail-image" src="/assets/img/projects/benchmarking-ct.png" alt="Benchmark-CT evaluation figure" />

Using this data, we LoRA-fine-tuned Llama3-8B to create the LlamaCT family of models. The best model improves aggregate benchmark accuracy from 22.9% for Llama3-8B-Instruct to 53.0%, matching GPT-4o with combined visual and textual input on the benchmark.

You can read the paper in the [NeurIPS Datasets and Benchmarks track](https://papers.nips.cc/paper_files/paper/2024/hash/6d5e00006b65fcc55c3c1798da821663-Abstract-Datasets_and_Benchmarks_Track.html), access the preprint on [arXiv](https://arxiv.org/abs/2406.09891), and view the implementation on [GitHub](https://github.com/machine-teaching-group/neurips2024-benchmark-ct).
