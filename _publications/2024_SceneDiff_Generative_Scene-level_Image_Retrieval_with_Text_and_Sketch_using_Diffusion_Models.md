---
title: "SceneDiff Generative Scene-level Image Retrieval with Text and Sketch using Diffusion Models"
collection: publications
permalink: /publication/2024_SceneDiff_Generative_Scene-level_Image_Retrieval_with_Text_and_Sketch_using_Diffusion_Models
excerpt: ''
date: 2024-08-03
venue: 'IJCAI'
tags:
  - Conference Publications
citation: 'Ran Zuo, Haoxiang Hu, Xiaoming Deng, Cangjun Gao, Zhengming Zhang, Yu-Kun Lai, Cuixia Ma*, Yong-Jin Liu*, Hongan Wang. SceneDiff: Generative Scene-level Image Retrieval with Text and Sketch using Diffusion Models. IJCAI, 2024.'
---

Abstract: Jointly using text and sketch for scene-level image retrieval utilizes the complementary between text and sketch to describe the fine-grained scene content and retrieve the target image, which plays a pivotal role in accurate image retrieval. Existing methods directly fuse the features of sketch and text and thus suffer from the bottleneck of limited utilization for crucial semantic and structural information, leading to inaccurate matching with images. In this paper, we propose SceneDiff, a novel retrieval network that leverages a pre-trained diffusion model to establish a shared generative latent space, enabling a joint latent representation learning for both sketch and text features and precise alignment with the corresponding image. Specifically, we encode text, sketch and image features, and project them into the diffusion-based share space, conditioning the denoising process on sketch and text features to generate latent fusion features, while employing the pre-trained autoencoder for latent image features. Within this space, we introduce the content-aware feature transformation module to reconcile encoded sketch and image features with the diffusion latent space's dimensional requirements and preserve their visual content information. Then we augment the representation capability of the generated latent fusion features by integrating multiple samplings with partition attention, and utilize contrastive learning to align both direct fusion features and generated latent fusion features with corresponding image representations. Our method outperforms the state-of-the-art works through extensive experiments, providing a novel insight into the related retrieval field.



[Download paper here](http://yongjinliu.github.io/files/2024_SceneDiff_Generative_Scene-level_Image_Retrieval_with_Text_and_Sketch_using_Diffusion_Models.pdf)


Recommended citation: Ran Zuo, Haoxiang Hu, Xiaoming Deng, Cangjun Gao, Zhengming Zhang, Yu-Kun Lai, Cuixia Ma*, Yong-Jin Liu*, Hongan Wang. SceneDiff: Generative Scene-level Image Retrieval with Text and Sketch using Diffusion Models. IJCAI, 2024.
