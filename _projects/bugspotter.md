---
layout: page
title: BugSpotter
description: LLM generation and executable verification of debugging exercises, evaluated in a 741-student classroom deployment.
permalink: /projects/bugspotter/
img: assets/img/projects/bugspotter.png
logo_img: assets/img/projects/bugspotter-logo.svg
website: https://bugspotter.netlify.app
importance: 1
---

BugSpotter is an LLM-based pipeline for automatically generating code debugging exercises from programming-problem specifications.

The system synthesizes buggy programs and validates candidate exercises by compiling and executing them against the problem's test suite. Corrected programs must pass the tests, while buggy programs must exhibit a verified failure, allowing invalid generations to be filtered automatically.

<img class="project-detail-image" src="/assets/img/projects/bugspotter.png" alt="BugSpotter interface screenshot" />

We deployed BugSpotter in an introductory programming course with 741 students. The generated exercises covered varied difficulty levels and produced student performance comparable to instructor-created exercises.

You can access the paper on [ACM Digital Library](https://doi.org/10.1145/3641554.3701974), read the preprint on [arXiv](https://arxiv.org/abs/2411.14303), and explore the system on the [BugSpotter website](https://bugspotter.netlify.app).
