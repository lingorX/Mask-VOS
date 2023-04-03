# Unified Mask Embedding and Correspondence Learning for Self-Supervised Video Segmentation
[[`arXiv`](https://arxiv.org/abs/2303.10100)] [[`BibTeX`](#CitingMaskVOS)]

## Updates
* This repo will release an official **PaddlePaddle** implementation.

## Abstract
The objective of this paper is self-supervised learning of video object segmentation. We develop a unified framework which simultaneously models cross-frame dense correspondence for locally discriminative feature learning and embeds object-level context for target-mask decoding. As a result, it is able to directly learn to perform mask-guided sequential segmentation from unlabeled videos, in contrast to previous efforts usually relying on an oblique solution - cheaply "copying" labels according to pixel-wise correlations. Concretely, our algorithm alternates between i) clustering video pixels for creating pseudo segmentation labels ex nihilo; and ii) utilizing the pseudo labels to learn mask encoding and decoding for VOS. Unsupervised correspondence learning is further incorporated into this self-taught, mask embedding scheme, so as to ensure the generic nature of the learnt representation and avoid cluster degeneracy. Our algorithm sets state-of-the-arts on two standard benchmarks (i.e., DAVIS17 and YouTube-VOS), narrowing the gap between self- and fully-supervised VOS, in terms of both performance and network architecture design.


## <a name="CitingMaskVOS"></a>Citing MaskVOS
```BibTeX
@article{li2023unified,
  title={Unified Mask Embedding and Correspondence Learning for Self-Supervised Video Segmentation},
  author={Li, Liulei and Wang, Wenguan and Zhou, Tianfei and Li, Jianwu and Yang, Yi},
  journal={arXiv preprint arXiv:2303.10100},
  year={2023}
}
```
