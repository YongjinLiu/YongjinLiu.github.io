---
title: "PCKRF Point Cloud Completion and Keypoint Refinement With Fusion Data for 6D Pose Estimation"
collection: publications
permalink: /publication/2024_PCKRF_Point_Cloud_Completion_and_Keypoint_Refinement_With_Fusion_Data_for_6D_Pose_Estimation
excerpt: ''
date: 2024-04-17
venue: ' IEEE Transactions on Visualization and Computer Graphics '
tags:
  - Journal Publications
citation: 'Yiheng Han,Irvin Haozhe Zhan,Long Zeng,Yu-Ping Wang,Ran Yi,Minjing Yu,Matthieu Gaetan Lin,Jenny Sheng Yong-Jin Liu*.PCKRF:Point Cloud Completion and Keypoint Refinement With Fusion Data for 6D Pose Estimation. IEEE Transactions on Visualization and Computer Graphics,ISSN 1077-2626.'
---

Abstract: Some robust point cloud registration approaches with controllable pose refinement magnitude, such as ICP and its variants, are commonly used to improve 6D pose estimation accuracy. However, the effectiveness of these methods gradually diminishes with the advancement of deep learning techniques and the enhancement of initial pose accuracy, primarily due to their lack of specific design for pose refinement. In this paper, we propose Point Cloud Completion and Keypoint Refinement with Fusion Data (PCKRF), a new pose refinement pipeline for 6D pose estimation. The pipeline consists of two steps. First, it completes the input point clouds via a novel pose-sensitive point completion network. The network uses both local and global features with pose information during point completion. Then, it registers the completed object point cloud with the corresponding target point cloud by our proposed Color supported Iterative KeyPoint (CIKP) method. The CIKP method introduces color information into registration and registers a point cloud around each keypoint to increase stability. The PCKRF pipeline can be integrated with existing popular 6D pose estimation methods, such as the full flow bidirectional fusion network, to further improve their pose estimation accuracy. Experiments demonstrate that our method exhibits superior stability compared to existing approaches when optimizing initial poses with relatively high precision. Notably, the results indicate that our method effectively complements most existing pose estimation techniques, leading to improved performance in most cases. Furthermore, our method achieves promising results even in challenging scenarios involving textureless and symmetrical objects. Our source code is available at https://github.com/zhanhz/KRF .



[Download paper here](http://yongjinliu.github.io/files/2024_PCKRF_Point_Cloud_Completion_and_Keypoint_Refinement_With_Fusion_Data_for_6D_Pose_Estimation.pdf)

[More information]
Recommended citation: Yiheng Han,Irvin Haozhe Zhan,Long Zeng,Yu-Ping Wang,Ran Yi,Minjing Yu,Matthieu Gaetan Lin,Jenny Sheng Yong-Jin Liu*.PCKRF:Point Cloud Completion and Keypoint Refinement With Fusion Data for 6D Pose Estimation. IEEE Transactions on Visualization and Computer Graphics,ISSN 1077-2626.



