# Awesome-Foundation-Model-Based-Depth

## 📖 Introduction

Welcome to the GitHub repository for Awesome-Foundation-Depth!
This repository is a curated collection of cutting-edge research, tools, and datasets dedicated to **Depth Estimation** and **Depth Completion leveraging Foundation Models (FMs)**. We aim to provide a systematic and up-to-date overview of how large-scale pre-trained models are revolutionizing geometric vision.

## 🚀 Key Features

- **Comprehensive Depth Estimation Survey**: A categorized collection of papers focusing on depth foundation models, further distinguished by their underlying paradigms: Discriminative Models (e.g., ViT-based backbones) and Generative Models (e.g., Diffusion-based synthesis).
- **Advanced Depth Completion Research**: A specialized track for depth completion methods that utilize the powerful priors of FMs to recover dense geometry from sparse inputs.
- **New Taxonomy**: We propose a novel taxonomy to categorize recent FM-based depth completion methods, providing a clearer framework for understanding the current state-of-the-art and future directions.

```
Taxonomy
├── Architectural Revision & Fine-tuning
  ├──MDE-Centric Fine-Tuning
  ├──DC-Centric Fine-Tuning
├── Knowledge Distillation
  ├──Label-Efficient Supervision
  ├──Fine-Grained Distillation
├── Test-time Adaptation
  ├──Latent Variable Optimization
  ├──Parameter-Efficient Test-Time Tuning
└── Explicit Output Calibration
```

## 💪 How to Contribute

We will continue to update this list with the latest resources. If you find any missed resources (paper/code) or errors, please **feel free to open an issue**.

## ✨ Monocular Depth Estimation

The collection includes depth foundation models, methods that adapt pretrained models, and earlier context papers. Video and stereo-guided methods are listed separately.

<a id="discriminative-model"></a>

### 🏷️ Discriminative Model

