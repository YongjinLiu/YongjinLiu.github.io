---
title: "Towards More Accurate Diffusion Model Acceleration with A Timestep Aligner"
collection: publications
permalink: /publication/2024-Towards_More_Accurate_Diffusion_Model_Acceleration_with_A_Timestep_Aligner
excerpt: ''
date: 2024-06-17
venue: 'CVPR 2024'
tags:
  - Conference Publications
citation: 'Mengfei Xia, Yujun Shen, Changsong Lei, Yu Zhou, Ran Yi, Deli Zhao, Wenping Wang, Yong-Jin Liu*. Towards More Accurate Diffusion Model Acceleration with A Timestep Aligner. CVPR 2024.'
---

Abstract: A diffusion model, which is formulated to produce an image using thousands of denoising steps, usually suffers from a slow inference speed. Existing acceleration algorithms simplify the sampling by skipping most steps yet exhibit considerable performance degradation. By viewing the generation of diffusion models as a discretized integral process, we argue that the quality drop is partly caused by applying an inaccurate integral direction to a timestep interval. To rectify this issue, we propose a timestep tuner that helps find a more accurate integral direction for a particular interval at the minimum cost. Specifically, at each denoising step, we replace the original parameterization by conditioning the network on a new timestep, enforcing the sampling distribution towards the real one. Extensive experiments show that our plug-in design can be trained efficiently and boost the inference performance of various state-of-the-art acceleration methods, especially when there are few denoising steps. For example, when using 10 denoising steps on LSUN Bedroom dataset, we improve the FID of DDIM from 9.65 to 6.07, simply by adopting our method for a more appropriate set of timesteps. Code is available at https://github.com/THU-LYJ-Lab/time-tuner.



[Download paper here](http://yongjinliu.github.io/files/2024-Towards_More_Accurate_Diffusion_Model_Acceleration_with_A_Timestep_Aligner.pdf)


[More information](https://cg.cs.tsinghua.edu.cn/people/~Yongjin/Yongjin.htm)

Recommended citation:Mengfei Xia, Yujun Shen, Changsong Lei, Yu Zhou, Ran Yi, Deli Zhao, Wenping Wang, Yong-Jin Liu*. Towards More Accurate Diffusion Model Acceleration with A Timestep Aligner. CVPR 2024.




