---
title: "Poisson Vector Graphics PVG-Guided Face Color Transfer in Videos"
collection: publications
permalink: /publication/2021-Poisson_Vector_Graphics_PVG-Guided_Face_Color_Transfer_in_Videos
excerpt: ''
date: 2020-09-18
venue: 'IEEE Computer Graphics and Applications'
tags:
  - Journal Publications
citation: 'Qian Fu, Ying He, Fei Hou, Qian Sun, Anxiang Zeng, Zhenchuan Huang, Juyong Zhang, Yong-Jin Liu. Poisson Vector Graphics (PVG)-Guided Face Color Transfer in Videos. IEEE Computer Graphics and Applications, vol. 41, no. 6, pp. 152-163, 1 Nov.-Dec. 2021.'
---

Abstract: This article presents a simple yet effective algorithm for automatically transferring face colors in portrait videos. We extract the facial features and vectorize the faces in the input video using Poisson vector graphics, which encodes the low-frequency colors as the boundary colors of diffusion curves, and the high-frequency colors as Poisson regions. Then, we transfer the face color of a reference image/video to the first frame of the input video by applying optimal mass transport between the boundary colors of diffusion curves. Next the boundary color of the first frame is transferred to the subsequent frames by matching the curves. Finally, with the original or modified Poisson regions, we render the video using an efficient random-access Poisson solver. Thanks to our efficient diffusion curve matching algorithm, transferring colors for the vectorized video takes less than 1 millisecond per frame. Our method is particularly desired for frequent transfer from multiple references due to its information reuse nature. The simple diffusion curve matching also greatly improves the performance of video vectorization, since we only need to solve an optimization problem for the first frame. Since our method does not require correspondence between the reference image/video and the input video, it is flexible and robust to handle faces with significantly different geometries and postures, which often pose challenges to the existing methods. Moreover, by manipulating Poisson regions, we can enhance or reduce the highlight and contrast so that the reference color can fit into the input video naturally. We demonstrate the efficacy of our method on image-to-video transfer and color swap in videos.


[Download paper here](http://yongjinliu.github.io/files/2021-Poisson_Vector_Graphics_PVG-Guided_Face_Color_Transfer_in_Videos.pdf)


[More information]

Recommended citation: Qian Fu, Ying He, Fei Hou, Qian Sun, Anxiang Zeng, Zhenchuan Huang, Juyong Zhang, Yong-Jin Liu. Poisson Vector Graphics (PVG)-Guided Face Color Transfer in Videos. IEEE Computer Graphics and Applications, vol. 41, no. 6, pp. 152-163, 1 Nov.-Dec. 2021.





