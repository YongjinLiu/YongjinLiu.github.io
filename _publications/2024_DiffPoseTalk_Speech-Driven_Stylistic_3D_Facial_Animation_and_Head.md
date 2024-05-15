---
title: "DiffPoseTalk Speech-Driven Stylistic 3D Facial Animation and Head"
collection: publications
permalink: /publication/2024_DiffPoseTalk_Speech-Driven_Stylistic_3D_Facial_Animation_and_Head
excerpt: ''
date: 2024-07-01
venue: 'SIGGRAPH'
tags:
  - Conference Publications
citation: 'Zhiyao Sun, Tian Lv, Sheng Ye, Matthieu Gaetan Lin, Jenny Sheng, Yu-Hui Wen, Minjing Yu, Yong-Jin Liu*.DiffPoseTalk: Speech-Driven Stylistic 3D Facial Animation and Head Pose Generation via Diffusion Models. SIGGRAPH 2023.'
---

Abstract: The generation of stylistic 3D facial animations driven by speech presents a significant challenge as it requires learning a many-to-many mapping between speech, style, and the corresponding natural facial motion. However, existing methods either employ a deterministic model for speech-to-motion mapping or encode the style using a one-hot encoding scheme. Notably, the one-hot encoding approach fails to capture the complexity of the style and thus limits generalization ability. In this paper, we propose DiffPoseTalk, a generative framework based on the diffusion model combined with a style encoder that extracts style embeddings from short reference videos. During inference, we employ classifier-free guidance to guide the generation process based on the speech and style. In particular, our style includes the generation of head poses, thereby enhancing user perception. Additionally, we address the shortage of scanned 3D talking face data by training our model on reconstructed 3DMM parameters from a high-quality, in-the-wild audio-visual dataset. Extensive experiments and user study demonstrate that our approach outperforms state-of-the-art methods. The code and dataset are at https://diffposetalk.github.io.



[Download paper here](http://yongjinliu.github.io/files/2024_DiffPoseTalk_Speech-Driven_Stylistic_3D_Facial_Animation_and_Head.pdf)

[Download source code here](https://diffposetalk.github.io/ )

[Download appendix here](http://yongjinliu.github.io/files/2024_DiffPoseTalk_Speech-Driven_Stylistic_3D_Facial_Animation_and_Head_appendix.pdf)

Recommended citation: Zhiyao Sun, Tian Lv, Sheng Ye, Matthieu Gaetan Lin, Jenny Sheng, Yu-Hui Wen, Minjing Yu, Yong-Jin Liu*.DiffPoseTalk: Speech-Driven Stylistic 3D Facial Animation and Head Pose Generation via Diffusion Models. SIGGRAPH 2023.

