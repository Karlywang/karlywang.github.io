---
title: "Effective and Privacy-preserving Federated Online Learning to Rank"
collection: publications
permalink: /publication/2021-ictir-fpdgd
excerpt: ''
date: 2021-07-11
venue: 'International Conference on the Theory of Information Retrieval (ICTIR)'
authors: '<strong>Shuyi Wang</strong>, Bing Liu, Shengyao Zhuang, Guido Zuccon'
track: 'Full Paper, &#x1F3C6; Best Student Paper Award'
pdf_url: "https://dl.acm.org/doi/abs/10.1145/3471158.3472236"
code_url: "https://github.com/ielab/fpdgd-ictir2021"
---

## Abstract

Online Learning to Rank (OLTR) has been primarily studied in the
centralised setting, where a central server is responsible to index the
searchable data, collect the users’ queries and search interactions,
and optimize ranking models. A drawback of such a centralised
OLTR paradigm is that it cannot guarantee user’s privacy as all data
(both the searchable one and the one related to user interactions)
is collected by the server.
In this paper, we propose a Federated OLTR method, called
FPDGD, which leverages the state-of-the-art Pairwise Differentiable Gradient Descent (PDGD) and adapts it to the Federated
Averaging framework. For a strong privacy guarantee, we further
introduce a noise-adding clipping technique based on the theory of
differential privacy to be used in combination with FPDGD.
Empirical evaluation shows FPDGD significantly outperforms
the only other federated OLTR method. In addition, FPDGD is more
robust across different privacy guarantee requirements than the
current method: our method is therefore more reliable for real-life
applications.

Recommended citation:
```
@inproceedings{wang2021effective,
  title={Effective and privacy-preserving federated online learning to rank},
  author={Wang, Shuyi and Liu, Bing and Zhuang, Shengyao and Zuccon, Guido},
  booktitle={Proceedings of the 2021 ACM SIGIR International Conference on Theory of Information Retrieval},
  pages={3--12},
  year={2021}
}
```
