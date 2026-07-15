---
title: "Rectified Diffusion Guidance for Conditional Generation"
collection: publications
permalink: /publication/2025_Rectified_Diffusion_Guidance_for_Conditional_Generation
excerpt: ''
date: 2025-06-10
venue: '  CVPR 2025 '
tags:
  - Conference Publications
citation: 'M. Xia, N. Xue, Y. Shen, R. Yi, T. Gong and Y. -J. Liu, "Rectified Diffusion Guidance for Conditional Generation," 2025 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), Nashville, TN, USA, 2025, pp. 13371-13380, doi: 10.1109/CVPR52734.2025.01248.'
---

Abstract: Classifier-Free Guidance (CFG), which combines the conditional and unconditional score functions with two coefficients summing to one, serves as a practical technique for diffusion model sampling. Theoretically, however, denoising with CFG cannot be expressed as a reciprocal diffusion process, which may consequently leave some hidden risks during use. In this work, we revisit the theory behind CFG and rigorously confirm that the improper configuration of the combination coefficients (i.e., the widely used summing-to-one version) brings about expectation shift of the generative distribution. To rectify this issue, we propose ReCFG1 with a relaxation on the guidance coefficients such that denoising with ReCFG strictly aligns with the diffusion theory. We further show that our approach enjoys a closed-form solution given the guidance strength. That way, the rectified coefficients can be readily pre-computed via traversing the observed data, leaving the sampling speed barely affected. Empirical evidence on real-world data demonstrate the compatibility of our post-hoc design with existing state-of-the-art diffusion models, including both class-conditioned ones (e.g., EDM2 on ImageNet) and text-conditioned ones (e.g., SD3 on CC12M), without any retraining. Code is available at https://github.com/thuxmf/recfg.


[Download paper here](http://yongjinliu.github.io/files/2025_Rectified_Diffusion_Guidance_for_Conditional_Generation.pdf)


[More information](https://cg.cs.tsinghua.edu.cn/people/~Yongjin/Yongjin.htm)

Recommended citation: M. Xia, N. Xue, Y. Shen, R. Yi, T. Gong and Y. -J. Liu, "Rectified Diffusion Guidance for Conditional Generation," 2025 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), Nashville, TN, USA, 2025, pp. 13371-13380, doi: 10.1109/CVPR52734.2025.01248.


