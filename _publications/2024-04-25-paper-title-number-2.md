---
title: "Are Graph Embeddings the Panacea?"
collection: publications
category: conferences
permalink: /publication/2024-04-25-paper-title-number-2
excerpt: 'An Empirical Survey from the Data Fitness Perspective'
date: 2024-04-25
venue: 'Pacific-Asia Conference on Knowledge Discovery and Data Mining'
slidesurl: 'http://academicpages.github.io/files/PAKDD___Are_Graph_Embeddings_the_Panacea_.pdf'
paperurl: 'https://link.springer.com/chapter/10.1007/978-981-97-2253-2_32'
citation: 'Sun, Q., Huynh, D.Q., Reynolds, M., Liu, W. (2024). Are Graph Embeddings the Panacea?. In: Yang, DN., Xie, X., Tseng, V.S., Pei, J., Huang, JW., Lin, J.CW. (eds) Advances in Knowledge Discovery and Data Mining. PAKDD 2024. Lecture Notes in Computer Science(), vol 14646. Springer, Singapore. https://doi.org/10.1007/978-981-97-2253-2_32'
---

Graph representation learning has emerged as a machine learning go-to technique, outperforming traditional tabular view
of data across many domains. Current surveys on graph representation learning predominantly have an algorithmic focus
with the primary goal of explaining foundational principles and comparing performances, yet the natural and practical
question “Are graph embeddings the panacea?” has been so far neglected. In this paper, we propose to examine graph
embedding algorithms from a data fitness perspective by offering a methodical analysis that aligns network
characteristics of data with appropriate embedding algorithms. The overarching objective is to provide researchers and
practitioners with comprehensive and methodical investigations, enabling them to confidently answer pivotal questions
confronting node classification problems: 1) Is there a potential benefit of applying graph representation learning? 2)
Is structural information alone sufficient? 3) Which embedding technique would best suit my dataset? Through 1400
experiments across 35 datasets, we have evaluated four network embedding algorithms – three popular GNN-based
algorithms (GraphSage, GCN, GAE) and node2vec – over traditional classification methods, namely SVM, KNN, and Random
Forest (RF). Our results indicate that the cohesiveness of the network, the representation of relation information, and
the number of classes in a classification problem play significant roles in algorithm selection.