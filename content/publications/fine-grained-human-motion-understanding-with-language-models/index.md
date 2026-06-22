---
title: Fine-grained Human Motion Understanding with Language Models
authors:
  - Thomas Markhorst
  - Zhi-Yi Lin
  - Jouh Yeong Chew
  - Jan van Gemert
  - Xucong Zhang
author_notes:
  - ""
date: 2026-06-22T09:36:29.779Z
publishDate: 2026-06-22T09:36:29.779Z
publication_types:
  - article-journal
publication: "pre-print"
publication_short: ""
abstract: |
  In this work, we propose FiGMo, an LLM-based model for fine-grained human motion understanding that represents motion as a sequence of skeletal poses with explicit timestamps for each pose. Each pose encodes body joint positions and is temporally grounded with timestamp tokens, allowing the model to reason about motion order, duration, and rhythm. To study what supervision is needed for motion-language reasoning, we construct a diverse training mixture spanning pose captioning, pose question answering, motion captioning, and motion question answering. Our ablations show that the primary gains come from the diversity of pose- and motion-level supervision, while staged training provides a smaller additional benefit. Different from previous works that rely on ground-truth 3D motion capture, our approach supports both 2D and 3D skeletal motion representations through a unified pose encoder, and can optionally incorporate video to provide contextual information. Extensive experiments on BABEL-QA, HuMMan-QA, CompMo, NTU-RGB+D, and QEVD-Coach demonstrate that our method achieves state-of-the-art performance across multiple benchmarks, highlighting the effectiveness of explicit temporal encoding and diverse pose- and motion-level supervision for fine-grained human motion understanding. Notably, even when using only 2D skeletal input, our approach surpasses previous 3D-based methods
summary: One-line takeaway for readers skimming listings.
tags: null
featured: true
hugoblox:
  ids:
    arxiv: ""
links:
  - type: pdf
    url: https://thomas-markhorst.github.io/uploads/figmo_preprint.pdf
  - type: code
    url: ""
  - type: dataset
    url: ""
  - type: poster
    url: ""
  - type: project
    url: ""
  - type: slides
    url: ""
  - type: source
    url: https://thomas-markhorst.github.io/uploads/figmo_preprint.pdf
  - type: video
    url: ""
image:
  caption: "Image credit: [**Unsplash**](https://unsplash.com)"
  focal_point: ""
  preview_only: false
projects: []
slides: ""
status: published
---
<!-- Add the paper text or supplementary notes. Markdown, math, and code are supported. -->
