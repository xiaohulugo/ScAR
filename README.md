# ScAR
Official implementation of the IROS2023 paper "ScAR: Scaling Adversarial Robustness for LiDAR Object Detection". https://arxiv.org/abs/2312.03085.
![image](https://github.com/xiaohulugo/ScAR/blob/main/scar_framework.png)

Prerequisites:
---
1. PCDet https://github.com/open-mmlab/OpenPCDet

Usage:
---
1. Follow the instruction of PCDet to install the pre-requirements.
2. Use the attack.py file to generate three types of adversarial attacks: model-aware attack, distribution-aware attack, and blind attack.
3. Use the scar.py file to generate adversarial robust training samples.
4. Test the baseline and the scar-trained baseline on three types of attacked dataset.

Performance:
---
![image](https://github.com/xiaohulugo/ScAR/blob/main/scar_performance.png)

Notice: attack.py and scar.py can be applied on any baselines, you can simply modified the code to adapt to your method.
---

Citation:
---
Please cite the following paper if this you feel this code helpful.

```
@article{lu2023scar,
title={ScAR: Scaling Adversarial Robustness for LiDAR Object Detection},
author={Xiaohu Lu and Hayder Radha},
journal={arXiv preprint arXiv:2312.03085},
year={2023},
}
```
