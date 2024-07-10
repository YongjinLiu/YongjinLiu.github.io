---
title: "Automatic tooth arrangement with joint features of point and mesh representations via diffusion probabilistic models"
collection: publications
permalink: /publication/2024_Automatic_tooth_arrangement_with_joint_features_of_point_and_mesh_representations_via_diffusion_probabilistic_models
excerpt: ''
date: 2024-06-01
venue: ' Computer Aided Geometric Design '
tags:
  - Journal Publications
citation: 'Changsong Lei, Mengfei Xia, Shaofeng Wang, Yaqian Liang, Ran Yi, Yuhui Wen, Yong-Jin Liu*.Automatic Tooth Arrangement with Joint Features of Point and Mesh Representations via Diffusion Probabilistic Models. Computer Aided Geometric Design, Volume 111,2024,102293,ISSN 0167-8396, https://doi.org/10.1016/j.cagd.2024.102293.'
---

Abstract: Tooth arrangement is a crucial step in orthodontics treatment, in which aligning teeth could improve overall well-being, enhance facial aesthetics, and boost self-confidence. To improve the efficiency of tooth arrangement and minimize errors associated with unreasonable designs by inexperienced practitioners, some deep learning-based tooth arrangement methods have been proposed. Currently, most existing approaches employ MLPs to model the nonlinear relationship between tooth features and transformation matrices to achieve tooth arrangement automatically. However, the limited datasets (which to our knowledge, have not been made public) collected from clinical practice constrain the applicability of existing methods, making them inadequate for addressing diverse malocclusion issues. To address this challenge, we propose a general tooth arrangement neural network based on the diffusion probabilistic model. Conditioned on the features extracted from the dental model, the diffusion probabilistic model can learn the distribution of teeth transformation matrices from malocclusion to normal occlusion by gradually denoising from a random variable, thus more adeptly managing real orthodontic data. To take full advantage of effective features, we exploit both mesh and point cloud representations by designing different encoding networks to extract the tooth (local) and jaw (global) features, respectively. In addition to traditional metrics ADD, PA-ADD, CSA, and , we propose a new evaluation metric based on dental arch curves to judge whether the generated teeth meet the individual normal occlusion. Experimental results demonstrate that our proposed method achieves state-of-the-art tooth alignment results and satisfactory occlusal relationships between dental arches. We will publish the code and dataset.



[Download paper here](http://yongjinliu.github.io/files/2024_Automatic_tooth_arrangement_with_joint_features_of_point_and_mesh_representations_via_diffusion_probabilistic_models.pdf)

[More information]
Recommended citation: Changsong Lei, Mengfei Xia, Shaofeng Wang, Yaqian Liang, Ran Yi, Yuhui Wen, Yong-Jin Liu*.Automatic Tooth Arrangement with Joint Features of Point and Mesh Representations via Diffusion Probabilistic Models. Computer Aided Geometric Design, Volume 111,2024,102293,ISSN 0167-8396, https://doi.org/10.1016/j.cagd.2024.102293.




