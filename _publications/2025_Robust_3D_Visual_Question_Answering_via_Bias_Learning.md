---
title: "Robust 3D Visual Question Answering via Bias Learning"
collection: publications
permalink: /publication/ 2025_Robust_3D_Visual_Question_Answering_via_Bias_Learning
excerpt: ''
date: 2025-07-18
venue: ' IEEE Transactions on Circuits and Systems for Video Technology '
tags:
  - Journal Publications
citation: 'A. Mao, S. Wen, F. Chen, R. Yi and Y. -J. Liu, "Robust 3D Visual Question Answering via Bias Learning," in IEEE Transactions on Circuits and Systems for Video Technology, vol. 35, no. 12, pp. 12492-12507, Dec. 2025, doi: 10.1109/TCSVT.2025.3590456. '
---

Abstract: Visual question answering (VQA) tasks have witnessed significant advancements in recent years. So far, enhancing the robustness of models on diverse datasets and improving their performance in 3D environments remains a challenging research direction. In this paper, we propose a high-performance framework called Bias3D-VQA for 3D-VQA based on generative adversarial networks via bias learning, addressing the inherent biases that arise from the model's dependency on dataset-specific patterns or tendencies during training. Such biases often lead the model to focus on more frequently occurring but incorrect answers. Our framework comprises a target model, a bias model, and a generative adversarial component. In each training iteration, we employ an alternating training approach for the target and bias models. When training the bias model, fake point cloud data is generated from random noise, and then we accumulate biases present in language modality and various modules through adversarial training. When training the target model, both the question and the 3D point cloud are inputted into the bias model simultaneously, and the output of the bias model is utilized to correct the loss of the target model. Our approach(Bias3D-VQA) is the first to focus on enhancing model robustness by addressing diverse biases in the 3D-VQA domain. Our target model demonstrates superior performance compared to state-of-the-art models, showing significant improvements in classification accuracy and text generation quality. Notably, in the metrics such as EM@1 and CIDEr, our model even surpasses some pre-trained models with large additional datasets. The source code is available at https://github.com/coderr727/bias_3DQA.






[Download paper here](http://yongjinliu.github.io/files/ 2025_Robust_3D_Visual_Question_Answering_via_Bias_Learning.pdf)


[More information](https://cg.cs.tsinghua.edu.cn/people/~Yongjin/Yongjin.htm)

Recommended citation: A. Mao, S. Wen, F. Chen, R. Yi and Y. -J. Liu, "Robust 3D Visual Question Answering via Bias Learning," in IEEE Transactions on Circuits and Systems for Video Technology, vol. 35, no. 12, pp. 12492-12507, Dec. 2025, doi: 10.1109/TCSVT.2025.3590456.



