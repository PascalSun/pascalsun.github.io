---
title: "Graph Embeddings for Non-IID Data Feature Representation Learning"
collection: publications
category: conferences
permalink: /publication/2022-12-05-paper-title-number-1
excerpt: 'Best Research Paper Award at AusDM 2022'
date: 2022-12-05
venue: 'Australasian Conference on Data Mining'
slidesurl: 'http://academicpages.github.io/files/PhD_Graph_Embeddings_for_Non_IID_Data_Feature_Representation_Learning.pdf'
paperurl: 'https://link.springer.com/chapter/10.1007/978-981-19-8746-5_4'
citation: 'Sun, Q., Liu, W., Huynh, D., Reynolds, M. (2022). Graph Embeddings for Non-IID Data Feature Representation Learning. In: Park, L.A.F., et al. Data Mining. AusDM 2022. Communications in Computer and Information Science, vol 1741. Springer, Singapore. https://doi.org/10.1007/978-981-19-8746-5_4'
---

Most machine learning models like Random Forest (RF) and Support Vector Machine (SVM) assume that features in the
datasets are independent and identically distributed (IID). However, many datasets in the real world contain structural
dependencies so neither the data observations nor the features satisfy this IID assumption. In this paper, we propose to
incorporate the latent structural information in the data and learn the best embeddings for the downstream
classification tasks. Specifically, we build traffic knowledge graphs for a traffic-related dataset and apply node2vec
and TransE to learn the graph embeddings, which are then fed into three machine learning algorithms, namely SVM, RF, and
kNN to evaluate their performance on various classification tasks. We compare the performance of these three
classification models under two different representations of the same dataset: the first representation is based on
traffic speed, volume, and speed limit; the second representation is the graph embeddings learned from the traffic
knowledge graph. Our experimental results show that the road network information captured in the knowledge graphs is
crucial for predicting traffic risk levels. Through our empirical analysis, we demonstrate knowledge graphs can be
effectively used to capture the structural information in no-IID datasets.