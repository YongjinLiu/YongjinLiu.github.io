---
title: "O^2-Recon Completing 3D Reconstruction of Occluded Objects in the Scene with a Pre-trained 2D Diffusion Model"
collection: publications
permalink: /publication/2023-O^2-Recon_Completing_3D_Reconstruction_of_Occluded_Objects_in_the_Scene_with_a_Pre-trained_2D_Diffusion_Model
excerpt: ''
date: 2023-08-18
venue: 'AAAI 2023'
tags:
  - Conference Publications
citation: 'Yubin Hu, Sheng Ye, Wang Zhao, Matthieu Lin, Yuze He, Yu-Hui Wen, Ying He, Yong-Jin Liu*.O^2-Recon: Completing 3D Reconstruction of Occluded Objects in the Scene with a Pre-trained 2D Diffusion Model.AAAI 2024.'
---

Abstract: Occlusion is a common issue in 3D reconstruction from RGB-D videos, often blocking the complete reconstruction of objects and presenting an ongoing problem. In this paper, we propose a novel framework, empowered by a 2D diffusion-based in-painting model, to reconstruct complete surfaces for the hidden parts of objects. Specifically, we utilize a pre-trained diffusion model to fill in the hidden areas of 2D images. Then we use these in-painted images to optimize a neural implicit surface representation for each instance for 3D reconstruction. Since creating the in-painting masks needed for this process is tricky, we adopt a human-in-the-loop strategy that involves very little human engagement to generate high-quality masks. Moreover, some parts of objects can be totally hidden because the videos are usually shot from limited perspectives. To ensure recovering these invisible areas, we develop a cascaded network architecture for predicting signed distance field, making use of different frequency bands of positional encoding and maintaining overall smoothness. Besides the commonly used rendering loss, Eikonal loss, and silhouette loss, we adopt a CLIP-based semantic consistency loss to guide the surface from unseen camera angles. Experiments on ScanNet scenes show that our proposed framework achieves state-of-the-art accuracy and completeness in object-level reconstruction from scene-level RGB-D videos..



[Download paper here](http://yongjinliu.github.io/files/2023-O^2-Recon_Completing_3D_Reconstruction_of_Occluded_Objects_in_the_Scene_with_a_Pre-trained_2D_Diffusion_Model.pdf)


[More information](https://cg.cs.tsinghua.edu.cn/people/~Yongjin/Yongjin.htm)

Recommended citation: Yubin Hu, Sheng Ye, Wang Zhao, Matthieu Lin, Yuze He, Yu-Hui Wen, Ying He, Yong-Jin Liu*.O^2-Recon: Completing 3D Reconstruction of Occluded Objects in the Scene with a Pre-trained 2D Diffusion Model.AAAI 2024.





