---
title: "Exploring Temporal Feature Correlation for Efficient and Stable Video Semantic Segmentation"
collection: publications
permalink: /publication/2024-Exploring_Temporal_Feature_Correlation_for_Efficient_and_Stable_Video_Semantic_Segmentation
excerpt: ''
date: 2024-02-19
venue: 'AAAI 2024'
tags:
  - Conference Publications
citation: 'Matthieu Lin, Jenny Sheng, Yubin Hu, Yangguang Li, Lu Qi, Andrew Zhao, Gao Huang, Yong-Jin Liu*.Exploring Temporal Feature Correlation for Efficient and Stable Video Semantic Segmentation.AAAI 2024.'
---

Abstract: This paper tackles the problem of efficient and stable video semantic segmentation. While stability has been under-explored, prevalent work in efficient video semantic segmentation uses the keyframe paradigm. They efficiently process videos by only recomputing the low-level features and reusing high-level features computed at selected keyframes. In addition, the reused features stabilize the predictions across frames, thereby improving video consistency. However, dynamic scenes in the video can easily lead to misalignments between reused and recomputed features, which hampers performance. Moreover, relying on feature reuse to improve prediction consistency is brittle; an erroneous alignment of the features can easily lead to unstable predictions. Therefore, the keyframe paradigm exhibits a dilemma between stability and performance. We address this efficiency and stability challenge using a novel yet simple Temporal Feature Correlation (TFC) module. It uses the cosine similarity between two frames' low-level features to inform the semantic label's consistency across frames. Specifically, we selectively reuse label-consistent features across frames through linear interpolation and update others through sparse multi-scale deformable attention. As a result, we no longer directly reuse features to improve stability and thus effectively solve feature misalignment. This work provides a significant step towards efficient and stable video semantic segmentation. On the VSPW dataset, our method significantly improves the prediction consistency of image-based methods while being as fast and accurate.



[Download paper here](http://yongjinliu.github.io/files/2024-Exploring_Temporal_Feature_Correlation_for_Efficient_and_Stable_Video_Semantic_Segmentation.pdf)


[More information](https://cg.cs.tsinghua.edu.cn/people/~Yongjin/Yongjin.htm)

Recommended citation:Matthieu Lin, Jenny Sheng, Yubin Hu, Yangguang Li, Lu Qi, Andrew Zhao, Gao Huang, Yong-Jin Liu*.Exploring Temporal Feature Correlation for Efficient and Stable Video Semantic Segmentation.AAAI 2024.





