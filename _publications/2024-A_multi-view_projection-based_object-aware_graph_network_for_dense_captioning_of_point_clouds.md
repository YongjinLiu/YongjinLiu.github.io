---
title: "A multi-view projection based object-aware graph network for dense captioning of point clouds"
collection: publications
permalink: /publication/2024-A_multi-view_projection-based_object-aware_graph_network_for_dense_captioning_of_point_clouds
excerpt: ''
date: 2025-02-01
venue: 'Computers & Graphics'
tags:
  - Journal Publications
citation: 'Zijing Ma, Zhi Yang, Aihua Mao, Shuyi Wen, Ran Yi, Yongjin Liu, A multi-view projection-based object-aware graph network for dense captioning of point clouds, Computers & Graphics, Volume 126, 2025,104156,ISSN 0097-8493, https://doi.org/10.1016/j.cag.2024.104156.'
---

Abstract:  3D dense captioning has received increasing attention in the multimodal field of 3D vision and language. This task aims to generate a specific descriptive sentence for each object in the 3D scene, which helps build a semantic understanding of the scene. However, due to inevitable holes in point clouds, there are often incorrect objects in the generated descriptions. Moreover, most existing models use KNN to construct relation graphs, which are not robust and have poor adaptability to different scenes. They cannot represent the relationship between the surrounding objects well. To address these challenges, in this paper, we propose a novel multi-level mixed encoding model for accurate 3D dense captioning of objects in point clouds. To handle holes in point clouds, we extract multi-view projection image features of objects based on our key observation that a hole in an object seldom exists in all projection images from different view angles. Then, the image features are fused with object detection features as the input of subsequent modules. Moreover, we combine KNN and DBSCAN clustering algorithms to construct a graph G and fuse their output features subsequently, which ensures the robustness of the graph structure for accurately describing the relationships between objects. Specifically, DBSCAN clusters are formed based on density, which alleviates the problem of using a fixed K value in KNN. Extensive experiments conducted on ScanRefer and Nr3D datasets demonstrate the effectiveness of our proposed model.



[Download paper here](http://yongjinliu.github.io/files/2024-A_multi-view_projection-based_object-aware_graph_network_for_dense_captioning_of_point_clouds.pdf)


[More information](https://cg.cs.tsinghua.edu.cn/people/~Yongjin/Yongjin.htm)

Recommended citation:Zijing Ma, Zhi Yang, Aihua Mao, Shuyi Wen, Ran Yi, Yongjin Liu, A multi-view projection-based object-aware graph network for dense captioning of point clouds, Computers & Graphics, Volume 126, 2025,104156,ISSN 0097-8493, https://doi.org/10.1016/j.cag.2024.104156.





