---
title: "A Diffusion Model Translator for Efficient Image-to-Image Translation"
collection: publications
permalink: /publication/2024-A_Diffusion_Model_Translator_for_Efficient_Image-to-Image_Translation
excerpt: ''
date: 2024-06-30
venue: ' IEEE Transactions on Pattern Analysis and Machine Intelligence'
tags:
  - Journal Publications
citation: ' M. Xia, Y. Zhou, R. Yi, Y. -J. Liu and W. Wang, "A Diffusion Model Translator for Efficient Image-to-Image Translation," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 46, no. 12, pp. 10272-10283, Dec. 2024, doi: 10.1109/TPAMI.2024.3435448.'
---

Abstract: Applying diffusion models to image-to-image translation (I2I) has recently received increasing attention due to its practical applications. Previous attempts inject information from the source image into each denoising step for an iterative refinement, thus resulting in a time-consuming implementation. We propose an efficient method that equips a diffusion model with a lightweight translator, dubbed a Diffusion Model Translator (DMT), to accomplish I2I. Specifically, we first offer theoretical justification that in employing the pioneering DDPM work for the I2I task, it is both feasible and sufficient to transfer the distribution from one domain to another only at some intermediate step. We further observe that the translation performance highly depends on the chosen timestep for domain transfer, and therefore propose a practical strategy to automatically select an appropriate timestep for a given task. We evaluate our approach on a range of I2I applications, including image stylization, image colorization, segmentation to image, and sketch to image, to validate its efficacy and general utility. The comparisons show that our DMT surpasses existing methods in both quality and efficiency. Code is available at https://github.com/THU-LYJ-Lab/dmt .



[Download paper here](http://yongjinliu.github.io/files/2024-A_Diffusion_Model_Translator_for_Efficient_Image-to-Image_Translation.pdf)


[More information](https://cg.cs.tsinghua.edu.cn/people/~Yongjin/Yongjin.htm)

Recommended citation:M. Xia, Y. Zhou, R. Yi, Y. -J. Liu and W. Wang, "A Diffusion Model Translator for Efficient Image-to-Image Translation," in IEEE Transactions on Pattern Analysis and Machine Intelligence, vol. 46, no. 12, pp. 10272-10283, Dec. 2024, doi: 10.1109/TPAMI.2024.3435448.





