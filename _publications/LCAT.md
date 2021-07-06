---
title: "Long-term Cross Adversarial Training: A Robust Meta-learning Method for Few-shot Classification Tasks"
collection: publications
permalink: /publication/LCAT
excerpt: 'A Robust Meta-learning Method for Few-shot Classification Tasks'
date: 2021-06-22
venue: 'ICML 2021 Workshop on Adversarial Machine Learning'
paperurl: 'https://arxiv.org/pdf/2106.12900.pdf'
citation: 'Liu, F., **Zhao, S.**, Dai, X., & Xiao, B. (2021). Long-term Cross Adversarial Training: A Robust Meta-learning Method for Few-shot Classification Tasks. arXiv preprint arXiv:2106.12900.'
---
Meta-learning model can quickly adapt to new tasks using few-shot labeled data. However, despite achieving good generalization on few-shot classification tasks,  it is still challenging to improve the adversarial robustness of the meta-learning model in few-shot learning. Although adversarial training (AT) methods such as Adversarial Query (AQ) can improve the adversarially robust performance of meta-learning models, AT is still computationally expensive training. On the other hand,  meta-learning models trained with AT will drop significant accuracy on the original clean images.  This paper proposed a meta-learning method on the adversarially robust neural network called Long-term Cross Adversarial Training (LCAT). LCAT will update meta-learning model parameters cross along the natural and adversarial sample distribution direction with long-term to improve both adversarial and clean few-shot classification accuracy. Due to cross-adversarial training,  LCAT only needs half of the adversarial training epoch than AQ, resulting in a low adversarial training computation. Experiment results show that LCAT achieves superior performance both on the clean and adversarial few-shot classification accuracy than SOTA adversarial training methods for meta-learning models.

[Download paper here](https://arxiv.org/pdf/2106.12900.pdf)

Recommended citation: Liu, F., **Zhao, S.**, Dai, X., & Xiao, B. (2021). Long-term Cross Adversarial Training: A Robust Meta-learning Method for Few-shot Classification Tasks. arXiv preprint arXiv:2106.12900.
