---
title: "An Analysis of Untargeted Poisoning Attack and Defense Methods for Federated Online Learning to Rank Systems"
collection: publications
permalink: /publication/2023-ictir-poisoning-attack-foltr
excerpt: ''
date: 2023-07-04
venue: 'International Conference on Theory of Information Retrieval (ICTIR)'
authors: '<strong>Shuyi Wang</strong>, Guido Zuccon'
track: 'Full Paper'
pdf_url: "https://dl.acm.org/doi/abs/10.1145/3578337.3605117"
code_url: "https://github.com/ielab/foltr-attacks"
---

## Abstract

Federated online learning to rank (FOLTR) aims to preserve user privacy by not sharing their searchable data and search interactions, while guaranteeing high search effectiveness, especially in contexts where individual users have scarce training data and interactions. For this, FOLTR trains learning to rank models in an online manner -- i.e. by exploiting users' interactions with the search systems (queries, clicks), rather than labels -- and federatively -- i.e. by not aggregating interaction data in a central server for training purposes, but by training instances of a model on each user device on their own private data, and then sharing the model updates, not the data, across a set of users that have formed the federation. Existing FOLTR methods build upon advances in federated learning.

While federated learning methods have been shown effective at training machine learning models in a distributed way without the need of data sharing, they can be susceptible to attacks that target either the system's security or its overall effectiveness.

In this paper, we consider attacks on FOLTR systems that aim to compromise their search effectiveness. Within this scope, we experiment with and analyse data and model poisoning attack methods to showcase their impact on FOLTR search effectiveness. We also explore the effectiveness of defense methods designed to counteract attacks on FOLTR systems. We contribute an understanding of the effect of attack and defense methods for FOLTR systems, as well as identifying the key factors influencing their effectiveness.

Recommended citation:
```
@inproceedings{wang2023analysis,
  title={An Analysis of Untargeted Poisoning Attack and Defense Methods for Federated Online Learning to Rank Systems},
  author={Wang, Shuyi and Zuccon, Guido},
  booktitle={Proceedings of the 2023 ACM SIGIR International Conference on Theory of Information Retrieval},
  pages={215--224},
  year={2023}
}
```