- [Ma2026] MetricAnything: Scaling Metric Depth Pretraining with Noisy Heterogeneous Sources in *ECCV*, 2026. [\[paper\]](https://arxiv.org/abs/2601.22054) [\[code\]](https://github.com/metric-anything/metric-anything)
- [Lin2026] Depth Anything 3: Recovering the Visual Space from Any Views in *ICLR*, 2026. [\[paper\]](https://arxiv.org/abs/2511.10647) [\[code\]](https://github.com/ByteDance-Seed/Depth-Anything-3)
- [Fang2026] Dens3R: A Foundation Model for 3D Geometry Prediction in *ICLR*, 2026. [\[paper\]](https://arxiv.org/abs/2507.16290) [\[code\]](https://github.com/G-1nOnly/Dens3R)
- [Bochkovskii2025] Depth Pro: Sharp Monocular Metric Depth in Less Than a Second in *ICLR*, 2025. [\[paper\]](https://openreview.net/forum?id=aueXfY0Clv) [\[code\]](https://github.com/apple-aiml-research/ml-depth-pro)
- [Piccinelli2025] UniK3D: Universal Camera Monocular 3D Estimation in *CVPR*, 2025. [\[paper\]](https://arxiv.org/abs/2503.16591) [\[code\]](https://github.com/lpiccinelli-eth/UniK3D)
- [Guo2025] Depth Any Camera: Zero-Shot Metric Depth Estimation from Any Camera in *CVPR*, 2025. [\[paper\]](https://arxiv.org/abs/2501.02464) [\[code\]](https://github.com/yuliangguo/depth_any_camera)
- [Wang2025] Jasmine: Harnessing Diffusion Prior for Self-supervised Depth Estimation in *NeurIPS*, 2025. [\[paper\]](https://arxiv.org/abs/2503.15905) [\[code\]](https://github.com/wangjiyuan9/jasmine)
- [Wang2025] MoGe-2: Accurate Monocular Geometry with Metric Scale and Sharp Details in *arXiv*, 2025. [\[paper\]](https://arxiv.org/abs/2507.02546) [\[code\]](https://github.com/microsoft/moge)
- [Wang2025] MoGe: Unlocking Accurate Monocular Geometry Estimation for Open-Domain Images with Optimal Training Supervision in *CVPR*, 2025. [\[paper\]](https://arxiv.org/abs/2410.19115) [\[code\]](https://github.com/microsoft/moge)
- [Wang2025] VGGT: Visual Geometry Grounded Transformer in *CVPR*, 2025. 👍*CVPR Best Paper*. [\[paper\]](https://arxiv.org/abs/2503.11651) [\[code\]](https://github.com/facebookresearch/vggt)
- [Piccinelli2025] UniDepthV2: Universal Monocular Metric Depth Estimation Made Simpler in *IEEE TPAMI*, 2025 (early access; volume publication: 2026). [\[paper\]](https://arxiv.org/pdf/2502.20110) [\[code\]](https://github.com/lpiccinelli-eth/UniDepth)
- [Li2024] PatchFusion: An End-to-End Tile-Based Framework for High-Resolution Monocular Metric Depth Estimation in *CVPR*, 2024. [\[paper\]](https://arxiv.org/abs/2312.02284) [\[code\]](https://github.com/zhyever/PatchFusion)
- [Patni2024] ECoDepth: Effective Conditioning of Diffusion Models for Monocular Depth Estimation in *CVPR*, 2024. [\[paper\]](https://arxiv.org/abs/2403.18807) [\[code\]](https://github.com/Aradhye2002/EcoDepth)
- [Piccinelli2024] UniDepth: Universal Monocular Metric Depth Estimation in *CVPR*, 2024. [\[paper\]](https://openaccess.thecvf.com/content/CVPR2024/papers/Piccinelli_UniDepth_Universal_Monocular_Metric_Depth_Estimation_CVPR_2024_paper.pdf) [\[code\]](https://github.com/lpiccinelli-eth/UniDepth)
- [Wang2024] DUSt3R: Geometric 3D Vision Made Easy in *CVPR*, 2024. [\[paper\]](https://arxiv.org/abs/2312.14132) [\[code\]](https://github.com/naver/dust3r)
- [Yang2024] Depth Anything: Unleashing the Power of Large-Scale Unlabeled Data in *CVPR*, 2024. [\[paper\]](https://arxiv.org/abs/2401.10891) [\[code\]](https://github.com/LiheYoung/Depth-Anything)
- [Yang2024] Depth Anything V2 in *NeurIPS*, 2024. [\[paper\]](https://arxiv.org/abs/2406.09414) [\[code\]](https://github.com/DepthAnything/Depth-Anything-V2)
- [Hu2024] Metric3Dv2: A Versatile Monocular Geometric Foundation Model for Zero-shot Metric Depth and Surface Normal Estimation in *IEEE TPAMI*, 2024. [\[paper\]](https://arxiv.org/abs/2404.15506) [\[code\]](https://github.com/YvanYin/Metric3D)
- [Liu2024] Mono-ViFI: A Unified Learning Framework for Self-supervised Single- and Multi-frame Monocular Depth Estimation in *ECCV*, 2024. [\[paper\]](https://arxiv.org/abs/2407.14126) [\[code\]](https://github.com/LiuJF1226/Mono-ViFI)
- [Li2024] PatchRefiner: Leveraging Synthetic Data for Real-Domain High-Resolution Monocular Metric Depth Estimation in *ECCV*, 2024. [\[paper\]](https://arxiv.org/abs/2406.06679) [\[code\]](https://github.com/zhyever/PatchRefiner)
- [Han2024] High-Precision Self-Supervised Monocular Depth Estimation with Rich-Resource Prior in *ECCV*, 2024. [\[paper\]](https://arxiv.org/abs/2408.00361) [\[code\]](https://github.com/wencheng256/RPrDepth)
- [Zhao2023] Unleashing Text-to-Image Diffusion Models for Visual Perception in *ICCV*, 2023. [\[paper\]](https://arxiv.org/abs/2303.02153) [\[code\]](https://github.com/wl-zhao/VPD)
- [Bhat2023] ZoeDepth: Zero-shot Transfer by Combining Relative and Metric Depth in *arXiv*, 2023. [\[paper\]](https://arxiv.org/abs/2302.12288) [\[code\]](https://github.com/isl-org/ZoeDepth)
- [Guizilini2023] Towards Zero-Shot Scale-Aware Monocular Depth Estimation in *ICCV*, 2023. [\[paper\]](https://openaccess.thecvf.com/content/ICCV2023/papers/Guizilini_Towards_Zero-Shot_Scale-Aware_Monocular_Depth_Estimation_ICCV_2023_paper.pdf) [\[code\]](https://github.com/tri-ml/vidar)
- [Yin2023] Metric3D: Towards Zero-shot Metric 3D Prediction from A Single Image in *ICCV*, 2023. [\[paper\]](https://arxiv.org/abs/2307.10984) [\[code\]](https://github.com/YvanYin/Metric3D)
- [Zhang2022] Hierarchical Normalization for Robust Monocular Depth Estimation in *NeurIPS*, 2022. [\[paper\]](https://arxiv.org/abs/2210.09670) [\[code\]](https://github.com/icoz69/HDN)
- [Ranftl2021] Vision Transformers for Dense Prediction in *ICCV*, 2021. [\[paper\]](https://openaccess.thecvf.com/content/ICCV2021/papers/Ranftl_Vision_Transformers_for_Dense_Prediction_ICCV_2021_paper.pdf) [\[code\]](https://github.com/isl-org/DPT)
- [Yin2020] DiverseDepth: Affine-invariant Depth Prediction Using Diverse Data in *arXiv*, 2020. [\[paper\]](https://arxiv.org/abs/2002.00569) [\[code\]](https://github.com/YvanYin/DiverseDepth)
- [Ranftl2020] Towards Robust Monocular Depth Estimation: Mixing Datasets for Zero-shot Cross-dataset Transfer in *IEEE TPAMI*, 2020. [\[paper\]](https://ieeexplore.ieee.org/document/9178977) [\[code\]](https://github.com/isl-org/MiDaS)
- [Li2018] MegaDepth: Learning Single-View Depth Prediction from Internet Photos in *CVPR*, 2018. [\[paper\]](https://openaccess.thecvf.com/content_cvpr_2018/html/Li_MegaDepth_Learning_Single-View_CVPR_2018_paper.html) [\[code\]](https://github.com/zhengqili/MegaDepth)

### 🏷️ Generative Model

Includes diffusion/flow-based depth prediction and deterministic adaptations of generative models.

- [Song2026] DepthMaster: Taming Diffusion Models for Monocular Depth Estimation in *IEEE TCSVT*, 2026. [\[paper\]](https://doi.org/10.1109/TCSVT.2026.3681436) [\[code\]](https://github.com/indu1ge/DepthMaster)
- [Xu2025] What Matters When Repurposing Diffusion Models for General Dense Perception Tasks? in *ICLR*, 2025. [\[paper\]](https://proceedings.iclr.cc/paper_files/paper/2025/hash/13b8d8fb8d05369480c2c344f2ce3f25-Abstract-Conference.html) [\[code\]](https://github.com/aim-uofa/GenPercept)
- [He2025] Lotus-2: Advancing Geometric Dense Prediction with Powerful Image Generative Model in *arXiv*, 2025. [\[paper\]](https://arxiv.org/pdf/2512.01030) [\[code\]](https://github.com/EnVision-Research/Lotus-2)
- [Li2025] CH<sub>3</sub>Depth: Efficient and Flexible Depth Foundation Model with Flow Matching in *CVPR*, 2025. [\[paper\]](https://openaccess.thecvf.com/content/CVPR2025/papers/Li_CH3Depth_Efficient_and_Flexible_Depth_Foundation_Model_with_Flow_Matching_CVPR_2025_paper.pdf) [\[code\]](https://github.com/lijia7/CH3Depth)
- [Lin2025] More Than Generation: Unifying Generation and Depth Estimation via Text-to-Image Diffusion Models in *NeurIPS*, 2025. [\[paper\]](https://arxiv.org/abs/2510.23574) [\[code\]](https://github.com/H-EmbodVis/MERGE)
- [Liu2025] TPDepth: Leveraging Text Prompts with ControlNet to Boost Diffusion-based Depth Estimation in *ACM MM*, 2025. [\[paper\]](https://dl.acm.org/doi/10.1145/3746027.3755384) [\[code\]](https://github.com/Lioely/TPDepth)
- [Gui2025] DepthFM: Fast Monocular Depth Estimation with Flow Matching in *AAAI*, 2025. [\[paper\]](https://arxiv.org/abs/2403.13788) [\[code\]](https://github.com/CompVis/depth-fm)
- [Garcia2025] Fine-Tuning Image-Conditional Diffusion Models is Easier than You Think in *WACV*, 2025. [\[paper\]](https://arxiv.org/pdf/2409.11355) [\[code\]](https://github.com/VisualComputingInstitute/diffusion-e2e-ft)
- [He2025] Lotus: Diffusion-based Visual Foundation Model for High-quality Dense Prediction in *ICLR*, 2025. [\[paper\]](https://arxiv.org/abs/2409.18124) [\[code\]](https://github.com/EnVision-Research/Lotus)
- [Ke2025] Marigold: Affordable Adaptation of Diffusion-Based Image Generators for Image Analysis in *IEEE TPAMI*, 2025 (early access). [\[paper\]](https://arxiv.org/abs/2505.09358) [\[code\]](https://github.com/prs-eth/Marigold)
- [Ke2024] Repurposing Diffusion-Based Image Generators for Monocular Depth Estimation in *CVPR*, 2024. [\[paper\]](https://openaccess.thecvf.com/content/CVPR2024/papers/Ke_Repurposing_Diffusion-Based_Image_Generators_for_Monocular_Depth_Estimation_CVPR_2024_paper.pdf) [\[code\]](https://github.com/prs-eth/Marigold)
- [Fu2024] GeoWizard: Unleashing the Diffusion Priors for 3D Geometry Estimation from a Single Image in *ECCV*, 2024. [\[paper\]](https://arxiv.org/abs/2403.12013) [\[code\]](https://github.com/fuxiao0719/GeoWizard)
- [Shao2024] MonoDiffusion: Self-Supervised Monocular Depth Estimation Using Diffusion Model in *IEEE TCSVT*, 2024. [\[paper\]](https://arxiv.org/abs/2311.07198) [\[code\]](https://github.com/ShuweiShao/MonoDiffusion)
- [Wang2024] Digging into contrastive learning for robust depth estimation with diffusion models in *ACM MM*, 2024. [\[paper\]](https://arxiv.org/abs/2404.09831) [\[code\]](https://github.com/wangjiyuan9/D4RD)
- [Ji2023] DDP: Diffusion Model for Dense Visual Prediction in *ICCV*, 2023. [\[paper\]](https://openaccess.thecvf.com/content/ICCV2023/papers/Ji_DDP_Diffusion_Model_for_Dense_Visual_Prediction_ICCV_2023_paper.pdf) [\[code\]](https://github.com/JiYuanFeng/DDP)
- [Saxena2023] Monocular Depth Estimation using Diffusion Models in *arXiv*, 2023. [\[paper\]](https://arxiv.org/pdf/2302.14816) [\[code\]](https://depth-gen.github.io/)
- [Saxena2023] The Surprising Effectiveness of Diffusion Models for Optical Flow and Monocular Depth Estimation in *NeurIPS*, 2023. [\[paper\]](https://arxiv.org/pdf/2306.01923) [\[code\]](https://diffusion-vision.github.io/)

### 🏷️ Combination

- [He2025] Distill Any Depth: Distillation Creates a Stronger Monocular Depth Estimator in *arXiv*, 2025. [\[paper\]](https://arxiv.org/abs/2502.19204) [\[code\]](https://github.com/Westlake-AGI-Lab/Distill-Any-Depth)
- [Pham2025] SharpDepth: Sharpening Metric Depth Predictions Using Diffusion Distillation in *CVPR*, 2025. [\[paper\]](https://openaccess.thecvf.com/content/CVPR2025/papers/Pham_SharpDepth_Sharpening_Metric_Depth_Predictions_Using_Diffusion_Distillation_CVPR_2025_paper.pdf) [\[code\]](https://github.com/Qualcomm-AI-research/SharpDepth)
- [Zhang2024] BetterDepth: Plug-and-Play Diffusion Refiner for Zero-Shot Monocular Depth Estimation in *NeurIPS*, 2024. [\[paper\]](https://arxiv.org/abs/2407.17952)

### 🏷️ Video Depth Estimation & Temporal Refinement

- [Chen2025] Video Depth Anything: Consistent Depth Estimation for Super-Long Videos in *CVPR*, 2025. [\[paper\]](https://arxiv.org/abs/2501.12375) [\[code\]](https://github.com/DepthAnything/Video-Depth-Anything)
- [Ke2025] Video Depth without Video Models in *CVPR*, 2025. [\[paper\]](https://arxiv.org/abs/2411.19189) [\[code\]](https://github.com/prs-eth/RollingDepth)
- [Yang2025] Depth Any Video with Scalable Synthetic Data in *ICLR*, 2025. [\[paper\]](https://arxiv.org/abs/2410.10815) [\[code\]](https://github.com/Nightmare-n/DepthAnyVideo)
- [Hu2025] DepthCrafter: Generating Consistent Long Depth Sequences for Open-world Videos in *CVPR*, 2025. [\[paper\]](https://arxiv.org/abs/2409.02095) [\[code\]](https://github.com/Tencent/DepthCrafter)
- [Shao2025] Learning Temporally Consistent Video Depth from Video Diffusion Priors in *CVPR*, 2025. [\[paper\]](https://arxiv.org/abs/2406.01493) [\[code\]](https://github.com/jiahao-shao1/ChronoDepth)
- [Wang2023] Neural Video Depth Stabilizer in *ICCV*, 2023. [\[paper\]](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Neural_Video_Depth_Stabilizer_ICCV_2023_paper.pdf) [\[code\]](https://github.com/RaymondWang987/NVDS)

### 🏷️ Related Stereo-Guided Methods

These methods use additional stereo observations to guide monocular depth priors.

- [Pham2025] GeoDiff: Geometry-Guided Diffusion for Metric Depth Estimation in *ICCV Findings*, 2025. [\[paper\]](https://arxiv.org/pdf/2510.18291)

## ✨ Depth Completion (Foundation Model-based Method)

### 🏷️ Architectural Revision & Fine-tuning

- [Lyu2026] DidSee: Diffusion-Based Depth Completion for Material-Agnostic Robotic Perception and Manipulation in *IEEE TCSVT*, 2026. [\[paper\]](https://ieeexplore.ieee.org/document/11688125) [\[preprint\]](https://arxiv.org/abs/2506.21034) [\[project\]](https://wenzhoulyu.github.io/DidSee/index.html)
- [Yan2026] Zero-Shot Depth Completion with Vision-Language Model in *CVPR*, 2026. [\[paper\]](https://openaccess.thecvf.com/content/CVPR2026/html/Yan_Zero-Shot_Depth_Completion_with_Vision-Language_Model_CVPR_2026_paper.html)
- [Tan2026] Masked Depth Modeling for Spatial Perception in *ECCV*, 2026. [\[paper\]](https://arxiv.org/abs/2601.17895) [\[code\]](https://github.com/robbyant/lingbot-depth)
- [Kim2026] Dense Metric Depth Completion from Sparse Direct Time-of-Flight Sensors in *CVPR*, 2026. [\[paper\]](https://arxiv.org/abs/2608.04737) [\[code\]](https://github.com/KAIST-VCLAB/dToF-DMDC)
- [Keetha2026] MapAnything: Universal Feed-Forward Metric 3D Reconstruction in *3DV*, 2026. [\[paper\]](https://arxiv.org/abs/2509.13414) [\[code\]](https://github.com/facebookresearch/map-anything)
- [Gregorek2026] Need for Speed: Zero-Shot Depth Completion with Single-Step Diffusion in *CVPR Workshops (NTIRE)*, 2026. [\[paper\]](https://arxiv.org/abs/2603.10584) [\[code\]](https://github.com/dtu-pas/marigold-ssd)
- [Zhou2026] Any to Full: Prompting Depth Anything for Depth Completion in One Stage in *ECCV*, 2026. [\[paper\]](https://arxiv.org/abs/2603.05711) [\[code\]](https://github.com/zhiyuandaily/Any2Full)
- [Cho2026] OASIS-DC: Generalizable Depth Completion via Output-level Alignment of Sparse-Integrated Monocular Pseudo Depth in *ICRA*, 2026. [\[paper\]](https://arxiv.org/abs/2602.01268) [\[code\]](https://github.com/jhcho-53/OASIS-DC)
- [Yu2026] Large Depth Completion Model from Sparse Observations in *ICLR*, 2026. [\[paper\]](https://arxiv.org/abs/2605.30115) [\[code\]](https://github.com/aigc3d/LDCM)
- [Wang2026] Depth Anything with Any Prior in *ICLR*, 2026. [\[paper\]](https://arxiv.org/abs/2505.10565) [\[code\]](https://github.com/SpatialVision/Prior-Depth-Anything)
- [Xiang2025] DEPTHOR: Depth Enhancement from a Practical Light-Weight dToF Sensor and RGB Image in *ICCV*, 2025. [\[paper\]](https://openaccess.thecvf.com/content/ICCV2025/papers/Xiang_DEPTHOR_Depth_Enhancement_from_a_Practical_Light-Weight_dToF_Sensor_and_ICCV_2025_paper.pdf) [\[code\]](https://github.com/ShadowBbBb/Depthor)
- [Chen2025] Propagating Sparse Depth via Depth Foundation Model for Out-of-Distribution Depth Completion in *IEEE TIP*, 2025. [\[paper\]](https://arxiv.org/abs/2508.04984) [\[code\]](https://github.com/shenglunch/PSD)
- [Lin2025] Prompting Depth Anything for 4K Resolution Accurate Metric Depth Estimation in *CVPR*, 2025. [\[paper\]](https://openaccess.thecvf.com/content/CVPR2025/papers/Lin_Prompting_Depth_Anything_for_4K_Resolution_Accurate_Metric_Depth_Estimation_CVPR_2025_paper.pdf) [\[code\]](https://github.com/DepthAnything/PromptDA)
- [Park2024] A Simple yet Universal Framework for Depth Completion in *NeurIPS*, 2024. [\[paper\]](https://openreview.net/forum?id=Y4tHp5Jilp) [\[code\]](https://github.com/JinhwiPark/UniDC)
- [Park2024] Depth Prompting for Sensor-Agnostic Depth Estimation in *CVPR*, 2024. [\[paper\]](https://arxiv.org/abs/2405.11867) [\[code\]](https://github.com/JinhwiPark/DepthPrompting)
- [Liu2024] DepthLab: From Partial to Complete in *arXiv*, 2024. [\[paper\]](https://arxiv.org/abs/2412.18153) [\[code\]](https://github.com/ant-research/DepthLab)

MetricAnything (Ma et al., ECCV 2026), listed under [Discriminative Model](#discriminative-model), also performs depth completion using sparse metric prompts.

### 🏷️ Knowledge Distillation

- [Wang2026] AURORA-KITTI: Any-Weather Depth Completion and Denoising in *arXiv*, 2026. [\[paper\]](https://arxiv.org/abs/2603.14701)
- [Kim2025] All-day Depth Completion via Thermal-LiDAR Fusion in *arXiv*, 2025. [\[paper\]](https://arxiv.org/abs/2504.02356)
- [Yang2025] HFD-Teacher: High-Frequency Depth Distillation from Depth Foundation Models for Enhanced Depth Completion in *ICCV*, 2025. [\[paper\]](https://openaccess.thecvf.com/content/ICCV2025/papers/Yang_HFD-Teacher_High-Frequency_Depth_Distillation_from_Depth_Foundation_Models_for_Enhanced_ICCV_2025_paper.pdf)
- [Wang2025] PacGDC: Label-Efficient Generalizable Depth Completion with Projection Ambiguity and Consistency in *ICCV*, 2025. [\[paper\]](https://arxiv.org/abs/2507.07374) [\[code\]](https://github.com/Wang-xjtu/PacGDC)
- [Liang2025] Distilling Monocular Foundation Model for Fine-grained Depth Completion in *CVPR*, 2025. [\[paper\]](https://openaccess.thecvf.com/content/CVPR2025/html/Liang_Distilling_Monocular_Foundation_Model_for_Fine-grained_Depth_Completion_CVPR_2025_paper.html) [\[code\]](https://github.com/Sharpiless/DMD3C)

### 🏷️ Test-time Adaptation

- [Ke2026] Depth Completion as Parameter-Efficient Test-Time Adaptation in *arXiv*, 2026. [\[paper\]](https://arxiv.org/abs/2602.14751) [\[code\]](https://github.com/nv-dvl/capa)
- [Seo2026] StreamTTO: Efficient Online Test-Time Optimization for Video Depth Completion in *arXiv*, 2026. [\[paper\]](https://arxiv.org/abs/2603.01765) [\[code\]](https://github.com/Wonjun-Lee1009/Efficient-TTO-Depth-Completion)
- [Jeong2025] Test-Time Prompt Tuning for Zero-Shot Depth Completion in *ICCV*, 2025. [\[paper\]](https://openaccess.thecvf.com/content/ICCV2025/papers/Jeong_Test-Time_Prompt_Tuning_for_Zero-Shot_Depth_Completion_ICCV_2025_paper.pdf) [\[code\]](https://github.com/JinhwiPark/TestPromptDC)
- [Viola2025] Marigold-DC: Zero-Shot Monocular Depth Completion with Guided Diffusion in *ICCV*, 2025. [\[paper\]](https://arxiv.org/abs/2412.13389) [\[code\]](https://github.com/prs-eth/Marigold-DC)
- [Lee2025] Zero-shot Depth Completion via Test-time Alignment with Affine-invariant Depth Prior in *AAAI*, 2025. [\[paper\]](https://arxiv.org/abs/2502.06338) [\[code\]](https://github.com/kaist-ami/Zero-Shot-Depth-Completion)
- [Gregorek2025] SteeredMarigold: Steering Diffusion Towards Depth Completion of Largely Incomplete Depth Maps in *ICRA*, 2025. [\[paper\]](https://arxiv.org/abs/2409.10202) [\[code\]](https://github.com/DTU-PAS/steered-marigold)

### 🏷️ Explicit Output Calibration

- [Zhang2026] The Midas Touch for Metric Depth: Interpretable Metricization for Generalizable Depth Perception in *arXiv*, 2026. [\[paper\]](https://arxiv.org/abs/2610.16749)
- [Ma2026] The Midas Touch for Metric Depth in *CVPR*, 2026. [\[paper\]](https://openaccess.thecvf.com/content/CVPR2026/html/Ma_The_Midas_Touch_for_Metric_Depth_CVPR_2026_paper.html) [\[code\]](https://github.com/HenryMaxixi/MTD)
- [Dorer2026] AnchorD: Metric Grounding of Monocular Depth Using Factor Graphs in *IROS*, 2026. [\[paper\]](https://arxiv.org/abs/2605.02667)
- [Halperin2026] FounRef: Robust, Structure-Preserving, and Fast Metric Refinement of Frozen Monocular Foundation Priors with Sparse Anchors in *arXiv*, 2026. [\[paper\]](https://arxiv.org/abs/2609.29224)
- [Zhang2026] Boosting Metric Depth Completion via Training-Free Adaptive Response Geometry in *arXiv*, 2026. [\[paper\]](https://arxiv.org/abs/2609.36168)
- [Xu2024] Toward 3D scene reconstruction from locally scale-aligned monocular video depth in *JUSTC*, 2024. [\[paper\]](https://doi.org/10.52396/JUSTC-2023-0061)

## ✨ Related Generalizable Depth Completion Baselines

These methods are included for comparison and are not categorized as adaptations of depth foundation models.

- [Zuo2025] OMNI-DC: Highly Robust Depth Completion with Multiresolution Depth Integration in *ICCV*, 2025. [\[paper\]](https://arxiv.org/abs/2411.19278) [\[code\]](https://github.com/princeton-vl/OMNI-DC)
- [Wang2025] Scale Propagation Network for Generalizable Depth Completion in *IEEE TPAMI*, 2025. [\[paper\]](https://doi.org/10.1109/TPAMI.2024.3513440) [\[code\]](https://github.com/Wang-xjtu/SPNet)

## 📊 Datasets

- **Hypersim**: [Roberts2021] Hypersim: A Photorealistic Synthetic Dataset for Holistic Indoor Scene Understanding in *ICCV*, 2021. [\[paper\]](https://openaccess.thecvf.com/content/ICCV2021/papers/Roberts_Hypersim_A_Photorealistic_Synthetic_Dataset_for_Holistic_Indoor_Scene_Understanding_ICCV_2021_paper.pdf) [\[download\]](https://github.com/apple/ml-hypersim)
- **VOID**: [Wong2020] Unsupervised depth completion from visual inertial odometry in *IEEE RA-L*, 2020. [\[paper\]](https://ieeexplore.ieee.org/document/8972600) [\[download\]](https://github.com/alexklwong/void-dataset)
- **DDAD**: [Guizilini2020] 3D Packing for Self-Supervised Monocular Depth Estimation in *CVPR*, 2020. [\[paper\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Guizilini_3D_Packing_for_Self-Supervised_Monocular_Depth_Estimation_CVPR_2020_paper.pdf) [\[download\]](https://github.com/TRI-ML/DDAD)
- **NuScenes**: [Caesar2020] nuScenes: A multimodal dataset for autonomous driving in *CVPR*, 2020. [\[paper\]](https://openaccess.thecvf.com/content_CVPR_2020/papers/Caesar_nuScenes_A_Multimodal_Dataset_for_Autonomous_Driving_CVPR_2020_paper.pdf) [\[download\]](https://github.com/nutonomy/nuscenes-devkit)
- **DIODE**: [Vasiljevic2019] DIODE: A Dense Indoor and Outdoor DEpth Dataset in *arXiv*, 2019. [\[paper\]](https://arxiv.org/abs/1908.00463) [\[download\]](https://diode-dataset.org/)
- **IBims-1**: [Koch2018] Evaluation of CNN-based Single-Image Depth Estimation Methods in *ECCVW*, 2018. [\[paper\]](https://openaccess.thecvf.com/content_ECCVW_2018/papers/11131/Koch_Evaluation_of_CNN-based_Single-Image_Depth_Estimation_Methods_ECCVW_2018_paper.pdf) [\[download\]](https://www.asg.ed.tum.de/lmf/ibims1/)
- **ETH3D**: [Schöps2017] A Multi-view Stereo Benchmark with High-Resolution Images and Multi-camera Videos in *CVPR*, 2017. [\[paper\]](https://ieeexplore.ieee.org/document/8099755) [\[download\]](https://www.eth3d.net/)
- **KITTI**: [Uhrig2017] Sparsity Invariant CNNs in *3DV*, 2017. [\[paper\]](https://arxiv.org/abs/1708.06500) [\[download\]](https://www.cvlibs.net/datasets/kitti/eval_depth.php?benchmark=depth_completion)
- **ScanNet**: [Dai2017] ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes in *CVPR*, 2017. [\[paper\]](https://openaccess.thecvf.com/content_cvpr_2017/papers/Dai_ScanNet_Richly-Annotated_3D_CVPR_2017_paper.pdf) [\[download\]](http://www.scan-net.org/)
- **Virtual KITTI 1**: [Gaidon2016] Virtual Worlds as Proxy for Multi-Object Tracking Analysis in *CVPR*, 2016. [\[paper\]](https://openaccess.thecvf.com/content_cvpr_2016/papers/Gaidon_Virtual_Worlds_as_CVPR_2016_paper.pdf) [\[download\]](https://europe.naverlabs.com/research/computer-vision/proxy-virtual-worlds-vkitti-1/)
- **Virtual KITTI 2**: [Cabon2020] Virtual KITTI 2 in *arXiv*, 2020. [\[paper\]](https://arxiv.org/abs/2001.10773) [\[download\]](https://europe.naverlabs.com/proxy-virtual-worlds-vkitti-2/)
- **SYNTHIA**: [Ros2016] The SYNTHIA Dataset: A Large Collection of Synthetic Images for Semantic Segmentation of Urban Scenes in *CVPR*, 2016. [\[paper\]](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Ros_The_SYNTHIA_Dataset_CVPR_2016_paper.pdf) [\[download\]](https://synthia-dataset.net/)
- **NYU-v2**: [Silberman2012] Indoor Segmentation and Support Inference from RGBD Images in *ECCV*, 2012. [\[paper\]](https://cs.nyu.edu/~fergus/datasets/indoor_seg_support.pdf) [\[download\]](https://cs.nyu.edu/~fergus/datasets/nyu_depth_v2.html)

## 🔍 Related Survey

- [Yao2025] Monocular Depth Estimation in the Foundation Model Era: A Survey in *TechRxiv*, 2025. [\[paper\]](https://www.techrxiv.org/users/996121/articles/1356831-monocular-depth-estimation-in-the-foundation-model-era-a-survey)
- [Xu2025] Towards Depth Foundation Model: Recent Trends in Vision-Based Depth Estimation in *arXiv*, 2025. [\[paper\]](https://arxiv.org/abs/2507.11540)
- [Xie2024] Recent Advances in Conventional and Deep Learning-Based Depth Completion: A Survey in *IEEE TNNLS*, 2024. [\[paper\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9875218)
- [Arampatzakis2023] Monocular Depth Estimation: A Thorough Review in *IEEE TPAMI*, 2023. [\[paper\]](https://ieeexplore.ieee.org/document/10313067)
- [Hu2022] Deep Depth Completion From Extremely Sparse Data: A Survey in *IEEE TPAMI*, 2022. [\[paper\]](https://ieeexplore.ieee.org/document/9984942)
