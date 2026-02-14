---
title: "BeST--A Novel Source Selection Metric for Transfer Learning"
collection: publications
# category: manuscripts
permalink: /publication/2025-01-01-best-source-selection
excerpt: ''
date: 2025-01-01
venue: 'arXiv'
# slidesurl: 'https://academicpages.github.io/files/slides3.pdf'
paperurl: 'https://arxiv.org/abs/2501.10933' 
# bibtexurl:''
citation: 'Soni, Ashutosh, Peizhong Ju, Atilla Eryilmaz, and Ness B. Shroff. "BeST--A Novel Source Selection Metric for Transfer Learning." arXiv preprint arXiv:2501.10933 (2025).'
publish_details: 'Published in arXiv, 2025'
---

One of the most fundamental, and yet relatively less explored, goals in transfer learning is the efficient means of selecting top candidates from a large number of previously trained models (optimized for various "source" tasks) that would perform the best for a new "target" task with a limited amount of data. In this paper, we undertake this goal by developing a novel task-similarity metric (BeST) and an associated method that consistently performs well in identifying the most transferrable source(s) for a given task. In particular, our design employs an innovative quantization-level optimization procedure in the context of classification tasks that yields a measure of similarity between a source model and the given target data. The procedure uses a concept similar to early stopping (usually implemented to train deep neural networks (DNNs) to ensure generalization) to derive a function that approximates the transfer learning mapping without training. The advantage of our metric is that it can be quickly computed to identify the top candidate(s) for a given target task before a computationally intensive transfer operation (typically using DNNs) can be implemented between the selected source and the target task. As such, our metric can provide significant computational savings for transfer learning from a selection of a large number of possible source models. Through extensive experimental evaluations, we establish that our metric performs well over different datasets and varying numbers of data samples. 