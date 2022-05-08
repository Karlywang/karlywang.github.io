---
title: "Is non-IID Data a Threat in Federated Online Learning to Rank?"
collection: publications
permalink: /publication/2022-sigir-noniid-foltr
excerpt: ''
date: 2022-01-01
venue: 'International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR)'
authors: '<strong>Shuyi Wang</strong>, Guido Zuccon'
track: 'Full Paper'
pdf_url: "https://arxiv.org/abs/2204.09272"
code_url: "https://github.com/ielab/2022-SIGIR-noniid-foltr"
---

## Abstract
In this perspective paper we study the effect of non independent and identically distributed (non-IID) data on federated online learning to rank (FOLTR) and chart directions for future work in this new and largely unexplored research area of Information Retrieval. In the FOLTR process, clients participate in a federation to jointly create an effective ranker from the implicit click signal originating in each client, without the need to share data (documents, queries, clicks). A well-known factor that affects the performance of federated learning systems, and that poses serious challenges to these approaches, is that there may be some type of bias in the way data is distributed across clients. While FOLTR systems are on their own rights a type of federated learning system, the presence and effect of non-IID data in FOLTR has not been studied. To this aim, we first enumerate possible data distribution settings that may showcase data bias across clients and thus give rise to the non-IID problem. Then, we study the impact of each setting on the performance of the current state-of-the-art FOLTR approach, the Federated Pairwise Differentiable Gradient Descent (FPDGD), and we highlight which data distributions may pose a problem for FOLTR methods.We also explore how common approaches proposed in the federated learning literature address non-IID issues in FOLTR. This allows us to unveil new research gaps that, we argue, future research in FOLTR should consider. This is an important contribution to the current state of FOLTR field because, for FOLTR systems to be deployed, the factors affecting their performance, including the impact of non-IID data, need to be thoroughly understood.

Recommended citation:
```
@article{wang2022non,
  title={Is Non-IID Data a Threat in Federated Online Learning to Rank?},
  author={Wang, Shuyi and Zuccon, Guido},
  journal={arXiv preprint arXiv:2204.09272},
  year={2022}
}
```
