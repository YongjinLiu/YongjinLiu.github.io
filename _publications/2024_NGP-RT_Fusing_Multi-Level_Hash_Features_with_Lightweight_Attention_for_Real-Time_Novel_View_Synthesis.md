---
title: "NGP-RT: Fusing Multi-Level Hash Features with Lightweight Attention for Real-Time Novel View Synthesis"
collection: publications
permalink: /publication/2024_NGP-RT_Fusing_Multi-Level_Hash_Features_with_Lightweight_Attention_for_Real-Time_Novel_View_Synthesis
date: 2024-09-29
venue: 'ECCV 2024'
tags:
  - Conference Publications
citation: 'Yubin Hu*, Xiaoyang Guo, Yang Xiao, Jingwei Huang, Yong-Jin Liu*. NGP-RT: Fusing Multi-Level Hash Features with Lightweight Attention for Real-Time Novel View Synthesis. ECCV 2024.'
---

Abstract: This paper presents NGP-RT, a novel approach for enhancing the rendering speed of Instant-NGP to achieve real-time novel view synthesis. As a classic NeRF-based method, Instant-NGP stores implicit features in multi-level grids or hash tables and applies a shallow MLP to convert the implicit features into explicit colors and densities. Although it achieves fast training speed, there is still a lot of room for improvement in its rendering speed due to the per-point MLP executions for implicit multi-level feature aggregation, especially for real-time applications. To address this challenge, our proposed NGP-RT explicitly stores colors and densities as hash features, and leverages a lightweight attention mechanism to disambiguate the hash collisions instead of using computationally intensive MLP. At the rendering stage, NGP-RT incorporates a pre-computed occupancy distance grid into the ray marching strategy to inform the distance to the nearest occupied voxel, thereby reducing the number of marching points and global memory access. Experimental results show that on the challenging Mip-NeRF 360 dataset, NGP-RT achieves better rendering quality than previous NeRF-based methods, achieving 108 fps at 1080p resolution on a single Nvidia RTX 3090 GPU. Our approach is promising for NeRF-based real-time applications that require efficient and high-quality rendering.



[Download paper here](http://yongjinliu.github.io/files/2024_NGP-RT_Fusing_Multi-Level_Hash_Features_with_Lightweight_Attention_for_Real-Time_Novel_View_Synthesis.pdf)


[More information](https://cg.cs.tsinghua.edu.cn/people/~Yongjin/Yongjin.htm)

Recommended citation:Yubin Hu*, Xiaoyang Guo, Yang Xiao, Jingwei Huang, Yong-Jin Liu*. NGP-RT: Fusing Multi-Level Hash Features with Lightweight Attention for Real-Time Novel View Synthesis. ECCV 2024.




