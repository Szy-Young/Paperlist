# Point Cloud Understanding

## Basic architecture

[ICLR22 PointMLP](https://arxiv.org/abs/2202.07123)
Rethinking Network Design and Local Geometry in Point Cloud: A Simple Residual MLP Framework

[CVPR17 PointSetGeneration](https://openaccess.thecvf.com/content_cvpr_2017/papers/Fan_A_Point_Set_CVPR_2017_paper.pdf)
A Point Set Generation Network for 3D Object Reconstruction from a Single Image

## Instance segmentation

[CVPR19 GSPN](https://openaccess.thecvf.com/content_CVPR_2019/html/Yi_GSPN_Generative_Shape_Proposal_Network_for_3D_Instance_Segmentation_in_CVPR_2019_paper.html)
GSPN: Generative Shape Proposal Network for 3D Instance Segmentation in Point Cloud

## Scene flow

[NIPS21](https://proceedings.neurips.cc/paper/2021/hash/41263b9a46f6f8f22668476661614478-Abstract.html)
Neural Scene Flow Prior

[CVPR21 Flowstep3D](https://openaccess.thecvf.com/content/CVPR2021/html/Kittenplon_FlowStep3D_Model_Unrolling_for_Self-Supervised_Scene_Flow_Estimation_CVPR_2021_paper.html)
FlowStep3D: Model Unrolling for Self-Supervised Scene Flow Estimation

<br/>

# Image Understanding

## Instance segmentation

[21 Mask2Former](https://arxiv.org/abs/2112.01527)
Masked-attention Mask Transformer for Universal Image Segmentation

[NIPS21 MaskFormer](https://arxiv.org/abs/2107.06278)
Per-Pixel Classification is Not All You Need for Semantic Segmentation

[NIPS21 K-Net](https://proceedings.neurips.cc/paper/2021/hash/55a7cf9c71f1c9c495413f934dd1a158-Abstract.html)
K-Net: Towards Unified Image Segmentation

<br/>

# Motion Segmentation

## Layered models

[CVPR17 MR-Flow](https://openaccess.thecvf.com/content_cvpr_2017/papers/Wulff_Optical_Flow_in_CVPR_2017_paper.pdf)
Optical Flow in Mostly Rigid Scenes

[CVPR16 SOF](https://openaccess.thecvf.com/content_cvpr_2016/html/Sevilla-Lara_Optical_Flow_With_CVPR_2016_paper.html)
Optical Flow With Semantic Segmentation and Localized Layers

[CVPR13 FC-2Layers](https://openaccess.thecvf.com/content_cvpr_2013/html/Sun_A_Fully-Connected_Layered_2013_CVPR_paper.html)
A Fully-Connected Layered Model of Foreground and Background Flow

[CVPR12 nLayers](https://cs.brown.edu/people/dqsun/pubs/cvpr_2012_layer.pdf)
Layered segmentation and optical flow estimation over time

[NIPS10 Layers++](https://proceedings.neurips.cc/paper/2010/hash/f7664060cc52bc6f3d620bcedc94a4b6-Abstract.html)
Layered Image Motion with Explicit Occlusions, Temporal Consistency, and Depth Ordering

## Robotics-related

[22](https://arxiv.org/abs/2201.04501)
Automatic Labeling to Generate Training Data for Online LiDAR-based Moving Object Segmentation

[RAL21 LMNet](https://arxiv.org/abs/2105.08971)
Moving object segmentation in 3D LiDAR data: A learning-based approach exploiting sequential data

[IROS19 SelfDeepMask](https://arxiv.org/abs/2005.09484)
Self-supervised Transfer Learning for Instance Segmentation through Physical Interaction

<br/>

# Representation Learning

## Learning by compression

[21](https://www.stat.cmu.edu/~ryantibs/papers/sparsitynn.pdf)
Equivalences Between Sparse Models and Neural Networks

[NIPS20 MCR2](https://arxiv.org/abs/2006.08558)
Learning Diverse and Discriminative Representations via the Principle of Maximal Coding Rate Reduction

[00 Information bottleneck](https://arxiv.org/abs/physics/0004057)
The information bottleneck method

## Contrastive learning

[3DV21 PoseContrast](https://ieeexplore.ieee.org/abstract/document/9665831)
PoseContrast: Class-Agnostic Object Viewpoint Estimation in the Wild with Pose-Aware Contrastive Learning

[ICCV21 DepthContrast](https://openaccess.thecvf.com/content/ICCV2021/html/Zhang_Self-Supervised_Pretraining_of_3D_Features_on_Any_Point-Cloud_ICCV_2021_paper.html)
Self-Supervised Pretraining of 3D Features on Any Point-Cloud

[CVPR21 ContrastiveSceneContexts](https://openaccess.thecvf.com/content/CVPR2021/html/Hou_Exploring_Data-Efficient_3D_Scene_Understanding_With_Contrastive_Scene_Contexts_CVPR_2021_paper.html)
Exploring Data-Efficient 3D Scene Understanding With Contrastive Scene Contexts

[NIPS20 InfoMin](https://proceedings.neurips.cc/paper/2020/hash/4c2e5eaae9152079b9e95845750bb9ab-Abstract.html)
What Makes for Good Views for Contrastive Learning?

[ECCV20 PointContrast](https://arxiv.org/abs/2007.10985)
PointContrast: Unsupervised Pre-training for 3D Point Cloud Understanding

## Object-centric learning / Unsupervised segmentation

[21 PPD](https://arxiv.org/abs/2110.04411)
Unsupervised Pose-Aware Part Decomposition for 3D Articulated Objects

[NIPS21 SIMONe](https://proceedings.neurips.cc/paper/2021/hash/a860a7886d7c7e2a8d3eaac96f76dc0d-Abstract.html)
SIMONe: View-Invariant, Temporally-Abstracted Object Representations via Unsupervised Video Decomposition

[ICCV21 InSeGAN](https://openaccess.thecvf.com/content/ICCV2021/html/Cherian_InSeGAN_A_Generative_Approach_to_Segmenting_Identical_Instances_in_Depth_ICCV_2021_paper.html)
InSeGAN: A Generative Approach to Segmenting Identical Instances in Depth Images

[NIPS20 MulMON](https://proceedings.neurips.cc/paper/2020/hash/3d9dabe52805a1ea21864b09f3397593-Abstract.html)
Learning Object-Centric Representations of Multi-Object Scenes from Multiple View

[ICLR20 Genesis](https://arxiv.org/abs/1907.13052)
GENESIS: Generative Scene Inference and Sampling with Object-Centric Latent Representations

[ICCV19 BAE-Net](https://openaccess.thecvf.com/content_ICCV_2019/html/Chen_BAE-NET_Branched_Autoencoder_for_Shape_Co-Segmentation_ICCV_2019_paper.html)
BAE-NET: Branched Autoencoder for Shape Co-Segmentation

<br/>
