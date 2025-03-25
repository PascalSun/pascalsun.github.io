---
title: "TriagedMSA: Triaging Sentimental Disagreement in Multimodal Sentiment Analysis"
collection: publications
category: manuscripts
permalink: /publication/2024-11-12-paper-title-number-5
date: 2025-01-01
venue: 'IEEE Transactions on Affective Computing'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10819657/'
citation: '[TriagedMSA: Triaging Sentimental Disagreement in Multimodal Sentiment Analysis](https://aclanthology.org/2024.emnlp-demo.5) (Y. Luo et al.)'
---

Existing multimodal sentiment analysis models are effective at capturing sentiment commonalities across different modalities and discerning emotions. However, these models still face significant challenges when analyzing samples with sentiment polarity differences across modalities. Neural networks struggle to process such divergent sentiment samples, particularly when they are scarce within datasets. While larger datasets could help address this limitation, collecting and annotating them is resource-intensive. To overcome this challenge, we propose TriagedMSA, a multimodal sentiment analysis model with triage capability. Our model introduces the Sentiment Disagreement Triage Network, which identifies sentiment disagreement between modalities within a sample. This triage mechanism reduces mutual influence by learning to distinguish between samples of sentiment agreement and disagreement. To process these two sample types, we develop the Sentiment Selection Attention Network and the Sentiment Commonality Attention Network, both of which enhance modality interaction learning. Furthermore, we propose the Adaptive Polarity Detection (APD) algorithm, which ensures the generalizability of our model across different datasets, regardless of whether unimodal labels are available. The APD algorithm adaptively determines sentiment polarity disagreement or agreement between modalities. We conduct experiments on three multimodal sentiment analysis datasets: CMU-MOSI, CMU-MOSEI and CH-SIMS.v2. The results demonstrate that our proposed methodology outperforms existing state-of-the-art approaches.