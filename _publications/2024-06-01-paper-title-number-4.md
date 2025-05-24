---
title: "Docs2KG: A Human-LLM Collaborative Approach to Unified Knowledge Graph Construction from Heterogeneous Documents"
collection: publications
category: conferences
permalink: /publication/2024-06-01-paper-title-number-4
excerpt: 'Uncovering Knowledge from Chaos'
date: 2025-04-23
venue: 'WWW 25: Companion Proceedings of the ACM on Web Conference 2025'
slidesurl: 'https://dl.acm.org/doi/pdf/10.1145/3701716.3715309'
paperurl: 'https://dl.acm.org/doi/10.1145/3701716.37153092'
citation: 'Qiang Sun, Yuanyi Luo, Wenxiao Zhang, Sirui Li, Jichunyang Li, Kai Niu, Xiangrui Kong, and Wei Liu. 2025. Docs2KG: A Human-LLM Collaborative Approach to Unified Knowledge Graph Construction from Heterogeneous Documents. In Companion Proceedings of the ACM on Web Conference 2025 (WWW 25). Association for Computing Machinery, New York, NY, USA, 801–804. https://doi.org/10.1145/3701716.3715309'
---

Enterprises generate vast amounts of unstructured documents, posing challenges for knowledge extraction and representation. Large language models (LLMs) offer strong potential for processing such data but struggle with factual accuracy and provenance. Knowledge graphs (KGs) provide a structured framework to address these limitations [6], yet constructing high-quality KGs from heterogeneous data remains a challenge. To address this issue, we present Docs2KG, a modular framework to build high-quality KGs from diverse unstructured documents. We first employs state-of-the-art document processing techniques to extract textual content, tabular data, and figures. The extracted information is then unified into a multifaceted KG with three aspects: (1) a Layout KG capturing document structural hierarchies, (2) a Metadata KG preserving document properties, and (3) a Semantic KG representing domain-specific entities and relationships. Docs2KG supports multiple construction paradigms for Semantic KG: ontology-based approaches, hybrid NLP pipelines with LLM verification, LLM-guided ontology generation, and specialized models for named entity recognition, event extraction, and causal relationship identification to enhance semantic coverage and accuracy. A key feature of Docs2KG is its human-in-the-loop verification interface, enabling iterative quality assessment and refinement of the resulting KGs. Docs2KG is openly available at https://docs2kg.ai4wa.com, with the aim of advancing knowledge graph construction research and accelerating enterprise applications through high-quality knowledge graph construction.