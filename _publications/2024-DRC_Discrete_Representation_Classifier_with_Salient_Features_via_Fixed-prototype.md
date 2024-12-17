---
title: "DRC: Discrete Representation Classifier with Salient Features via Fixed-prototype"
collection: publications
permalink: /publication/2024-DRC_Discrete_Representation_Classifier_with_Salient_Features_via_Fixed-prototype
excerpt: ''
date: 2024-09-02
venue: ' IEEE Transactions on Circuits and Systems for Video Technology'
tags:
  - Journal Publications
citation: ' Qinglei Li, Qi Wang, Yongbin Qin, Xinyu Dong, Xingcai Wu, Shiming Chen, Wu Liu, Yong-Jin Liu*, Jiebo Luo, "DRC: Discrete Representation Classifier with Salient Features via Fixed-prototype," in IEEE Transactions on Circuits and Systems for Video Technology, doi: 10.1109/TCSVT.2024.3453052.'
---

Abstract: Image classification models including convolutional neural networks (CNN) and vision transformers (ViT) commonly employ a fully connected (FC) layer as the classifier. However, the fully connected nature of FC brings large amounts of weight parameters, limits the efficiency of inference, tends to over-fit the training data, and struggles to learn distinct class weights. To solve these problems, we propose a discrete representation classifier (DRC), a generic parameter-free classifier that offers efficiency, robustness, and more discriminative categorization. Specifically, the DRC discards numerous unimportant features and focuses solely on the salient features which are reinforced during training and presented in short discrete form during inference. Unlike the way of learning pseudo-prototypes (weights) from data laden with complex patterns and noises in FC, the DRC introducing discriminative fixed-prototypes which are almost uniformly distributed across the high-dimensional feature space, thus helps the model to learn more distinct boundaries between categories. Further leveraging the advantage of DRC’s focus on salient features, we propose Salient-CAM, which is able to locate the most important region in image without the need for weighting feature maps. The experiments demonstrate that simply replacing the model’s classifier from FC to DRC can lead to a significant acceleration in the whole model’s inference and a more robust classification. Additionally, the proposed Salient-CAM exhibits excellent object localization ability in complex natural scenes.



[Download paper here](http://yongjinliu.github.io/files/2024-DRC_Discrete_Representation_Classifier_with_Salient_Features_via_Fixed-prototype.pdf)


[More information](https://cg.cs.tsinghua.edu.cn/people/~Yongjin/Yongjin.htm)

Recommended citation: Qinglei Li, Qi Wang, Yongbin Qin, Xinyu Dong, Xingcai Wu, Shiming Chen, Wu Liu, Yong-Jin Liu*, Jiebo Luo, "DRC: Discrete Representation Classifier with Salient Features via Fixed-prototype," in IEEE Transactions on Circuits and Systems for Video Technology, doi: 10.1109/TCSVT.2024.3453052.





