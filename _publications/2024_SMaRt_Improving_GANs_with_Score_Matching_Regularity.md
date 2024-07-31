---
title: "SMaRt Improving GANs with Score Matching Regularity"
collection: publications
permalink: /publication/2024_SMaRt_Improving_GANs_with_Score_Matching_Regularity
excerpt: ''
date: 2024-07-27
venue: 'ICML'24'
tags:
  - Conference Publications
citation: 'Mengfei Xia, Yujun Shen, Ceyuan Yang, Ran Yi, Wenping Wang, Yong-Jin Liu. Proceedings of the 41st International Conference on Machine Learning, PMLR 235:54133-54155, 2024.'
---

Abstract: Generative adversarial networks (GANs) usually struggle in learning from highly diverse data, whose underlying manifold is complex. In this work, we revisit the mathematical foundations of GANs, and theoretically reveal that the native adversarial loss for GAN training is insufficient to fix the problem of subsets with positive Lebesgue measure of the generated data manifold lying out of the real data manifold. Instead, we find that score matching serves as a promising solution to this issue thanks to its capability of persistently pushing the generated data points towards the real data manifold. We thereby propose to improve the optimization of GANs with score matching regularity (SMaRt). Regarding the empirical evidences, we first design a toy example to show that training GANs by the aid of a ground-truth score function can help reproduce the real data distribution more accurately, and then confirm that our approach can consistently boost the synthesis performance of various state-of-the-art GANs on real-world datasets with pre-trained diffusion models acting as the approximate score function. For instance, when training Aurora on the ImageNet 64×64 dataset, we manage to improve FID from 8.87 to 7.11, on par with the performance of one-step consistency model. Code is available at https://github.com/thuxmf/SMaRt.



[Download paper here](http://yongjinliu.github.io/files/2024_SMaRt_Improving_GANs_with_Score_Matching_Regularity.pdf)


Recommended citation: Mengfei Xia, Yujun Shen, Ceyuan Yang, Ran Yi, Wenping Wang, Yong-Jin Liu. Proceedings of the 41st International Conference on Machine Learning, PMLR 235:54133-54155, 2024.

