---
title: "Federated Online Learning to Rank with Evolution Strategies: A Reproducibility Study"
collection: publications
permalink: /publication/2021-ecir-foltr-es-reproduce
excerpt: ''
date: 2021-01-01
venue: 'European Conference on Information Retrieval (ECIR)'
authors: '<strong>Shuyi Wang</strong>, Shengyao Zhuang, Guido Zuccon'
track: 'Reproducibility Paper'
pdf_url: "https://link.springer.com/chapter/10.1007/978-3-030-72240-1_10"
code_url: "https://github.com/ielab/foltr"
---

## Abstract

Online Learning to Rank (OLTR) optimizes ranking models using implicit users’ feedback, such as clicks, directly manipulating search engine results in production. This process requires OLTR methods to collect user queries and clicks; current methods are not suited to situations in which users want to maintain their privacy, i.e. not sharing data, queries and clicks.

Recently, the federated OLTR with evolution strategies (FOLtR-ES) method has been proposed to provide a solution that can meet a number of users’ privacy requirements. Specifically, this method exploits the federated learning framework and 𝜖-local differential privacy. However, the original research study that introduced this method only evaluated it on a small Learning to Rank (LTR) dataset and with no conformity with respect to current OLTR evaluation practice. It further did not explore specific parameters of the method, such as the number of clients involved in the federated learning process, and did not compare FOLtR-ES with the current state-of-the-art OLTR method. This paper aims to remedy to this gap.

Our findings question whether FOLtR-ES is a mature method that can be considered in practice: its effectiveness largely varies across datasets, click types, ranker types and settings. Its performance is also far from that of current state-of-the-art OLTR, questioning whether the maintained of privacy guaranteed by FOLtR-ES is not achieved by seriously undermining search effectiveness and user experience.


Recommended citation:
```
@inproceedings{wang2021federated,
  title={Federated Online Learning to Rank with Evolution Strategies: A Reproducibility Study},
  author={Wang, Shuyi and Zhuang, Shengyao and Zuccon, Guido},
  booktitle={European Conference on Information Retrieval},
  pages={134--149},
  year={2021},
  organization={Springer}
}
```
