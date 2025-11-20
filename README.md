# SAM2S: Segment Anything in Surgical Videos via Semantic Long-term Tracking
[![Project Page](https://img.shields.io/badge/Project-Page-green)](https://jinlab-imvr.github.io/SAM2S)

<div align="center">

</div>

Official implementation of SAM2S, a foundation model that enhances SAM2 for surgical interactive Video Object Segmentation (iVOS) through semantic long-term tracking and domain-specific adaptations. The source code is coming soon.

>Haofeng Liu, Ziyue Wang, Sudhanshu Mishra, Mingqi Gao, Guanyi Qin, Chang Han Low, Alex Y. W. Kong, Yueming Jin



## Overview


Surgical video segmentation is crucial for computer-assisted surgery, enabling precise localization and tracking of instruments and tissues. While SAM2 provides prompt-based flexibility, it faces significant challenges in surgical scenarios due to domain gaps and limited long-term tracking capabilities.

SAM2S addresses these limitations through:

1. **SA-SV Benchmark Construction**: Large-scale surgical iVOS dataset spanning diverse procedures (cholecystectomy, colonoscopy, nephrectomy, prostatectomy, etc.) with instance-level spatio-temporal annotations
2. **Enhanced Long-term Tracking**: DiveMem employs hybrid temporal sampling during training and diversity-based frame selection during inference
3. **Semantic Understanding**: TSL leverages semantic categories of surgical instruments while preserving class-agnostic generalization
4. **Multi-source Robustness**: ARL handles annotation ambiguities through uniform label softening

![architecture](./assets/intro.png)
<p align="center"><i>Overall of SAM2S</i></p>

