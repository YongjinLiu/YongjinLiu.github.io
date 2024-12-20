---
title: "MMPI a Flexible Radiance Field Representation by Multiple Multi-plane Images Blending"
collection: publications
permalink: /publication/2024_MMPI_a_Flexible_Radiance_Field_Representation_by_Multiple_Multi-plane_Images_Blending
excerpt: ''
date: 2024-05-13
venue: 'ICRA'
tags:
  - Conference Publications
citation: 'Yuze He, Peng Wang, Yubin Hu, Wang Zhao, Ran Yi,Yong-Jin Liu*and Wenping Wang. MMPI: a Flexible Radiance Field Representation by Multiple Multi-plane Images Blending. ICRA 2024.'
---

Abstract: This paper presents a flexible representation of neural radiance fields based on multi-plane images (MPI), for high-quality view synthesis of complex scenes. MPI with Normalized Device Coordinate (NDC) parameterization is widely used in NeRF learning for its simple definition, easy calculation, and powerful ability to represent unbounded scenes. However, existing NeRF works that adopt MPI representation for novel view synthesis can only handle simple forward-facing unbounded scenes (e.g., the scenes in the LLFF dataset), where the input cameras are all observing in similar directions with small relative translations. Hence, extending these MPIbased methods to more complex scenes like large-range or even 360-degree scenes is very challenging. In this paper, we explore the potential of MPI and show that MPI can synthesize high-quality novel views of complex scenes with diverse camera distributions and view directions, which are not only limited to simple forward-facing scenes. Our key idea is to encode the neural radiance field with multiple MPIs facing different directions and blend them with an adaptive blending operation. For each region of the scene, the blending operation gives larger blending weights to those advantaged MPIs with stronger local representation abilities while giving lower weights to those with weaker representation abilities. Such blending operation automatically modulates the multiple MPIs to appropriately represent the diverse local density and color information. Experiments on the KITTI dataset and ScanNet dataset demonstrate that our proposed MMPI synthesizes high-quality images from diverse camera pose distributions and is fast to train, outperforming the previous fast-training NeRF methods for novel view synthesis. Moreover, we show that MMPI can encode extremely long trajectories and produce novel view renderings, demonstrating its potential in applications like autonomous driving. Our demo video is available at https://youtube.com/watch?v=mbNKwN5urC8.



[Download paper here](http://yongjinliu.github.io/files/2024_MMPI_a_Flexible_Radiance_Field_Representation_by_Multiple_Multi-plane_Images_Blending.pdf)



Recommended citation: Yuze He, Peng Wang, Yubin Hu, Wang Zhao, Ran Yi,Yong-Jin Liu*and Wenping Wang. MMPI: a Flexible Radiance Field Representation by Multiple Multi-plane Images Blending. ICRA 2024.

