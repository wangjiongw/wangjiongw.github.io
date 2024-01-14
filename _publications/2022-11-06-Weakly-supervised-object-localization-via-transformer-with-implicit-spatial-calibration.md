---
title: "Weakly supervised object localization via transformer with implicit spatial calibration"
collection: publications
permalink: /publication/2022-11-06-Weakly-supervised-object-localization-via-transformer-with-implicit-spatial-calibration
excerpt: 'Taming Transformer for WSOL'
date: 2022-11-06
venue: 'ECCV2022'
paperurl: 'https://arxiv.org/pdf/2207.10447'
citation: ' '
---

Weakly Supervised Object Localization (WSOL), which aims to localize objects by only using image-level labels, has attracted much attention because of its low annotation cost in real applications. Recent studies leverage the advantage of self-attention in visual Transformer for long-range dependency to re-active semantic regions, aiming to avoid partial activation in traditional class activation mapping (CAM). However, the long-range modeling in Transformer neglects the inherent spatial coherence of the object, and it usually diffuses the semantic-aware regions far from the object boundary, making localization results significantly larger or far smaller. To address such an issue, we introduce a simple yet effective Spatial Calibration Module (SCM) for accurate WSOL, incorporating semantic similarities of patch tokens and their spatial relationships into a unified diffusion model. Specifically, we introduce a learnable parameter to dynamically adjust the semantic correlations and spatial context intensities for effective information propagation. In practice, SCM is designed as an external module of Transformer, and can be removed during inference to reduce the computation cost. The object-sensitive localization ability is implicitly embedded into the Transformer encoder through optimization in the training phase. It enables the generated attention maps to capture the sharper object boundaries and filter the object-irrelevant background area. Extensive experimental results demonstrate the effectiveness of the proposed method, which significantly outperforms its counterpart TS-CAM on both CUB-200 and ImageNet-1K benchmarks. The code is available at [here](https://github.com/hbai98/SCM).

[Download paper here](https://arxiv.org/pdf/2207.10447)

Recommended citation:  
```
@inproceedings{bai2022weakly,
  title={Weakly supervised object localization via transformer with implicit spatial calibration},
  author={Bai, Haotian and Zhang, Ruimao and Wang, Jiong and Wan, Xiang},
  booktitle={European Conference on Computer Vision},
  pages={612--628},
  year={2022},
  organization={Springer}
}
```