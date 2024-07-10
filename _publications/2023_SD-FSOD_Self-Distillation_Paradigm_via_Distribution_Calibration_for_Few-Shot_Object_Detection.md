---
title: "SD-FSOD Self-Distillation Paradigm via Distribution Calibration for Few-Shot Object Detection"
collection: publications
permalink: /publication/2023_SD-FSOD_Self-Distillation_Paradigm_via_Distribution_Calibration_for_Few-Shot_Object_Detection
excerpt: ''
date: 2023-12-15
venue: ' IEEE Transactions on Circuits and Systems for Video Technology '
tags:
  - Journal Publications
citation: 'Han Chen, Qi Wang, Kailin Xie, Liang Lei, Matthieu Gaetan Lin, Tian lv, Yong-Jin Liu*, Jiebo Luo.SD-FSOD: Self-Distillation Paradigm via Distribution Calibration for Few-Shot Object Detection. IEEE Transactions on Circuits and Systems for Video Technology,Volume: 34, Issue: 7, On Page(s): 5963-5976,Print ISSN: 1051-8215,doi: 10.1109/TCSVT.2023.3343397.'
---

Abstract: Few-shot object detection (FSOD) aims to detect novel targets with only a few instances of the associated samples. Although combinations of distillation techniques and meta-learning paradigms have been acknowledged as the primary strategies for FSOD tasks, the existing distillation methods exhibit inherent biases and sensitivity to novel class variability. A critical hurdle for FSOD distillation is the difficulty in ensuring appropriate knowledge learned from the teacher model during the fine-tuning stage. Furthermore, coarse distillation procedures risk misalignment between the learned and actual distributions. This misalignment could potentially negate the benefits of positive cases and impede the detector’s evolution. To address these deficiencies, we propose a novel self-distillation paradigm exclusively for the fine-tuning stage (SD-FSOD). Our methods integrate a Distribution Prototype Extractor (DPE) and Self-Distillation Memory (SDM), promoting feature distribution consistency during distillation. In detail, the DPE module reliably initializes the weights of the detector, ensuring a robust class distribution for the distillation process. Meanwhile, the SDM module utilizes decoupling techniques to divide the distillation tasks into two sub-task branches, allowing the student model to independently learn and share precise features through isolated distillation processes. The synergistic integration of feature calibration techniques and the continuous self-distillation paradigm distinctly enhances the fine-tuning process, which shows the superiority of the FSOD self-distillation methodologies. The extensive experiments on the PASCAL VOC and MS COCO datasets demonstrate that our proposed approach produces significant improvements and achieves state-of-the-art (SOTA) performance.



[Download paper here](http://yongjinliu.github.io/files/2023_SD-FSOD_Self-Distillation_Paradigm_via_Distribution_Calibration_for_Few-Shot_Object_Detection.pdf)

[More information]
Recommended citation: Han Chen, Qi Wang, Kailin Xie, Liang Lei, Matthieu Gaetan Lin, Tian lv, Yong-Jin Liu*, Jiebo Luo.SD-FSOD: Self-Distillation Paradigm via Distribution Calibration for Few-Shot Object Detection. IEEE Transactions on Circuits and Systems for Video Technology,Volume: 34, Issue: 7, On Page(s): 5963-5976,Print ISSN: 1051-8215,doi: 10.1109/TCSVT.2023.3343397.



