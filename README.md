# Awesome-Synthetic-Data-for-Perception-Task [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <!-- omit in toc -->
This repository contains a collection of resources and papers on **Awesome-Synthetic-Data-for-Perception-Task**.

<p align="center">
<img src="./assets/out-1.gif" width="600px"/>   
</p>

<p align="center">
<img src="./assets/1681826106888.jpg" width="600px"/>   
</p>

<p align="center">
(Source: <a href="https://arxiv.org/abs/2001.10773">Virtual kitti 2</a>, <a href="https://weijiawu.github.io/DiffusionMask/">DiffuMask</a>)
</p>


## :paintbrush: Table of Contents <!-- omit in toc -->
- [Survey](#Survey)
- [3D Virtual Engine](#3D-Virtual)
- [Classification Task](#Classification-Task)
- [Face Recognition](#Face-Recognition)
- [Scene Text Detection & Recognition](#Scene-Text)
- [Semantic Segmentation](#Semantic-Segmentation)
- [Instance Segmentation](#Instance-Segmentation)
- [Object Detection](#Object-Detection)
- [3D Human Pose](#3D-Human-Pose)
- [Pose](#Pose)
- [Depth Estimation Task](#Depth-Estimation-Task)
- [Open Pose Task](#Open-Pose-Task)
- [Referring Segmentation Task](#Referring-Segmentation)
- [Medical Image](#Medical-Image)





### Survey
+ [A survey on generative adversarial networks for imbalance problems in computer vision tasks](https://journalofbigdata.springeropen.com/articles/10.1186/s40537-021-00414-0)(Journal of Big Data 2021)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://journalofbigdata.springeropen.com/articles/10.1186/s40537-021-00414-0) 



### Classification Task

+ [Positive-Unlabeled Learning with Adversarial Data Augmentation for Knowledge Graph Completion](https://arxiv.org/abs/2205.00904)(IJCAI 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2205.00904) 

+ [RareGAN: Generating Samples for Rare Classes](https://arxiv.org/abs/2203.10674)(AAAI 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.10674) 

+ [Data Augmentation in High Dimensional Low Sample Size Setting Using a Geometry-Based Variational Autoencoder](https://ieeexplore.ieee.org/abstract/document/9806307/)(TPAMI 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ieeexplore.ieee.org/abstract/document/9806307/) 

+ [Deep Generative Mixture Model for Robust Imbalance Classification](https://ieeexplore.ieee.org/abstract/document/9806307/)(TPAMI 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ieeexplore.ieee.org/document/9785970/) 

+ [Do Deep Networks Transfer Invariances Across Classes?](https://arxiv.org/abs/2203.09739)(ICLR 2022)
  [![Star](https://img.shields.io/github/stars/IBM/BAGAN.svg?style=social&label=Star)](https://github.com/AllanYangZhou/generative-invariance-transfer?utm_source=catalyzex.com)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2203.09739) 



+ [BAGAN: Data Augmentation with Balancing GAN](https://arxiv.org/abs/1803.09655)(Mar 2018)
  [![Star](https://img.shields.io/github/stars/IBM/BAGAN.svg?style=social&label=Star)](https://github.com/CVMI-Lab/SyntheticData?utm_source=catalyzex.com)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1803.09655) 

+ [Deep Synthetic Noise Generation for RGB-D Data Augmentation](https://www.semanticscholar.org/paper/Deep-Synthetic-Noise-Generation-for-RGB-D-Data-Hammond/e9607b30ab4ce1d466bb7ce6df2de6d0b28fa680)(Mar 2019)
  [![Star](https://img.shields.io/github/stars/pdhhammond/deep-noise-generation.svg?style=social&label=Star)](https://github.com/CVMI-Lab/SyntheticData?utm_source=catalyzex.com)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://www.semanticscholar.org/paper/Deep-Synthetic-Noise-Generation-for-RGB-D-Data-Hammond/e9607b30ab4ce1d466bb7ce6df2de6d0b28fa680) 



+ [Efficient Augmentation for Imbalanced Deep Learning](https://arxiv.org/abs/2304.10253)(Mon, 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2207.06080) 


+ [A data augmentation perspective on diffusion models and retrieva](https://arxiv.org/abs/2304.10253)(Apr, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.10253) 


+ [Synthetic Data from Diffusion Models Improves ImageNet Classification](https://arxiv.org/abs/2304.08466)(Apr, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.08466) 

+ [Is synthetic data from generative models ready for image recognition?](https://arxiv.org/abs/2210.07574)(ICLR 2023, Spotlight)
  [![Star](https://img.shields.io/github/stars/CVMI-Lab/SyntheticData.svg?style=social&label=Star)](https://github.com/CVMI-Lab/SyntheticData?utm_source=catalyzex.com)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.07574) 

+ [Diversity is Definitely Needed: Improving Model-Agnostic Zero-shot Classification via Stable Diffusion](https://arxiv.org/abs/2302.03298)(Apr 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.03298) 

+ [Diffusion Models and Semi-Supervised Learners Benefit Mutually with Few Labels](https://arxiv.org/abs/2302.03298)(Apr 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2302.10586.pdf) 

+ [Diversity is Definitely Needed: Improving Model-Agnostic Zero-shot Classification via Stable Diffusion](https://arxiv.org/pdf/2302.03298)(Apr 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2302.03298) 

+ [Exploring Incompatible Knowledge Transfer in Few-shot Image Generation](https://github.com/yunqing-me/RICK)(CVPR 2023)
  [![Star](https://img.shields.io/github/stars/yunqing-me/RICK.svg?style=social&label=Star)](https://github.com/yunqing-me/RICK)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2302.03298) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yunqing-me.github.io/RICK/)

+ [Accelerating dataset distillation via model augmentation](https://arxiv.org/pdf/2212.06152.pdf)(December 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2212.06152.pdf) 

### 3D Human Pose
+ [Monocular 3D Human Pose Estimation for Sports Broadcasts using Partial Sports Field Registration](https://arxiv.org/pdf/2304.04437)(CVPR 2023)
  [![Star](https://img.shields.io/github/stars/tobibaum/PartialSportsFieldReg_3DHPE.svg?style=social&label=Star)]
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2304.04437) 


### Semantic Segmentation

+ [DiffuMask: Synthesizing Images with Pixel-level Annotations for Semantic Segmentation Using Diffusion Models](https://arxiv.org/abs/2303.11681)(Mar 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.11681) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://weijiawu.github.io/DiffusionMask/)

+ [Guiding Text-to-Image Diffusion Model Towards Grounded Generation](https://arxiv.org/abs/2301.05221)(Jan 2023)
  [![Star](https://img.shields.io/github/stars/Lipurple/Grounded-Diffusion.svg?style=social&label=Star)]
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.05221) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://lipurple.github.io/Grounded_Diffusion/)


+ [HandsOff: Labeled Dataset Generation With No Additional Human Annotations](https://openreview.net/pdf?id=gcpD-9_eOIL)(NeurIPS 2022 Workshop)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openreview.net/pdf?id=gcpD-9_eOIL) 

+ [DatasetGAN: Efficient Labeled Data Factory with Minimal Human Effort](https://nv-tlabs.github.io/big-datasetgan/resources/paper.pdf)(CVPR 2021 oral)
  [![Star](https://img.shields.io/github/stars/nv-tlabs/datasetGAN_release.svg?style=social&label=Star)]
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2104.06490) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://nv-tlabs.github.io/datasetGAN/)

### Instance Segmentation

+ [BigDatasetGAN: Synthesizing ImageNet with Pixel-wise Annotations](https://nv-tlabs.github.io/big-datasetgan/resources/paper.pdf)(CVPR 2022)
  [![Star](https://img.shields.io/github/stars/nv-tlabs/bigdatasetgan_code.svg?style=social&label=Star)](https://github.com/nv-tlabs/bigdatasetgan_code)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2201.04684) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://nv-tlabs.github.io/big-datasetgan/?utm_source=catalyzex.com)









### Object Detection
+ [CrowdSim2: an Open Synthetic Benchmark for Object Detectors](https://arxiv.org/pdf/2304.05090.pdf)(the 18th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications, 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2304.05090.pdf) 


+ [X-Paste: Revisit Copy-Paste at Scale with CLIP and StableDiffusion](https://arxiv.org/abs/2212.03863)(Dec, 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.03863)


+ [DALL-E for Detection: Language-driven Compositional Image Synthesis for Object Detection](https://arxiv.org/pdf/2206.09592.pdf)(Dec, 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2206.09592.pdf)

+ [Neural-Sim: Learning to Generate Training Data with NeRF](https://arxiv.org/pdf/2207.11368.pdf)(ECCV, 2022)
  [![Star](https://img.shields.io/github/stars/gyhandy/Neural-Sim-NeRF?style=social&label=Star)](https://github.com/gyhandy/Neural-Sim-NeRF)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2207.11368.pdf)

+ [EM-Paste: EM-guided Cut-Paste with DALL-E Augmentation for Image-level Weakly Supervised Instance Segmentation](https://arxiv.org/abs/2212.07629)(Dec, 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.07629)






### Face Recognition
+ [DCFace: Synthetic Face Generation with Dual Condition Diffusion Model](https://arxiv.org/pdf/2304.07060.pdf)(CVPR 2023)
  [![Star](https://img.shields.io/github/stars/mk-minchul/dcface.svg?style=social&label=Star)]
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2304.07060.pdf) 

+ [SynthASpoof: Developing Face Presentation Attack Detection Based on Privacy-friendly Synthetic Data](https://arxiv.org/pdf/2303.02660)(CVPR 2023 workshop)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2303.02660) 




### Instance Segmentation
+ [HaDR: Applying Domain Randomization for Generating Synthetic Multimodal Dataset for Hand Instance Segmentation in Cluttered Industrial Environments](https://arxiv.org/pdf/2304.05826)(April 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2304.05826.pdf) 


### 3D Virtual Engine 

+ [Virtual kitti 2](https://arxiv.org/abs/2001.10773)(Apr., 2023)  
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2001.10773) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://europe.naverlabs.com/research/computer-vision/proxy-virtual-worlds-vkitti-2/)


### Medical Image

+ [Brain PET Synthesis from MRI Using Joint Probability Distribution of Diffusion Model at Ultrahigh Fields](https://arxiv.org/pdf/2211.08901.pdf)(November 2022)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2211.08901.pdf) 


+ [Distributed Conditional GAN (discGAN) For Synthetic Healthcare Data Generation](https://arxiv.org/pdf/2304.04290.pdf)(April 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2304.04290.pdf) 

+ [MedGen3D: A Deep Generative Framework for Paired 3D Image and Mask Generation](https://arxiv.org/pdf/2304.04106)(MICCAI 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2304.04106) 


+ [Zero-shot CT Field-of-view Completion with Unconditional Generative Diffusion Prior](https://arxiv.org/pdf/2304.03760)(MIDL 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2304.03760) 


### Pose
+ [Pose Augmentation: Class-agnostic Object Pose Transformation for Object Recognition](https://arxiv.org/pdf/2304.03760)(ECCV 2020)
  [![Star](https://img.shields.io/github/stars/gyhandy/Pose-Augmentation?style=social&label=Star)](https://github.com/gyhandy/Pose-Augmentation?utm_source=catalyzex.com)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2003.08526.pdf) 

+ [StyleGAN-Human: A Data-Centric Odyssey of Human Generation](https://arxiv.org/abs/2204.11823)(ECCV 2020)
  [![Star](https://img.shields.io/github/stars/stylegan-human/StyleGAN-Human?style=social&label=Star)](https://github.com/stylegan-human/StyleGAN-Human)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2204.11823) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://stylegan-human.github.io/)




## :paintbrush: Others for Diffusion Model <!-- omit in toc -->
- [Image Generation](#image)
- [3D Generation](#3D-Generation)
- [3D Editing](#3D-Editing)
- [Reinforcement Learning with Human Feedback](#Reinforcement-Learning-with-Human-Feedback)

### 3D Editing


+ [SPIn-NeRF: Multiview Segmentation and Perceptual Inpainting with Neural Radiance Fields](https://arxiv.org/pdf/2211.12254.pdf)(CVPR 2022)
  [![Star](https://img.shields.io/github/stars/SamsungLabs/SPIn-NeRF?style=social&label=Star)](https://github.com/SamsungLabs/SPIn-NeRF)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2211.12254.pdf) 
  [![Website](https://img.shields.io/badge/Website-9cf)](https://spinnerf3d.github.io/)


### Reinforcement Learning with Human Feedback

+ [Better Aligning Text-to-Image Models with Human Preference](https://arxiv.org/abs/2303.14420)(Mar 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14420) 


+ [RAFT: Reward rAnked FineTuning for Generative Foundation Model Alignment](https://arxiv.org/abs/2304.06767)(Apr 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.06767) 

+ [Aligning Text-to-Image Models using Human Feedback](https://arxiv.org/pdf/2302.12192.pdf)(Apr 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2302.12192.pdf) 

+ [ImageReward: Learning and Evaluating Human Preferences for Text-to-Image Generation](https://arxiv.org/abs/2304.05977)(Thu 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.05977) 


