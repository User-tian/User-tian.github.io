---
title: "Exploring Unified Perspective For Fast Shapley Value Estimation"
collection: publications
permalink: /publication/simshap
date: 2023-11-02
venue: 'Arxiv'
paperurl: 'https://arxiv.org/abs/2311.01010'
status: 'preprint'
excerpt: Shapley values have emerged as a widely accepted and trustworthy tool, grounded in theoretical axioms, for addressing challenges posed by black-box models like deep neural networks. However, computing Shapley values encounters exponential complexity in the number of features. Various approaches, including ApproSemivalue, KernelSHAP, and FastSHAP, have been explored to expedite the computation. We analyze the consistency of existing works and conclude that stochastic estimators can be unified as the linear transformation of importance sampling of feature subsets. Based on this, we investigate the possibility of designing simple amortized estimators and propose a straightforward and efficient one, SimSHAP, by eliminating redundant techniques. Extensive experiments conducted on tabular and image datasets validate the effectiveness of our SimSHAP, which significantly accelerates the computation of accurate Shapley values.
citation: 'Zhang, B., Tian, B., Zheng, W., Zhou, J., & Lu, J. (2023). Exploring Unified Perspective For Fast Shapley Value Estimation. arXiv preprint arXiv:2311.01010.'
authors: Borui Zhang$^*$, **Baotong Tian$^*$**, Wenzhao Zheng, Jie Zhou, Jiwen Lu
---
