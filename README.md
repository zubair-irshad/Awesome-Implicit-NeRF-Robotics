# Awesome-Implicit-NeRF-Robotics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repo contains a curative list of **Implicit Representations and NeRF papers relating to Robotics/RL domain**, inspired by [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) <br>

#### Please feel free to send me [pull requests](https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics/blob/main/how-to-PR.md) or [email](mailto:muhammadzubairirshad@gmail.com) to add papers! <br>

If you find this repository useful, please consider [citing](#citation) and STARing this list. Feel free to share this list with others!

For an overview of **NeRFs**, checkout the Survey ([Neural Volume Rendering: NeRF And Beyond](https://arxiv.org/abs/2101.05204)), Blog post ([NeRF Explosion 2020](https://dellaert.github.io/NeRF/)) and Collection ([awesome-NeRF](https://github.com/yenchenlin/awesome-NeRF))

---
## Overview

  - [Object Pose Estimation](#object-pose-estimation)
  - [SLAM](#slam)
  - [Manipulation/RL](#manipulationrl)
  - [Object Reconstruction](#object-reconstruction)
  - [Physics](#physics)
  - [Planning/Navigation](#planningnavigation)
  - [Citation](#citation)
 
---
## Object Pose Estimation

* **BundleSDF**: "Neural 6-DoF Tracking and 3D Reconstruction of Unknown Objects", *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2303.14158.pdf)] [[Webpage](https://bundlesdf.github.io/)] 

* **ShAPO**: "Implicit Representations for Multi Object Shape Appearance and Pose Optimization", *ECCV, 2022*. [[Paper](https://arxiv.org/pdf/2207.13691.pdf)] [[Pytorch Code](https://github.com/zubair-irshad/shapo)] [[Webpage](https://zubair-irshad.github.io/projects/ShAPO.html)] [[Video](https://youtu.be/LMg7NDcLDcA)] 

* **NCF**: "Neural Correspondence Field for Object Pose Estimation", *ECCV, 2022*. [[Paper](https://arxiv.org/pdf/2208.00113.pdf)] [[Pytorch Code]( https://github.com/LinHuang17/NCF-code)] [[Webpage](https://linhuang17.github.io/NCF/)]

* **Neural-Sim**: "Learning to Generate Training Data with NeRF", *ECCV 2022*.  [[Paper](https://arxiv.org/pdf/2207.11368.pdf)] [[Pytorch Code](https://github.com/gyhandy/Neural-Sim-NeRF)] [[Webpage](https://fylwen.github.io/disp6d.html)]

* **DISP6D**: "Disentangled Implicit Shape and Pose Learning for Scalable 6D Pose Estimation", *ECCV 2022*.  [[Paper](https://arxiv.org/pdf/2107.12549.pdf)] [[Pytorch Code](https://github.com/fylwen/DISP-6D)] [[Webpage](https://nerf2nerf.github.io/)] [[Video](https://youtu.be/GTBfCB2A7sI)]

* **SNAKE**: "SNAKE: Shape-aware Neural 3D Keypoint Field", *NeurIPS, 2022*. [[Paper](https://arxiv.org/abs/2206.01724.pdf)] [[Pytorch Code](https://github.com/zhongcl-thu/SNAKE)]

* **NeRF-RPN**: "A general framework for object detection in NeRFs", *arXiv*. [[Paper](https://arxiv.org/abs/2211.11646)] [[Video](https://youtu.be/M8_4Ih1CJjE)] 

* **nerf2nerf**: "Pairwise Registration of Neural Radiance Fields", *arXiv*.  [[Paper](https://arxiv.org/pdf/2211.01600.pdf)] [[Pytorch Code]( https://github.com/nerf2nerf/nerf2nerf)] [[Webpage](https://nerf2nerf.github.io/)] [[Dataset](https://drive.google.com/drive/folders/1jNpwAv1T1ntjIHUMJ1wABePA2Z8_nRRQ)]

* **iNeRF**: "Inverting Neural Radiance Fields for Pose Estimation", *IROS, 2021*. [[Paper](https://arxiv.org/pdf/2012.05877.pdf)] [[Pytorch Code](https://github.com/yenchenlin/iNeRF-public)] [[Website](https://yenchenlin.me/inerf/)] [[Dataset](https://github.com/BerkeleyAutomation/dex-nerf-datasets)]

* **NeRF-Pose**: "A First-Reconstruct-Then-Regress Approach for Weakly-supervised 6D Object Pose Estimation", *arXiv*. [[Paper](https://arxiv.org/pdf/2203.04802.pdf)]

* **PixTrack**: "Precise 6DoF Object Pose Tracking using NeRF Templates and Feature-metric Alignment", *arXiv*. [[Paper](https://arxiv.org/pdf/2209.03910.pdf)] [[Pytorch Code](https://github.com/GiantAI/pixtrack)]

* "Parallel Inversion of Neural Radiance Fields for Robust Pose Estimation", *arXiv*. [[Paper](https://arxiv.org/abs/2210.10108v1)] [[Website](https://pnerfp.github.io/)]

* **NARF22**: "Neural Articulated Radiance Fields for Configuration-Aware Rendering", *IROS, 2022*. [[Paper](https://arxiv.org/pdf/2210.01166.pdf)] [[Website](https://progress.eecs.umich.edu/projects/narf/)]

* **FroDO**: "From Detections to 3D Objects", *CVPR, 2020*. [[Paper](https://arxiv.org/pdf/2005.05125.pdf)] 

* **SDFEst**: "Categorical Pose and Shape Estimation of Objects From RGB-D Using Signed Distance Fields", *RA-L, 2022*. [[Paper](https://arxiv.org/pdf/2207.04880.pdf)] [[Pytorch Code](https://arxiv.org/pdf/2207.04880.pdf)]

* **SSC-6D**: "Self-Supervised Category-Level 6D Object Pose Estimation with Deep Implicit Shape Representation", *AAAI, 2022*. [[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/20104)] [[Pytorch Code](https://github.com/swords123/SSC-6D)]

* **Style2NeRF**: "An Unsupervised One-Shot NeRF for Semantic 3D Reconstruction", *BMVC, 2022*. [[Paper](https://bmvc2022.mpi-inf.mpg.de/0104.pdf)] 

* "Shape, Pose, and Appearance from a Single Image via Bootstrapped Radiance Field Inversion", *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2211.11674.pdf)] [[Code](https://github.com/google-research/nerf-from-image)]

* **TexPose**: "Neural Texture Learning for Self-Supervised 6D Object Pose Estimation", *CVPR 2023*. [[Paper](https://arxiv.org/pdf/2212.12902.pdf)][[Code](https://github.com/HanzhiC/TexPose)]

* **Canonical Fields**: "Self-Supervised Learning of Pose-Canonicalized Neural Fields", *arXiv*. [[Paper](https://arxiv.org/pdf/2212.02493.pdf)]
  
* **NeRF-Det**: "Learning Geometry-Aware Volumetric Representation for Multi-View 3D Object Detection", *arXiv*. [[Paper](https://arxiv.org/abs/2307.14620)] [[Page] https://chenfengxu714.github.io/nerfdet/] [[Code] https://github.com/facebookresearch/NeRF-Det]

---
## SLAM
* **iSDF**: "Real-Time Neural Signed Distance Fields for Robot Perception", *RSS, 2022*. [[Paper](https://arxiv.org/abs/2204.02296)] [[Pytorch Code](https://github.com/facebookresearch/iSDF)] [[Website](https://joeaortiz.github.io/iSDF/)]

* **LENS**: "LENS: Localization enhanced by NeRF synthesis", *CORL, 2021*. [[Paper](https://arxiv.org/abs/2110.06558)]

* **NICE-SLAM**: "Neural Implicit Scalable Encoding for SLAM", *CVPR, 2021*. [[Paper](https://arxiv.org/abs/2112.12130)] [Pytorch Code](https://github.com/cvg/nice-slam)] [[Website](https://pengsongyou.github.io/nice-slam?utm_source=catalyzex.com)]

* **iMAP**: "Implicit Mapping and Positioning in Real-Time", *ICCV, 2021*. [[Paper](https://arxiv.org/abs/2103.12352)] [[Website](https://edgarsucar.github.io/iMAP/)]

* **BNV-Fusion**: "BNV-Fusion: Dense 3D Reconstruction using Bi-level Neural Volume Fusion", *CVPR, 2022*. [[Paper](https://arxiv.org/pdf/2204.01139.pdf)] [Pytorch Code](https://github.com/likojack/bnv_fusion)]

* **NeRF-SLAM**: "Real-Time Dense Monocular SLAM with Neural Radiance Fields", *arXiv*. [[Paper](https://arxiv.org/pdf/2210.13641.pdf)]

* **NICER-SLAM**: "Neural Implicit Scene Encoding for RGB SLAM", *arXiv*. [[Paper](https://arxiv.org/pdf/2302.03594.pdf)] [[Video](https://youtu.be/tUXzqEZWg2w)]

* **Nerfels**: "Renderable Neural Codes for Improved Camera Pose Estimation", *CVPR 2022 Workshop*. [[Paper](https://openaccess.thecvf.com/content/CVPR2022W/IMW/papers/Avraham_Nerfels_Renderable_Neural_Codes_for_Improved_Camera_Pose_Estimation_CVPRW_2022_paper.pdf)]

* **GO-Surf**: "A Real-time Monocular Visual SLAM with ORB Features and NeRF-realized Mapping", *3DV, 2022*. [[Paper](https://arxiv.org/pdf/2206.14735.pdf)] [[Website(https://jingwenwang95.github.io/go_surf/)] [[Pytorch Code](https://github.com/JingwenWang95/go-surf)]

* **Orbeez-SLAM**: "Neural Feature Grid Optimization for Fast, High-Fidelity RGB-D Surface Reconstruction", *arXiv, 2022*. [[Paper](https://arxiv.org/pdf/2209.13274.pdf)]

* **ESLAM**: "Efficient Dense SLAM System Based on Hybrid Representation of Signed Distance Fields", *arXiv,  2022*. [[Paper](https://arxiv.org/pdf/2211.11704.pdf)]

* **Panoptic Multi-TSDFs**: "a Flexible Representation for Online Multi-resolution Volumetric Mapping and Long-term Dynamic Scene Consistency", *ICRA,  2022*. [[Paper](https://arxiv.org/pdf/2211.11704.pdf)] [[Pytorch Code](https://github.com/ethz-asl/panoptic_mapping)]

* **SHINE-Mapping**: "Large-Scale 3D Mapping Using Sparse Hierarchical Implicit Neural Representations", *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2210.02299.pdf)] [[Code](https://github.com/PRBonn/SHINE_mapping)]

* "SDF-based RGB-D Camera Tracking in Neural Scene Representations", *ICRA Workshop, 2022*. [[Paper](https://neural-implicit-workshop.stanford.edu/assets/pdf/bruns.pdf)]

* **Loc-NeRF**: "Monte Carlo Localization using Neural Radiance Fields", *ICRA,  2023*. [[Paper](https://arxiv.org/abs/2209.09050)] [[Code](https://github.com/MIT-SPARK/Loc-NeRF)] [[Video](https://www.youtube.com/watch?v=yIgl3kbpbXY)]

* **Vox-Fusion**: "Dense Tracking and Mapping with Voxel-based Neural Implicit Representation", *ISMAR,  2022*. [[Paper](https://arxiv.org/pdf/2210.15858.pdf)] [[Website](https://yangxingrui.com/vox-fusion/)] [[Pytorch Code](https://github.com/zju3dv/Vox-Fusion)] [[Video](https://www.youtube.com/watch?v=Prp28y1b2Qs)]

* **NodeSLAM**: "Dense Tracking and Mapping with Voxel-based Neural Implicit Representation", *3DV, 2020*. [[Paper](https://arxiv.org/pdf/2004.04485.pdf)] 

* **iLabel**: "Revealing Objects in Neural Fields", *RA-L, 2023*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9996585)] 

* **Nerf–**: "Neural radiance fields without known camera parameters", *arXiv*. [[Paper](https://arxiv.org/pdf/2102.07064.pdf)] 

* **L2G-NeRF**: "Local-to-Global Registration for Bundle-Adjusting Neural Radiance Fields", *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2211.11505.pdf)] [[Website](https://rover-xingyu.github.io/L2G-NeRF/)] [[code](https://github.com/rover-xingyu/L2G-NeRF)]

* **H2-Mapping**: "Real-time Dense Mapping Using Hierarchical Hybrid Representation", *RA-L, 2023*. [[Paper](https://arxiv.org/pdf/2306.03207.pdf)] [[code](https://github.com/SYSU-STAR/H2-Mapping)]

* **Continual Neural Mapping**: "Learning An Implicit Scene Representation from Sequential Observations", *ICCV,  2021*. [[Paper](https://arxiv.org/pdf/2108.05851.pdf)]

* **LATITUDE**: Robotic Global Localization with Truncated Dynamic Low-pass Filter in City-scale NeRF, *ICRA,  2023*. [[Paper](https://arxiv.org/pdf/2209.09357.pdf)] [[Pytorch Code](https://github.com/jike5/LATITUDE)]

* "Dense RGB SLAM with neural implicit maps", *ICLR,  2023*. [[Paper](https://arxiv.org/pdf/2301.08930.pdf)]

* **NOCaL**: Calibration-free semi-supervised learning of odometry and camera intrinsics, *ICRA,  2023*. [[Paper](https://arxiv.org/pdf/2210.07435.pdf)] [[Website](https://roboticimaging.org/Projects/NOCaL/)]

- **IRMCL**: Implicit Representation-based Online Global Localization, *arXiv*. [[Paper](https://arxiv.org/pdf/2210.03113.pdf)] [[Code](https://github.com/PRBonn/ir-mcl)]

- Efficient Implicit Neural Reconstruction Using LiDAR, *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2302.14363.pdf)] [[Website](http://starydy.xyz/EINRUL/)] [[Pytorch Code](https://github.com/StarRealMan/EINRUL)] [[Video](https://www.youtube.com/watch?v=wUp2I-X-IdI)]

* **vMAP**: "Vectorised Object Mapping for Neural Field SLAM", *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2302.01838.pdf)] [[Website](https://kxhit.github.io/vMAP)]

* "An Algorithm for the SE(3)-Transformation on Neural Implicit Maps for Remapping Functions", *RA-L, 2022*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9804847)]

* "Implicit Object Reconstruction With Noisy Data", *RSS Workshop, 2021*. [[Paper](https://arxiv.org/pdf/2204.10516.pdf)]

* **NeuSE**: "Neural SE(3)-Equivariant Embedding for Consistent Spatial Understanding with Objects", *arXiv*. [[Paper](https://arxiv.org/pdf/2303.07308.pdf)] [[Website](https://neuse-slam.github.io/neuse/)]

* **ObjectFusion**: "Accurate object-level SLAM with neural object priors", *Graphical Models,  2022*. [[Paper](https://www.sciencedirect.com/science/article/pii/S1524070322000418)]

* **NDF_Change**: "Robust Change Detection Based on Neural Descriptor Fields", *IROS, 2022*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9981246)]

* **LNDF**: "Local Neural Descriptor Fields: Locally Conditioned Object Representations for Manipulation", *ICRA, 2023*. [[Paper](https://arxiv.org/abs/2302.03573)] [[Webpage](https://elchun.github.io/lndf/)]

- **NeRF-LOAM**: Neural Implicit Representation for Large-Scale Incremental LiDAR Odometry and Mapping, *arXiv*. [[Paper](https://arxiv.org/pdf/2303.10709.pdf)] [[Code](https://github.com/JunyuanDeng/NeRF-LOAM)]

* **NeuralBlox**: "Real-Time Neural Representation Fusion for Robust Volumetric Mapping", *3DV, 2021*. [[Paper](https://ieeexplore.ieee.org/abstract/document/9665902)] [[Code](https://github.com/ethz-asl/neuralblox)]

- **Di-fusion**: Online implicit 3d reconstruction with deep priors, *CVPR, 2021*.[[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Huang_DI-Fusion_Online_Implicit_3D_Reconstruction_With_Deep_Priors_CVPR_2021_paper.pdf)] [[Pytorch Code](https://github.com/huangjh-pub/di-fusion)] 

* **CROSSFIRE**: "Camera Relocalization On Self-Supervised Features from an Implicit Representation", *arXiv*. [[Paper](https://arxiv.org/abs/2303.04869)]

* **SDF-Loc**: "Signed Distance Field based 2D Relocalization and Map Update in Dynamic Environments", *ACC, 2019*. [[Paper](https://hitcm.github.io/data/papers/ACC19_sdf_loc.pdf)]

* **iDF-SLAM**: "End-to-End RGB-D SLAM with Neural Implicit Mapping and Deep Feature Tracking", *arXiv*. [[Paper](https://arxiv.org/pdf/2209.07919.pdf)]

* "Implicit Map Augmentation for Relocalization", *ECCV Workshop, 2022*. [[Paper](https://link.springer.com/chapter/10.1007/978-3-031-25066-8_36)]

* "Visual-Inertial Odometry Priors for Bundle-Adjusting Neural Radiance Fields", *ICCAS, 2022*. [[Paper](http://mpil.sookmyung.ac.kr/wp-content/uploads/2022/12/2022_ICCAS_Kim.pdf)]

* "Towards Open World NeRF-Based SLAM", *arXiv, 2023*.  [[Paper](https://arxiv.org/pdf/2301.03102.pdf)]

*  **Uni-Fusion**: Universal Continuous Mapping, *arXiv, 2023*.[[Paper](https://arxiv.org/pdf/2303.12678.pdf)] [[Website](https://jarrome.github.io/Uni-Fusion/)]

*  **NEWTON**: Neural View-Centric Mapping for On-the-Fly Large-Scale SLAM, *arXiv, 2023*.[[Paper](https://arxiv.org/pdf/2303.13654v1.pdf)]

*  **Point-SLAM**: Dense Neural Point Cloud-based SLAM, *arXiv, 2023*. [[Paper](https://arxiv.org/pdf/2304.04278.pdf)] [[Code](https://github.com/tfy14esa/Point-SLAM)]

* "ActiveRMAP: Radiance Field for Active Mapping And Planning", *arXiv, 2022". [[Paper](https://arxiv.org/pdf/2211.12656.pdf)]

* **NF-Atlas**: Multi-Volume Neural Feature Fields for Large Scale LiDAR Mapping, *arXiv, 2023*. [[Paper](https://arxiv.org/pdf/2304.04624.pdf)]

*  **RO-MAP**: Real-Time Multi-Object Mapping with Neural Radiance Fields, *arXiv, 2023*. [[Paper](https://arxiv.org/pdf/2304.05735.pdf)] [[Code](https://github.com/XiaoHan-Git/RO-MAP)] [[Video](https://www.youtube.com/watch?v=sFrLXPw40wU)]

*  **Co-SLAM**: Joint Coordinate and Sparse Parametric Encodings for Neural Real-Time SLAM, *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2304.14377.pdf)] [[Website](https://hengyiwang.github.io/projects/CoSLAM)]
*  Neural Implicit Dense Semantic SLAM, *arXiv, 2023*. [[Paper](https://arxiv.org/pdf/2304.14560.pdf)]

* **2D-SDF-SLAM**: "A Signed Distance Function based SLAM Frontend for Laser Scanners", *IROS, 2015*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=7353633)]

* **LONER**: "LiDAR Only Neural Representations for Real-Time SLAM", *RA-L, 2023*. [[paper](https://arxiv.org/abs/2309.04937)] [[code](https://github.com/umautobots/loner)] [[website](https://umautobots.github.io/loner)]
---
## Manipulation/RL

* **D<sup>3</sup>Fields**: "D<sup>3</sup>Fields: Dynamic 3D Descriptor Fields for Zero-Shot Generalizable Robotic Manipulation", *arXiv*. [[Paper](https://arxiv.org/abs/2309.16118)] [[Webpage](https://robopil.github.io/d3fields/)] [[Code](https://github.com/WangYixuan12/d3fields)] [[Video](https://youtu.be/yNkIOwAO3GA)]

* **SNeRL**: "Semantic-aware Neural Radiance Fields for Reinforcement Learning", *ICML, 2023*. [[Paper](https://arxiv.org/pdf/2301.11520.pdf)] [[Webpage](https://sjlee.cc/snerl/)]

* **Ditto**: "Building Digital Twins of Articulated Objects from Interaction", *CVPR, 2022*. [[Paper](https://arxiv.org/abs/2202.08227)] [[Pytorch Code](https://github.com/UT-Austin-RPL/Ditto)] [[Website](https://ut-austin-rpl.github.io/Ditto/)]

* **Relational-NDF**: "SE(3)-Equivariant Relational Rearrangement with Neural Descriptor Fields", *CORL 2022*. [[Paper](https://arxiv.org/pdf/2211.09786.pdf)] [[Pytorch Code](https://github.com/anthonysimeonov/relational_ndf)] [[Website](https://anthonysimeonov.github.io/r-ndf/)]

* **Neural Descriptor Fields**: "SE(3)-Equivariant Object Representations for Manipulation", *arXiv*. [[Paper](https://arxiv.org/abs/2112.05124)] [[Pytorch Code](https://github.com/anthonysimeonov/ndf_robot)] [[Website](https://yilundu.github.io/ndf/)]

* **Evo-NeRF**: "Evolving NeRF for Sequential Robot Grasping of Transparent Objects", *CORL 2022*. [[Paper](https://openreview.net/pdf?id=Bxr45keYrf)]  [[Website](https://sites.google.com/view/evo-nerf)]

* **NeRF-RL**: "Reinforcement Learning with Neural Radiance Fields", *arXiv*. [[Paper](https://dannydriess.github.io/papers/22-driess-NeRF-RL-preprint.pdf)]  [[Website](https://dannydriess.github.io/nerf-rl/)]

* **Neural Motion Fields**: "Encoding Grasp Trajectories as Implicit Value Functions", *RSS 2022*. [[Paper](https://arxiv.org/pdf/2206.14854.pdf)]  [[Video](https://youtu.be/B-pEhT1pi-Q)]

* **Grasping Field**: "Learning Implicit Representations for Human Grasps", *3DV 2020*. [[Paper](https://arxiv.org/pdf/2008.04451.pdf)] [[Pytorch Code](https://github.com/korrawe/grasping_field)] [[Video](https://youtu.be/J8x5i1FCgTQ)]

* **Dex-NeRF**: "Using a Neural Radiance Field to Grasp Transparent Objects", *CORL, 2021*. [[Paper](https://arxiv.org/abs/2110.14217)]  [[Website](https://sites.google.com/view/dex-nerf)]

* **NeRF-Supervision**: "Learning Dense Object Descriptors from Neural Radiance Fields", *ICRA, 2022*. [[Paper](https://arxiv.org/abs/2203.01913)] [[Pytorch Code](https://github.com/yenchenlin/nerf-supervision-public)] [[Website](https://yenchenlin.me/nerf-supervision/)]

* **GIGA**: "Synergies Between Affordance and Geometry: 6-DoF Grasp Detection via Implicit Representations", *RSS, 2021*. [[Paper](https://arxiv.org/abs/2104.01542)] [[Pytorch Code](https://github.com/UT-Austin-RPL/GIGA)] [[Website](https://sites.google.com/view/rpl-giga2021)]

* **NeuralGrasps**: "Learning Implicit Representations for Grasps of Multiple Robotic Hands", *CORL, 2022*. [[Paper](https://arxiv.org/abs/2207.02959)] [[Website](https://irvlutd.github.io/NeuralGrasps/)]

* "Real-time Mapping of Physical Scene Properties with an Autonomous Robot Experimenter", *CORL, 2022*. [[Paper](https://arxiv.org/abs/2210.17325)] [[Website](https://ihaughton.github.io/RobE/)]

* **ObjectFolder**: "A Dataset of Objects with Implicit Visual, Auditory, and Tactile Representations"", *CORL, 2021*. [[Paper](https://arxiv.org/pdf/2109.07991.pdf)] [[Pytorch Code](https://github.com/rhgao/ObjectFolder)] [[Website](https://ai.stanford.edu/~rhgao/objectfolder/)]

* **ObjectFolder 2.0**: "A Multisensory Object Dataset for Sim2Real Transfer"", *CVPR, 2022*. [[Paper](https://arxiv.org/pdf/2204.02389.pdf)] [[Pytorch Code](https://github.com/rhgao/ObjectFolder)] [[Website](https://ai.stanford.edu/~rhgao/objectfolder2.0/)]

* "Template-Based Category-Agnostic Instance Detection for Robotic Manipulation"", *RA-L, 2022*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9935113)] 

* **NeRF2Real**: "Sim2real Transfer of Vision-guided Bipedal Motion Skills using Neural Radiance Fields"", *arXiv*. [[Paper](https://arxiv.org/pdf/2210.04932.pdf)] [[Website](https://sites.google.com/view/nerf2real/home)]

* **NeRF-Frenemy**: "Co-Opting Adversarial Learning for Autonomy-Directed Co-Design", *RSS Workshop, 2022*. [[Paper](https://imrss2022.github.io/contributions/lewis.pdf)] [[Website](https://progress.eecs.umich.edu/projects/nerf-frenemy/)]

* **CLA-NeRF**: "Category-Level Articulated Neural Radiance Field", *ICRA, 2022*. [[Paper](https://arxiv.org/pdf/2202.00181.pdf)] [[Website](https://weichengtseng.github.io/project_website/icra22/index.html)]

* **VIRDO**: "Visio-tactile Implicit Representations of Deformable Objects", *ICRA, 2022*. [[Paper](https://arxiv.org/pdf/2202.00868.pdf)] [[Website](https://www.mmintlab.com/research/virdo-visio-tactile-implicit-representations-of-deformable-objects/)]

* **VIRDO++:**: "Real-World, Visuo-Tactile Dynamics and Perception of Deformable Objects", *CORL, 2022*. [[Paper](https://arxiv.org/pdf/2210.03701.pdf)] [[Website](https://www.mmintlab.com/virdopp/)]

* **SceneCollisionNet**: "Object Rearrangement Using Learned Implicit Collision Functions", *ICRA, 2021*. [[Paper](https://arxiv.org/pdf/2011.10726.pdf)] [[Website](https://research.nvidia.com/publication/2021-03_object-rearrangement-using-learned-implicit-collision-functions)]

* "RGB-D Local Implicit Function for Depth Completion of Transparent Objects", *CVPR, 2021*. [[Paper](https://arxiv.org/pdf/2104.00622.pdf)] [[Website](https://research.nvidia.com/publication/2021-03_rgb-d-local-implicit-function-depth-completion-transparent-objects)]

* "Learning Models as Functionals of Signed-Distance Fields for Manipulation Planning", *CORL, 2021*. [[Paper](https://openreview.net/pdf?id=FS30JeiGG3h)] [[Video](https://youtu.be/ga8Wlkss7co)]

* **ContactNets**: "Learning Discontinuous Contact Dynamics with Smooth, Implicit Representations", *CORL, 2020*. [[Paper](https://arxiv.org/pdf/2009.11193.pdf)] [[Pytorch Code](https://github.com/DAIRLab/contact-nets)]

* "Learning Implicit Priors for Motion Optimization", *IROS, 2022*. [[Paper](https://arxiv.org/pdf/2204.05369.pdf)] [[Website](https://sites.google.com/view/implicit-priors)]

* **MIRA**: "Mental Imagery for Robotic Affordances", *CORL, 2022*. [[Paper](https://arxiv.org/pdf/2212.06088.pdf)] [[Website](http://yenchenlin.me/mira/)]

* **NiFR**: "Neural Fields for Robotic Object Manipulation from a Single Image", *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2210.12126.pdf)]

* **NIFT**: "Neural Interaction Field and Template for Object Manipulation", *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2210.10992.pdf)]

* "Learning 6-DoF Task-oriented Grasp Detection via Implicit Estimation and Visual Affordance", "IROS, 2022". [[Paper](https://arxiv.org/pdf/2210.08537.pdf)]

* **GraspNeRF**: "Multiview-based 6-DoF Grasp Detection for Transparent and Specular Objects Using Generalizable NeRF", *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2210.06575v1.pdf)]

* **Touching a NeRF**: "Leveraging Neural Radiance Fields for Tactile Sensory Data Generation ", *CORL, 2022*. [[Paper](https://openreview.net/pdf?id=No3mbanRlZJ)]

* **SE(3)-DiffusionFields**: "Learning smooth cost functions for joint grasp and motion optimization through diffusion", *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2209.03855.pdf)] [[Pytorch Code](https://github.com/TheCamusean/grasp_diffusion)]

* **Equivariant Descriptor Fields**: "SE(3)-Equivariant Energy-Based Models for End-to-End Visual Robotic Manipulation Learning ", *ICLR, 2023*. [[Paper](https://openreview.net/pdf?id=dnjZSPGmY5O)] 

* **KP-NERF**: "Dynamical Scene Representation and Control with Keypoint-Conditioned Neural Radiance Field", *CASE, 2022*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9926555)]

* **ACID**: "Action-Conditional Implicit Visual Dynamics for Deformable Object Manipulation", *RSS, 2022*. [[Paper](https://arxiv.org/pdf/2203.06856.pdf)] [[Pytorch Code](https://github.com/NVlabs/ACID)]

* **TRITON**: "Neural Neural Textures Make Sim2Real Consistent", *CORL, 2022*. [[Paper](https://arxiv.org/pdf/2206.13500.pdf)] [[Website](https://tritonpaper.github.io/)] [[Pytorch Code](https://github.com/TritonPaper/TRITON)]

* "Perceiving Unseen 3D Objects by Poking the Objects", *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2302.13375.pdf)] [[Website](https://zju3dv.github.io/poking_perception/)] [[Pytorch Code](https://github.com/zju3dv/poking_perception)]

* "Feature-Realistic Neural Fusion for Real-Time, Open Set Scene Understanding", *ICRA, 2023*. [[Paper](https://arxiv.org/pdf/2210.03043.pdf)] [[Website](https://makezur.github.io/FeatureRealisticFusion/)]

* **CGF**: "Learning Continuous Grasping Function with a Dexterous Hand from Human Demonstrations", *arXiv*. [[Paper](https://arxiv.org/pdf/2203.06856.pdf)] [[Website](https://jianglongye.com/cgf/)]

* **NGDF**: "Neural Grasp Distance Fields for Robot Manipulation", *arXiv*. [[Paper](https://arxiv.org/pdf/2211.02647.pdf)] [[Website](https://sites.google.com/view/neural-grasp-distance-fields?pli=1)] [[Pytorch Code](https://github.com/facebookresearch/NGDF/)] 

* **NCF**: "Neural Contact Fields: Tracking Extrinsic Contact with Tactile Sensing", *arXiv*. [[Paper](https://arxiv.org/pdf/2210.09297.pdf)] [[Pytorch Code](https://github.com/carolinahiguera/NCF)] 

* **SPARTN**: "NeRF in the Palm of Your Hand: Corrective Augmentation for Robotics via Novel-View Synthesis", *arXiv*. [[Paper](https://arxiv.org/pdf/2301.08556.pdf)] 

* "RGB-Only Reconstruction of Tabletop Scenes for Collision-Free Manipulator Control", *arXiv*. [[Paper](https://arxiv.org/pdf/2210.11668v1.pdf)] [[Website](https://sites.google.com/nvidia.com/ngp-mpc/)]

* ""Affordance Transfer based on Self-Aligning Implicit Representations of Local Surfaces", "RSS Workshop, 2022". [Paper][https://imrss2022.github.io/contributions/tekden.pdf]

* "A Real2Sim2Real Method for Robust Object Grasping with Neural Surface Reconstruction", *arXiv*. [[Paper](https://arxiv.org/pdf/2210.02685.pdf)] [[Video](https://www.youtube.com/watch?v=TkvAKLsxkSc)]

* **EndoNeRF**: "Neural Rendering for Stereo 3D Reconstruction of Deformable Tissues in Robotic Surgery", *MICCAI, 2022*. [[Paper](https://arxiv.org/pdf/2206.15255.pdf)] [[Pytorch Code](https://github.com/med-air/EndoNeRF)]
	
---
## Object Reconstruction

* "Self-supervised Neural Articulated Shape and Appearance Models", *CVPR, 2022*. [[Paper](https://arxiv.org/pdf/2205.08525.pdf)] [[Website](https://weify627.github.io/nasam/)]

* **NeuS**: "Learning Neural Implicit Surfacesby Volume Rendering for Multi-view Reconstruction", *Neurips, 2021*. [[Paper](https://arxiv.org/pdf/2106.10689.pdf)] [[Website](https://lingjie0206.github.io/papers/NeuS/)]

* **VolSDF**: "Volume Rendering of Neural Implicit Surfaces", *Neurips, 2021*. [[Paper](https://arxiv.org/pdf/2106.12052.pdf)] [[Pytorch Code](https://github.com/lioryariv/volsdf)]

* **UNISURF**: "Unifying Neural Implicit Surfaces and Radiance Fields for Multi-View Reconstruction", *ICCV, 2021*. [[Paper](https://arxiv.org/pdf/2104.10078.pdf)] [[Website](https://moechsle.github.io/unisurf/)] [[Pytorch Code](https://github.com/autonomousvision/unisurf)]

* **ObjectSDF**: "Object-Compositional Neural Implicit Surfaces", *ECCV, 2022*. [[Paper](https://arxiv.org/pdf/2207.09686.pdf)] [[Website](https://wuqianyi.top/objectsdf/)] [[Pytorch Code](https://github.com/QianyiWu/objsdf)]

* **IDR**: "Multiview Neural Surface Reconstruction by Disentangling Geometry and Appearance", *Neurips, 2020*. [[Paper](https://arxiv.org/pdf/2003.09852.pdf)] [[Website](https://lioryariv.github.io/idr/)] [[Pytorch Code](https://github.com/lioryariv/idr)]

* **DVR**: "Differentiable Volumetric Rendering: Learning Implicit 3D Representations without 3D Supervision", *CVPR, 2020*. [[Paper](https://arxiv.org/pdf/1912.07372.pdf)] [[Pytorch Code](https://github.com/autonomousvision/differentiable_volumetric_rendering)]

* **A-SDF**: "Learning Disentangled Signed Distance Functions for Articulated Shape Representation", *ICCV, 2021*. [[Paper](https://arxiv.org/pdf/2104.07645.pdf)] [[Pytorch Code](https://github.com/JitengMu/A-SDF)]

* **CodeNeRF**: "Disentangled Neural Radiance Fields for Object Categories", *ICCV, 2021*. [[Paper](https://arxiv.org/pdf/2109.01750.pdf)] [[Pytorch Code](https://github.com/wbjang/code-nerf)]

* **DeepSDF**: " Learning Continuous Signed Distance Functions for Shape Representation", *CVPR, 2019*. [[Paper](
https://arxiv.org/pdf/1901.05103.pdf)] [[Pytorch Code](https://github.com/facebookresearch/DeepSDF)]

* **Occupancy networks**: " Learning 3d reconstruction in function space", *CVPR, 2019*. [[Paper](https://arxiv.org/pdf/1812.03828.pdf)] [[Website](https://avg.is.mpg.de/publications/occupancy-networks)]

---
## Physics
* **DANOs**: "Differentiable Physics Simulation of Dynamics-Augmented Neural Objects", *arXiv*. [[Paper](https://arxiv.org/abs/2210.09420)] [[Video](https://youtu.be/Md0PM-wv_Xg)]

* **PAC-NeRF**: "Physics Augmented Continuum Neural Radiance Fields for Geometry-Agnostic System Identification", *ICLR, 23*. [[Paper](https://openreview.net/pdf?id=tVkrbkz42vc)] [[Website](https://sites.google.com/view/PAC-NeRF)] [[Video](https://youtu.be/Md0PM-wv_Xg)] [[Pytorch Code](https://github.com/xuan-li/PAC-NeRF)]

* **NeuPhysics**: "Editable Neural Geometry and Physics from Monocular Videos", *Neurips, 2022*. [[Paper](https://arxiv.org/abs/2210.12352)] [[Pytorch Code](https://github.com/gaoalexander/neuphysics)] [[Website](https://ylqiao.net/publication/2022nerf/)]

* **NeRF-ysics**: "A Differentiable Pipeline for Enriching NeRF-Represented Objects with Dynamical Properties", *ICRA Workshop, 2022*. [[Paper](https://neural-implicit-workshop.stanford.edu/assets/pdf/lecleach.pdf)]

* "Neural Implicit Representations for Physical Parameter Inference from a Single Video", *WACV, 2023*. [[Paper](https://arxiv.org/pdf/2204.14030.pdf)] [[Pytorch Code](https://github.com/florianHofherr/PhysParamInference)] [[Website](https://florianhofherr.github.io/phys-param-inference/)]

* **NeuroFluid**: "Fluid Dynamics Grounding with Particle-Driven Neural Radiance Fields", *ICML, 2022*. [[Paper](https://proceedings.mlr.press/v162/guan22a/guan22a.pdf)] [[Pytorch Code](https://github.com/syguan96/NeuroFluid)]

---
## Planning/Navigation
* **NeRFlow**: "Neural Radiance Flow for 4D View Synthesis and Video Processing", *ICCV, 2021*. [[Paper](https://arxiv.org/abs/2012.09790)] [[Pytorch Code](https://github.com/yilundu/nerflow)] [[Website](https://yilundu.github.io/nerflow/)] 

* **NeRF-Navigation**: "Vision-Only Robot Navigation in a Neural Radiance World", *ICRA, 2022*. [[Paper](https://mikh3x4.github.io/nerf-navigation/assets/NeRF_Navigation.pdf)] [[Pytorch Code](https://github.com/mikh3x4/nerf-navigation)] [[Website](https://mikh3x4.github.io/nerf-navigation/)] 

* **RNR-Map**: "Renderable Neural Radiance Map for Visual Navigation", *CVPR, 2023*. [[Paper](https://arxiv.org/pdf/2303.00304.pdf)] [[Website](https://obin-hero.github.io/RNRmap/)] 

* "Uncertainty Guided Policy for Active Robotic 3D Reconstruction using Neural Radiance Fields", *RAL, 2022*. [[Paper (https://arxiv.org/pdf/2209.08409.pdf)] [[Website](https://www.vis.xyz/pub/robotic-3d-scan-with-nerf/)] 

* **NeRF-dy**: "3D Neural Scene Representations for Visuomotor Control", *CORL, 2021*. [[Paper](https://arxiv.org/abs/2107.04004)] [[Website](https://3d-representation-learning.github.io/nerf-dy/)] 

* **CompNeRFdyn**: "Learning Multi-Object Dynamics with Compositional Neural Radiance Fields", *arXiv*. [[Paper](https://arxiv.org/pdf/2202.11855.pdf)] [[Website](https://dannydriess.github.io/compnerfdyn/)] 

* **PIFO**: "Deep Visual Constraints: Neural Implicit Models for Manipulation Planning from Visual Input", *arXiv*. [[Paper](https://arxiv.org/pdf/2112.04812.pdf)] [[Website](https://sites.google.com/view/deep-visual-constraints)] 

* "Learning Continuous Environment Fields via Implicit Functions", *ICLR, 2022*. [[Paper](https://arxiv.org/pdf/2111.13997.pdf)] [[Website](https://research.nvidia.com/publication/2022-04_learning-continuous-environment-fields-implicit-functions)] 

* "Learning Barrier Functions with Memory for Robust Safe Navigation", *RA-L, 2021*. [[Paper](https://arxiv.org/pdf/2011.01899.pdf)]

* **RedSDF**: "Regularized Deep Signed Distance Fields for Reactive Motion Generation", *IROS, 2022*. [[Paper](https://arxiv.org/abs/2203.04739)] [[Website](https://irosalab.com/2022/02/28/redsdf/)] 

* **AutoNeRF**: "Training Implicit Scene Representations with Autonomous Agents", *arxiv*. [[Paper](https://arxiv.org/pdf/2304.11241.pdf)] [[Website](https://pierremarza.github.io/projects/autonerf/)]

* **ESDF**: "Sampling-free obstacle gradients and reactive planning in Neural Radiance Fields", *arXiv*. [[Paper](https://arxiv.org/abs/2205.01389)]

* **CLIP-Fields**: "Open-label semantic navigation with pre-trained VLMs and language models", *arxiv*. [[Paper](https://arxiv.org/abs/2210.05663)] [[Pytorch Code and Tutorials](https://github.com/notmahi/clip-fields)] [[Website](https://mahis.life/clip-fields/)]

* **Voxfield**: Non-Projective Signed Distance Fields for Online Planning and 3D Reconstruction", *IROS, 2022*. [[Paper](https://www.ipb.uni-bonn.de/wp-content/papercite-data/pdf/pan2022iros.pdf)] [[Pytorch Code](https://github.com/VIS4ROB-lab/voxfield)]

* **Voxblox**: Incremental 3D Euclidean Signed Distance Fields for On-Board MAV Planning, *IROS, 2017*. [[Paper](https://arxiv.org/pdf/1611.03631.pdf)]

* **NFOMP**: Neural Field for Optimal Motion Planner of Differential Drive Robots With Nonholonomic Constraints", *RA-L, 2022*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9851532)] [[Video](https://youtu.be/beEfEOmxJfM)]

* **CATNIPS**: Collision Avoidance Through Neural Implicit Probabilistic Scenes", *arXiv*. [[Paper](https://arxiv.org/pdf/2302.12931.pdf)] 

* **MeSLAM**: Memory Efficient SLAM based on Neural Fields, *IEEE SMC, 2022*. [[Paper](https://arxiv.org/pdf/2209.09357.pdf)] 

* **NTFields**: "Neural Time Fields for Physics-Informed Robot Motion Planning", *ICLR, 2023*. [[Paper](https://arxiv.org/pdf/2210.00120.pdf)]

* "Real-time Semantic 3D Reconstruction for High-Touch Surface Recognition for Robotic Disinfection", *IROS, 2022*. [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9981300)] 

* **NeurAR**: "Neural Uncertainty for Autonomous 3D Reconstruction", *RA-L, 2023*. [[Paper](https://arxiv.org/pdf/2207.10985.pdf)] 

* **IR-MCL**: "Implicit Representation-Based Online Global Localization", *RA-L, 2023*. [[Paper](https://arxiv.org/pdf/2210.03113.pdf)] [[Pytorch Code](https://github.com/PRBonn/ir-mcl)] 

* **360Roam**: "Real-Time Indoor Roaming Using Geometry-Aware 360◦ Radiance Fields", *arXiv*. [[Paper](https://arxiv.org/pdf/2208.02705.pdf)] [[Pytorch Code](https://github.com/PRBonn/ir-mcl)] 

* "Learning Deep SDF Maps Online for Robot Navigation and Exploration", *arXiv*. [[Paper](https://arxiv.org/pdf/2207.10782.pdf)]

* **DroNeRF**: Real-time Multi-agent Drone Pose Optimization for Computing Neural Radiance Fields. [[Paper](https://arxiv.org/pdf/2303.04322.pdf)]

* "Enforcing safety for vision-based controllers via Control Barrier Functions and Neural Radiance Fields", *arXiv*. [[Paper](https://arxiv.org/pdf/2209.12266.pdf)]

* "Full-Body Visual Self-Modeling of Robot Morphologies", *arXiv*. [[Paper](https://arxiv.org/abs/2205.01389)] [[Website](https://huajianup.github.io/research/360Roam/)]

* "Efficient View Path Planning for Autonomous Implicit Reconstruction", *arxiv*. [[Paper](https://arxiv.org/abs/2210.05129)]

* "Multi-Object Navigation with dynamically learned neural implicit representations", *arxiv*. [[Paper](https://arxiv.org/pdf/2209.13159.pdf)] [[Website](https://small-zeng.github.io/EVPP/)

----
## Citation
If you find this repository useful, please consider citing this list:
```
@misc{irshad2022implicitnerfroboticsresources,
    title = {Awesome Implicit NeRF Robotics - A curated list of resources on implicit neural representations and nerf relating to robotics},
    author = {Muhammad Zubair Irshad},
    journal = {GitHub repository},
    url = {https://github.com/zubair-irshad/Awesome-Implicit-NeRF-Robotics},
    DOI= {10.5281/ZENODO.7552613}
    year = {2022},
}
```
