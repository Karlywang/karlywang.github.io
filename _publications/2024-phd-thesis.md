---
title: "Effective and secure federated online learning to rank"
collection: publications
permalink: /publication/2024-phd-thesis
excerpt: ''
date: 2024-11-15
venue: 'The University of Queensland'
authors: '<strong>Shuyi Wang</strong>'
track: 'Thesis'
pdf_url: "https://karlywang.github.io/files/Shuyi Wang_phd_thesis.pdf"
code_url: 
---

## Abstract

Online Learning to Rank (OLTR) optimises ranking models using implicit user feedback, such as clicks. Unlike traditional Learning to Rank (LTR) methods that rely on a static set of training data with relevance judgements to learn a ranking model, OLTR methods update the model continually as new data arrives. Thus, it addresses several drawbacks such as the high cost of human annotations, potential misalignment between user preferences and human judgments, and the rapid changes in user query intents. However, OLTR methods typically require the collection of searchable data, user queries, and clicks, which poses privacy concerns for users.

Federated Online Learning to Rank (FOLTR) integrates OLTR within a Federated Learning (FL) framework to enhance privacy by not sharing raw data. While promising, FOLTR methods currently lag behind traditional centralised OLTR due to challenges in ranking effectiveness, robustness with respect to data distribution across clients, susceptibility to attacks, and the ability to unlearn client interactions and data. This thesis comprehensively investigates these challenges and proposes effective and secure FOLTR methods.

First, we address the effectiveness of FOLTR by identifying the limitations of existing work and proposing a new method, termed Federated Pairwise Differentiable Gradient Descent (FPDGD). By adapting Pairwise Differentiable Gradient Descent (PDGD) to the Federated Averaging framework, we significantly improve upon the previous method, as demonstrated by empirical evaluations.

Next, we examine the robustness of FOLTR under non independent and identically distributed (non-IID) data across clients. We identify four data distribution scenarios that can lead to non-IID issues and evaluate their impact on ranking performance. Additionally, we assess common federated learning approaches to mitigate these non-IID challenges in FOLTR.

We also investigate data and model poisoning attack strategies and their impact on FOLTR effectiveness. We explore robust aggregation rules for federated learning to counter these attacks, providing insights into the effectiveness of attack and defense methods in FOLTR systems and identifying key factors influencing their success.

Finally, we propose an efficient unlearning method to remove a client's contributions from the FOLTR system using historical local updates. To verify the unlearning process, we introduce a novel evaluation approach based on poisoning attacks.

In summary, this thesis presents a comprehensive study on Federated Online Learning to Rank, addressing its effectiveness, robustness, security, and unlearning capabilities, thereby expanding the landscape of FOLTR.


Recommended citation:
```
@article{wang2024effective,
  title={Effective and secure federated online learning to rank},
  author={Wang, Shuyi},
  year={2024}
}
```
