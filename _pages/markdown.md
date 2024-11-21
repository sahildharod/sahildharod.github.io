---
permalink: /markdown/
title: ""
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## Domain Generalization in Multimodal Machine Learning

*Research project with [Prof.Preethi Jyothi](https://www.cse.iitb.ac.in/~pjyothi/), In Collaboration with Google DeepMind*

Several state-of-the-art VLMs (e.g. CLIP, BLIP-2) have achieved near-perfect performance on widely-used image-text retrieval benchmarks such as MSCOCO-Test-5K and Flickr30K-Test-1K. As a measure of out-of-distribution (OOD) generalization, prior works rely on zero-shot performance evaluated on one dataset (Flickr) using a VLM finetuned on another one (MSCOCO). We argue that such comparisons are insufficient to assess the OOD generalization capability of models due to high visual and linguistic similarity between the evaluation and finetuning datasets.

To address this gap, we introduce WikiDO (drawn from Wikipedia Diversity Observatory), a novel cross-modal retrieval benchmark consisting of 380K image-text pairs scraped from Wikipedia to assess the OOD generalization capabilities of pretrained VLMs. My role in the project was to review literature and work with BLIP-2, a state-of-the-art VLM, establishing baseline metrics for image and text retrieval on Flickr and MS-COCO datasets, and using techniques like codebooks that learn discrete representations for images and text and feature-splitting to bridge the performance gap. 

Our work has been accepted at *NeurIPS 2024* in the Datasets and Benchmarks Track.

## Constrained Best Arm Identification in Grouped Bandits

In my B.Tech Thesis, I worked with *[Prof. Sharayu Moharir](https://sites.google.com/view/sharayu-homepage/home)* on deriving bounds for a multi-armed bandit problem. If we consider a scenario, where we want to find the best service centre where each of them provides multiple services, we would be interested in the one that has the highest average rating along with a constraint on the minimum rating for a service. 

In order to solve such problems, we developed an iterative algorithm to find the best arm among N arms, where each arm has M attributes, constrained to have mean above $\mu_{TH}$. Additionally, I also derived a lower \\(\mathcal{O}\left(H_{\text{id}}\right\\)$) and a upper bound \\(\mathcal{O}\left(H_{\text{id}}\ln \frac{H_{\text{id}}}{\delta}\right)\\) on the expected sample complexity in terms of the hardness index of the problem. Thus, we also demonstrated how hardness index is an effective and generalized tool to find bounds of a problem.

## Low Resource Voice Transfer for Speech Generation

This is an ongoing project under the guidance of *[Prof. Ganesh Ramakrishnan](https://www.cse.iitb.ac.in/~ganesh/)* and *[Prof.Preethi Jyothi](https://www.cse.iitb.ac.in/~pjyothi/)* in which we're currently analyzing models like VALL-E that view TTS as conditional language modelling for Indian languages. Our aim is to improve tokenizers and add dialect-specific blocks to improve voice transfer capabilities of the model for various Indian languages.