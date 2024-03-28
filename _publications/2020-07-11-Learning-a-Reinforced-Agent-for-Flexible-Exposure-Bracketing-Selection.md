---
title: "Learning a Reinforced Agent for Flexible Exposure Bracketing Selection"
collection: publications
permalink: /publication/2020-06-16-Learning-a-Reinforced-Agent-for-Flexible-Exposure-Bracketing-Selection
excerpt: 'Reinforcement Learning for HDR'
date: 2020-06-16
venue: 'CVPR2020'
paperurl: 'https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_Learning_a_Reinforced_Agent_for_Flexible_Exposure_Bracketing_Selection_CVPR_2020_paper.pdf'
citation: ' '
---

Automatically selecting exposure bracketing (images exposed differently) is important to obtain a high dynamic range image by using multi-exposure fusion. Unlike previous methods that have many restrictions such as requiring camera response function, sensor noise model, and a stream of preview images with different exposures (not accessible in some scenarios e.g. mobile applications), we propose a novel deep neural network to automatically select exposure bracketing, named EBSNet, which is sufficiently flexible without having the above restrictions. EBSNet is formulated as a reinforced agent that is trained by maximizing rewards provided by a multi-exposure fusion network (MEFNet). By utilizing the illumination and semantic information extracted from just a single auto-exposure preview image, EBSNet enables to select an optimal exposure bracketing for multi-exposure fusion. EBSNet and MEFNet can be jointly trained to produce favorable results against recent state-of-the-art approaches. To facilitate future research, we provide a new benchmark dataset for multi-exposure selection and fusion.

[Download paper here](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wang_Learning_a_Reinforced_Agent_for_Flexible_Exposure_Bracketing_Selection_CVPR_2020_paper.pdf)

Recommended citation:  

```
@InProceedings{Wang_2020_CVPR,
author = {Wang, Zhouxia and Zhang, Jiawei and Lin, Mude and Wang, Jiong and Luo, Ping and Ren, Jimmy},
title = {Learning a Reinforced Agent for Flexible Exposure Bracketing Selection},
booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2020}
}
```