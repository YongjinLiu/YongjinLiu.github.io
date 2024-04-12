---
title: "SparseDGCNN Recognizing Emotion from Multichannel EEG Signals"
collection: publications
permalink: /publication/2023-SparseDGCNN-Recognizing-Emotion-from-Multichannel-EEG-Signals
excerpt: ''
date: 2021-01-13
venue: ''
tags:
  - Journal Publications
citation: 'Guanhua Zhang, Minjing Yu, Yong-Jin Liu*, Guozhen Zhao, Dan Zhang, Wenming Zheng. SparseDGCNN: Recognizing Emotion from Multichannel EEG Signals. IEEE Trans. Affect. Comput. 14(1): 537-548 (2023).'
---

Abstract: Emotion recognition from EEG signals has attracted much attention in affective computing. Recently, a novel dynamic graph convolutional neural network (DGCNN) model was proposed, which simultaneously optimized the network parameters and a weighted graph G characterizing the strength of functional relation between each pair of two electrodes in the EEG recording equipment. In this article, we propose a sparse DGCNN model which modifies DGCNN by imposing a sparseness constraint on G and improves the emotion recognition performance. Our work is based on an important observation: the tomography study reveals that different brain regions sampled by EEG electrodes may be related to different functions of the brain and then the functional relations among electrodes are possibly highly localized and sparse. However, introducing sparseness constraint into the graph G makes the loss function of sparse DGCNN non-differentiable at some singular points. To ensure that the training process of sparse DGCNN converges, we apply the forward-backward splitting method. To evaluate the performance of sparse DGCNN, we compare it with four representative recognition methods (SVM, DBN, GELM and DGCNN). In addition to comparing different recognition methods, our experiments also compare different features and spectral bands, including EEG features in time-frequency domain (DE, PSD, DASM,RASM, ASM and DCAU on different bands) extracted from four representative EEG datasets (SEED, DEAP, DREAMER, and CMEED). The results show that (1) sparse DGCNN has consistently better accuracy than representative methods and has a good scalability, and(2) DE, PSD, and ASM features on g band convey most discriminative emotional information, and fusion of separate features andfrequency bands can improve recognition performance.



[Download paper here](http://yongjinliu.github.io/files/2023-SparseDGCNN-Recognizing-Emotion-from-Multichannel-EEG-Signals.pdf)


[More information](https://cg.cs.tsinghua.edu.cn/people/~Yongjin/Yongjin.htm)

Recommended citation: Guanhua Zhang, Minjing Yu, Yong-Jin Liu*, Guozhen Zhao, Dan Zhang, Wenming Zheng. SparseDGCNN: Recognizing Emotion from Multichannel EEG Signals. IEEE Trans. Affect. Comput. 14(1): 537-548 (2023).





