# Flash-Mono: Feed-Forward Accelerated Gaussian Splatting Monocular SLAM

**ICLR 2026 Poster** | [Project Page](https://victkk.github.io/flash-mono/) | [Paper (PDF)](https://openreview.net/pdf/99fb8fc57267609eb421394a9765e1566a6fe7aa.pdf) | [OpenReview](https://openreview.net/forum?id=nv3q3crc5D)

This repository hosts the project page for **Flash-Mono**.

## Authors

[Zicheng Zhang](https://victkk.github.io/)<sup>1</sup>, [Ke Wu](https://github.com/Promethe-us)<sup>1</sup>, [Xiangting Meng](https://github.com/Launch-on-Titania)<sup>2</sup>, [Keyu Liu](https://github.com/LordLKY)<sup>3</sup>, [Jieru Zhao](https://zjru.github.io/)<sup>3</sup>, [Wenchao Ding](https://wenchaoding.github.io/)<sup>1</sup>

<sup>1</sup>Fudan University &nbsp; <sup>2</sup>ShanghaiTech University &nbsp; <sup>3</sup>Shanghai Jiao Tong University

## Abstract

Monocular 3D Gaussian Splatting SLAM suffers from critical limitations in time efficiency, geometric accuracy, and multi-view consistency. We present **Flash-Mono**, a system composed of three core modules: a feed-forward prediction frontend, a 2D Gaussian Splatting mapping backend, and an efficient hidden-state-based loop closure module. By directly predicting Gaussian attributes, our method bypasses the burdensome per-frame optimization required in optimization-based GS-SLAM, achieving a **10x** speedup while ensuring high-quality rendering.

## Citation

```bibtex
@inproceedings{zhang2026flashmono,
  title={Flash-Mono: Feed-Forward Accelerated Gaussian Splatting Monocular {SLAM}},
  author={Zicheng Zhang and Ke Wu and Xiangting Meng and Keyu Liu and Jieru Zhao and Wenchao Ding},
  booktitle={The Fourteenth International Conference on Learning Representations},
  year={2026},
  url={https://openreview.net/forum?id=nv3q3crc5D}
}
```

## Acknowledgments

This project page is built using the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template). Licensed under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).
