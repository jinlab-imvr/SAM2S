# SAM2S is now **SurgSLOT**

> **This project has been renamed.**
> SAM2S is released as **SurgSLOT: Segment Anything in Surgical Videos via Semantic Long-term Tracking**.
> **Code, checkpoints, and the benchmark are available at → [github.com/jinlab-imvr/SurgSLOT](https://github.com/jinlab-imvr/SurgSLOT)**
> This repository is kept only as a pointer to the new one and is no longer updated.

<div align="center">

[![Code](https://img.shields.io/badge/Code-SurgSLOT-black?logo=github)](https://github.com/jinlab-imvr/SurgSLOT)
[![Project Page](https://img.shields.io/badge/Project-Page-green)](https://jinlab-imvr.github.io/SurgSLOT/)
[![arXiv](https://img.shields.io/badge/arXiv-2511.16618-b31b1b.svg)](https://arxiv.org/abs/2511.16618)
[![Checkpoints](https://img.shields.io/badge/%F0%9F%A4%97%20Checkpoints-HeverLaw%2FSurgSLOT-yellow)](https://huggingface.co/HeverLaw/SurgSLOT)

</div>

## Where everything moved

| | |
|---|---|
| Code (SurgSLOT-SAM2 and SurgSLOT-SAM3) | https://github.com/jinlab-imvr/SurgSLOT |
| Checkpoints | https://huggingface.co/HeverLaw/SurgSLOT |
| Project page | https://jinlab-imvr.github.io/SurgSLOT/ |
| Paper | https://arxiv.org/abs/2511.16618 (same arXiv entry) |

Issues and questions should be opened in the [SurgSLOT repository](https://github.com/jinlab-imvr/SurgSLOT/issues).

## What SurgSLOT is

SurgSLOT is a promptable surgical video segmentation framework that equips both **SAM 2** and **SAM 3** with semantic long-term tracking. A user specifies the target with a first-frame visual prompt, and the model tracks it throughout the video, recovering the target after long disappearances instead of drifting to visually similar distractors. It is developed together with **iSurg**, a generalization-oriented surgical segmentation benchmark unifying 16 datasets across six procedure types.

Compared with the earlier SAM2S preprint, the released version adds the SAM 3 backbone, the extended iSurg benchmark, and the semantic-driven long-term memory (SLM) module. See the [SurgSLOT README](https://github.com/jinlab-imvr/SurgSLOT#readme) for installation, training, evaluation, and full results.

<p align="center">
  <img src="https://jinlab-imvr.github.io/SurgSLOT/static/images/intro.png" width="95%" alt="Overview">
</p>

<p align="center">
  <img src="https://jinlab-imvr.github.io/SurgSLOT/static/images/architecture.png" width="95%" alt="Architecture">
</p>

## Citation

```bibtex
@article{liu2025surgslot,
  title   = {SurgSLOT: Segment Anything in Surgical Videos via Semantic Long-term Tracking},
  author  = {Haofeng Liu and Ziyue Wang and Sudhanshu Mishra and Mingqi Gao and
             Guanyi Qin and Chang Han Low and Alex Y. W. Kong and Zhu Zhuo and
             Huazhu Fu and Joseph S. Ng and Yueming Jin},
  journal = {arXiv preprint arXiv:2511.16618},
  year    = {2025}
}
```
