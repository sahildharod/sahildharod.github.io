---
permalink: /markdown/
title: ""
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## Domain Generalization in Multimodal Machine Learning

*Research project with [Prof.Preethi Jyothi](https://www.cse.iitb.ac.in/~pjyothi/)

Several state-of-the-art VLMs (e.g. CLIP, BLIP-2) have achieved near-perfect performance on widely-used image-text retrieval benchmarks such as MSCOCO-Test-5K and Flickr30K-Test-1K. As a measure of out-of-distribution (OOD) generalization, prior works rely on zero-shot performance evaluated on one dataset (Flickr) using a VLM finetuned on another one (MSCOCO). We argue that such comparisons are insufficient to assess the OOD generalization capability of models due to high visual and linguistic similarity between the evaluation and finetuning datasets.

To address this gap, we introduce WikiDO (drawn from Wikipedia Diversity Observatory), a novel cross-modal retrieval benchmark consisting of 380K image-text pairs scraped from Wikipedia to assess the OOD generalization capabilities of pretrained VLMs. My role in the project was to review literature and work with BLIP-2, a state-of-the-art VLM, establishing baseline metrics for image and text retrieval on Flickr and MS-COCO datasets, and using techniques like codebooks that learn discrete representations for images and text and feature-splitting to bridge the performance gap. 

Our work has been accepted at *NeurIPS 2024 in the Datasets and Benchmark Track

