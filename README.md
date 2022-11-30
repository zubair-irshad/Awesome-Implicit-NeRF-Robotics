# Awesome-Implicit-NeRF-Robotics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repo contains a curative list of **Implicit Representations and NeRF papers relating to Robotics/RL domain**, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) <br>

#### Please feel free to send me [pull requests](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics/blob/main/how-to-PR.md) or [email](mailto:muhammadzubairirshad@gmail.com) to add papers! <br>

If you find this repository useful, please consider [citing](#citation) and STARing this list. Feel free to share this list with others!

For an overview of **NeRFs**, checkout the Survey ([Neural Volume Rendering: NeRF And Beyond](https://arxiv.org/abs/2101.05204)), Blog post ([NeRF Explosion 2020](https://dellaert.github.io/NeRF/)) and Collection ([awesome-NeRF](https://github.com/yenchenlin/awesome-NeRF))

---
## Overview

  - [Object Pose Estimation](#object-pose-estimation)
  - [SLAM](#slam)
  - [Physics](#physics)
  - [Manipulation/RL](#manipulationrl)
  - [Planning/Navigation](#planningnavigation)
  - [Citation](#citation)
 
---
## Object Pose Estimation

* **ShAPO**: Implicit Representations for Multi Object Shape Appearance and Pose Optimization, *ECCV, 2022*. [[Paper](https://arxiv.org/pdf/2207.13691.pdf)] [[Pytorch Code](https://github.com/zubair-irshad/shapo)] [[Webpage](https://zubair-irshad.github.io/projects/ShAPO.html)] [[Video](https://youtu.be/LMg7NDcLDcA)] 

* **NCF**: Neural Correspondence Field for Object Pose Estimation, *ECCV, 2022*. [[Paper](https://arxiv.org/pdf/2208.00113.pdf)] [[Pytorch Code]( https://github.com/LinHuang17/NCF-code)] [[Webpage](https://linhuang17.github.io/NCF/)]

* **NeRF-RPN**: A general framework for object detection in NeRFs, *arXiv*. [[Paper](https://arxiv.org/abs/2211.11646)] [[Video](https://youtu.be/M8_4Ih1CJjE)] 

* **iNeRF**: "Inverting Neural Radiance Fields for Pose Estimation", *IROS, 2021*. [[Paper](https://arxiv.org/pdf/2012.05877.pdf)] [[Pytorch Code](https://github.com/yenchenlin/iNeRF-public)] [[Website](https://yenchenlin.me/inerf/)] [[Dataset](https://github.com/BerkeleyAutomation/dex-nerf-datasets)]

* **NeRF-Pose**: " A First-Reconstruct-Then-Regress Approach for Weakly-supervised 6D Object Pose Estimation", *arXiv*. [[Paper](https://arxiv.org/pdf/2203.04802.pdf)]

* **SNAKE**: " SNAKE: Shape-aware Neural 3D Keypoint Field", *NeurIPS, 2022*. [[Paper](https://arxiv.org/abs/2206.01724.pdf)] [[Pytorch Code](https://github.com/zhongcl-thu/SNAKE)]

* **PixTrack**: Precise 6DoF Object Pose Tracking using NeRF Templates and Feature-metric Alignment, *arXiv*. [[Paper](https://arxiv.org/pdf/2209.03910.pdf)] [[Pytorch Code](https://github.com/GiantAI/pixtrack)]

---
## SLAM
* **iSDF**: Real-Time Neural Signed Distance Fields
for Robot Perception, *RSS, 2022*. [[Paper](https://arxiv.org/abs/2204.02296)] [[Pytorch Code](https://github.com/facebookresearch/iSDF)] [[Website](https://joeaortiz.github.io/iSDF/)]

* **LENS**: " LENS: Localization enhanced by NeRF synthesis", *CORL, 2021*. [[Paper](https://arxiv.org/abs/2110.06558)]

* **NICE-SLAM**: "Neural Implicit Scalable Encoding for SLAM", *CVPR, 2021*. [[Paper](https://arxiv.org/abs/2112.12130)] [Pytorch Code](https://github.com/cvg/nice-slam)] [[Website](https://pengsongyou.github.io/nice-slam?utm_source=catalyzex.com)]

* **iMAP**: "Implicit Mapping and Positioning in Real-Time", *ICCV, 2021*. [[Paper](https://arxiv.org/abs/2103.12352)] [[Website](https://edgarsucar.github.io/iMAP/)]

* **BNV-Fusion**: "BNV-Fusion: Dense 3D Reconstruction using Bi-level Neural Volume Fusion", *CVPR, 2022*. [[Paper](https://arxiv.org/pdf/2204.01139.pdf)] [Pytorch Code](https://github.com/likojack/bnv_fusion)]

* **NeRF-SLAM**: "Real-Time Dense Monocular SLAM with Neural Radiance Fields", *arXiv*. [[Paper](https://arxiv.org/pdf/2210.13641.pdf)]

---
## Physics
* **DANOs**: Differentiable Physics Simulation of Dynamics-Augmented Neural Objects, *arXiv*. [[Paper](https://arxiv.org/abs/2210.09420)] [[Video](https://youtu.be/Md0PM-wv_Xg)]

* **NeuPhysics**: Editable Neural Geometry and Physics from Monocular Videos, *Neurips, 2022*. [[Paper](https://arxiv.org/abs/2210.12352)] [[Pytorch Code](https://github.com/gaoalexander/neuphysics)] [[Website](https://ylqiao.net/publication/2022nerf/)]

---
## Manipulation/RL

* **Ditto**: Building Digital Twins of Articulated Objects from Interaction, *CVPR, 2022*. [[Paper](https://arxiv.org/abs/2202.08227)] [[Pytorch Code](https://github.com/UT-Austin-RPL/Ditto)] [[Website](https://ut-austin-rpl.github.io/Ditto/)]

* **Neural Descriptor Fields**:
SE(3)-Equivariant Object Representations for Manipulation, *arXiv*. [[Paper](https://arxiv.org/abs/2112.05124)] [[Pytorch Code](https://github.com/anthonysimeonov/ndf_robot)] [[Website](https://yilundu.github.io/ndf/)]

* **NeRF-RL**: "Reinforcement Learning with Neural Radiance Fields", *arXiv*. [[Paper](https://dannydriess.github.io/papers/22-driess-NeRF-RL-preprint.pdf)]  [[Website](https://dannydriess.github.io/nerf-rl/)]

* **Dex-NeRF**: "Using a Neural Radiance Field to Grasp Transparent Objects", *CORL, 2021*. [[Paper](https://arxiv.org/abs/2110.14217)]  [[Website](https://sites.google.com/view/dex-nerf)]

* **NeRF-Supervision**: "Learning Dense Object Descriptors from Neural Radiance Fields", *ICRA, 2022*. [[Paper](https://arxiv.org/abs/2203.01913)] [[Pytorch Code](https://github.com/yenchenlin/nerf-supervision-public)] [[Website](https://yenchenlin.me/nerf-supervision/)]

* **GIGA**: "Synergies Between Affordance and Geometry: 6-DoF Grasp Detection via Implicit Representations", *RSS, 2021*. [[Paper](https://arxiv.org/abs/2104.01542)] [[Pytorch Code](https://github.com/UT-Austin-RPL/GIGA)] [[Website](https://sites.google.com/view/rpl-giga2021)]

* **NeuralGrasps**: " Learning Implicit Representations for Grasps of Multiple Robotic Hands", *CORL, 2022*. [[Paper](https://arxiv.org/abs/2207.02959)] [[Website](https://irvlutd.github.io/NeuralGrasps/)]

* **ObjectFolder**: "A Dataset of Objects with Implicit Visual, Auditory, and Tactile Representations"", *CORL, 2021*. [[Paper](https://arxiv.org/pdf/2109.07991.pdf)] [[Pytorch Code](https://github.com/rhgao/ObjectFolder)] [[Website](https://ai.stanford.edu/~rhgao/objectfolder/)]

* **ObjectFolder 2.0**: "A Multisensory Object Dataset for Sim2Real Transfer"", *CVPR, 2022*. [[Paper](https://arxiv.org/pdf/2204.02389.pdf)] [[Pytorch Code](https://github.com/rhgao/ObjectFolder)] [[Website](https://ai.stanford.edu/~rhgao/objectfolder2.0/)]

* **NeRF2Real**: "Sim2real Transfer of Vision-guided Bipedal Motion Skills using Neural Radiance Fields"", *arXiv*. [[Paper](https://arxiv.org/pdf/2210.04932.pdf)] [[Website](https://sites.google.com/view/nerf2real/home)]

* **NiFR**: "Neural Fields for Robotic Object Manipulation from a Single Image", *arXiv*. [[Paper](https://arxiv.org/pdf/2210.12126.pdf)]

---
## Planning/Navigation
* **NeRFlow**: "Neural Radiance Flow for 4D View Synthesis and Video Processing", *ICCV, 2021*. [[Paper](https://arxiv.org/abs/2012.09790)] [[Pytorch Code](https://github.com/yilundu/nerflow)] [[Website](https://yilundu.github.io/nerflow/)] 

* **NeRF-Navigation**: "Vision-Only Robot Navigation in a Neural Radiance World", *ICRA, 2022*. [[Paper](https://mikh3x4.github.io/nerf-navigation/assets/NeRF_Navigation.pdf)] [[Pytorch Code](https://github.com/mikh3x4/nerf-navigation)] [[Website](https://mikh3x4.github.io/nerf-navigation/)] 

* Uncertainty Guided Policy for Active Robotic 3D Reconstruction using Neural Radiance Fields, *RAL, 2022*. [[Paper](https://arxiv.org/pdf/2209.08409.pdf)] [[Website](https://www.vis.xyz/pub/robotic-3d-scan-with-nerf/)] 

* **NeRF-dy**: "3D Neural Scene Representations for Visuomotor Control", *CORL, 2021*. [[Paper](https://arxiv.org/abs/2107.04004)] [[Website](https://3d-representation-learning.github.io/nerf-dy/)] 

* **CompNeRFdyn**: "Learning Multi-Object Dynamics with Compositional Neural Radiance Fields", *arXiv*. [[Paper](https://arxiv.org/pdf/2202.11855.pdf)] [[Website](https://dannydriess.github.io/compnerfdyn/)] 

* **PIFO**: "Deep Visual Constraints: Neural Implicit Models for Manipulation Planning from Visual Input", *arXiv*. [[Paper](https://arxiv.org/pdf/2112.04812.pdf)] [[Website](https://sites.google.com/view/deep-visual-constraints)] 

* **RedSDF**: "Regularized Deep Signed Distance Fields
for Reactive Motion Generation", *arXiv*. [[Paper](https://arxiv.org/abs/2203.04739)] [[Website](https://irosalab.com/2022/02/28/redsdf/)] 

* **ESDF**: "Sampling-free obstacle gradients and reactive planning in Neural Radiance Fields", *arXiv*. [[Paper](https://arxiv.org/abs/2205.01389)]

* "Full-Body Visual Self-Modeling of Robot Morphologies", *arXiv*. [[Paper](https://arxiv.org/abs/2205.01389)] [[Pytorch Code](https://github.com/BoyuanChen/visual-selfmodeling)] [[Website](https://robot-morphology.cs.columbia.edu/)
]

* **CLIP-Fields**: "Open-label semantic navigation with pre-trained VLMs and language models", *arxiv*. [[Paper](https://arxiv.org/abs/2210.05663)] [[Pytorch Code and Tutorials](https://github.com/notmahi/clip-fields)] [[Website](https://mahis.life/clip-fields/)]

----
## Citation
If you find this repository useful, please consider citing this list:
```
@misc{irshad2022implicitnerfroboticspaperslist,
    title = {Awesome-Implicit-NeRF-Robotics},
    author = {Muhammad Zubair Irshad},
    journal = {GitHub repository},
    url = {https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics},
    year = {2022},
}
```
