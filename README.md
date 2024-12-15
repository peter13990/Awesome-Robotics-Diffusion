# Awesome Robot Diffusion [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) <!-- omit in toc -->
A curated list of recent robot learning papers incorporating diffusion models for manipulation, navigation, planning etc.

<!-- <p align="center">
<img src="https://makeavideo.studio/assets/overview.webp" width="240px"/>
<img src="https://makeavideo.studio/assets/A_teddy_bear_painting_a_portrait.webp" width="240px"/>    
</p>

<p align="center">
<img src="https://tuneavideo.github.io/assets/teaser.gif" width="480px"/>  
</p>

<p align="center">
<img src="https://github.com/ChenyangQiQi/FateZero/blob/main/docs/gif_results/17_car_posche_01_concat_result.gif?raw=true" width="240px"/>
<img src="https://github.com/ChenyangQiQi/FateZero/blob/main/docs/gif_results/3_sunflower_vangogh_conat_result.gif?raw=true" width="240px"/>    
</p>

<p align="center">
(Source: <a href="https://makeavideo.studio/">Make-A-Video</a>, <a href="https://tuneavideo.github.io/">Tune-A-Video</a>, and <a href="https://fate-zero-edit.github.io/">Fate/Zero</a>.)
</p> -->

## Table of Contents <!-- omit in toc -->
- [Benchmarks](#benchmarks)
- [Diffusion Policy: Manipulation](#diffusion-policy-manipulation)
- [Diffusion Policy: Navigation / Task and Motion Planning](#diffusion-policy-navigation--task-and-motion-planning)
- [Diffusion Generation Models Powered Robot Learning](#diffusion-generation-models-powered-robot-learning)
- [Robot Learning Utilizing Diffusion Model Properties](#robot-learning-Utilizing-Diffusion-Model0Properties)


### Benchmarks

+ [Learning Complex Dexterous Manipulation with Deep Reinforcement Learning and Demonstrations](https://arxiv.org/abs/1709.10087) (RSS 2018)
  [![Star](https://img.shields.io/github/stars/aravindr93/hand_dapg.svg?style=social&label=Star)](https://github.com/aravindr93/hand_dapg)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1709.10087)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/deeprl-dexterous-manipulation)

+ [Meta-World: A Benchmark and Evaluation for Multi-Task and Meta Reinforcement Learning](https://arxiv.org/abs/1910.10897) (CoRL 2020)
  [![Star](https://img.shields.io/github/stars/Farama-Foundation/Metaworld.svg?style=social&label=Star)](https://github.com/Farama-Foundation/Metaworld)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1910.10897)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://meta-world.github.io/)


+ [DexMV: Imitation Learning for Dexterous Manipulation from Human Videos](https://arxiv.org/abs/2108.05877) (ECCV 2022)
  [![Star](https://img.shields.io/github/stars/yzqin/dexmv-sim.svg?style=social&label=Star)](https://github.com/yzqin/dexmv-sim)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2108.05877)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yzqin.github.io/dexmv/)

+ [Towards Human-Level Bimanual Dexterous Manipulation with Reinforcement Learning](https://arxiv.org/pdf/2206.08686) (NeurIPS 2022 Datasets and Benchmarks Track)
  [![Star](https://img.shields.io/github/stars/PKU-MARL/DexterousHands.svg?style=social&label=Star)](https://github.com/PKU-MARL/DexterousHands)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2206.08686)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://pku-marl.github.io/DexterousHands/)

+ [Dexart: Benchmarking generalizable dexterous manipulation with articulated objects](https://arxiv.org/abs/2305.05706) (CVPR 2023)
  [![Star](https://img.shields.io/github/stars/Kami-code/dexart-release.svg?style=social&label=Star)](https://github.com/Kami-code/dexart-release)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.05706)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.chenbao.tech/dexart/)

Visual Pusher

Bridege

Panda Arm

  Dexdeform: Dexterous deformable object manipulation with human demonstrations and differentiable physics (To be checked)

### Diffusion Policy: Manipulation
+ [Imitating Human Behaviour with Diffusion Models](https://arxiv.org/abs/2301.10677) (ICLR 2023)
  [![Star](https://img.shields.io/github/stars/microsoft/Imitating-Human-Behaviour-w-Diffusion.svg?style=social&label=Star)](https://github.com/microsoft/Imitating-Human-Behaviour-w-Diffusion)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.10677)
  <!-- [![Website](https://img.shields.io/badge/Website-9cf)](https://pypi.org/project/fvmd/1.0.0/) -->
  
+ [Se(3)-diffusionfields: Learning cost functions for joint grasp and motion optimization through diffusion](https://arxiv.org/abs/2209.03855) (ICRA 2023)
  [![Star](https://img.shields.io/github/stars/robotgradient/grasp_diffusion.svg?style=social&label=Star)](https://github.com/robotgradient/grasp_diffusion)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.03855)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/se3dif)

+ [Diffusion policy: Visuomotor policy learning via action diffusion](https://arxiv.org/abs/2303.04137) (RSS 2023)
  [![Star](https://img.shields.io/github/stars/real-stanford/diffusion_policy.svg?style=social&label=Star)](https://github.com/real-stanford/diffusion_policy)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.04137)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://diffusion-policy.cs.columbia.edu/)

+ [Goal-conditioned imitation learning using score-based diffusion policies](https://arxiv.org/abs/2304.02532) (RSS 2023)
  [![Star](https://img.shields.io/github/stars/intuitive-robots/beso.svg?style=social&label=Star)](https://github.com/intuitive-robots/beso)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.02532)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://intuitive-robots.github.io/beso-website/)

+ [Scaling Up and Distilling Down: Language-Guided Robot Skill Acquisition](https://www.sciencedirect.com/science/article/abs/pii/S0950705124008244) (CoRL 2023)
  [![Star](https://img.shields.io/github/stars/real-stanford/scalingup.svg?style=social&label=Star)](https://github.com/real-stanford/scalingup)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.cs.columbia.edu/~huy/scalingup/)

+ [ChainedDiffuser: Unifying Trajectory Diffusion and Keypose Prediction for Robotic Manipulation](https://openreview.net/forum?id=W0zgY2mBTA8) (CoRL 2023)
  [![Star](https://img.shields.io/github/stars/zhouxian/act3d-chained-diffuser.svg?style=social&label=Star)](https://github.com/zhouxian/act3d-chained-diffuser)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://chained-diffuser.github.io/)

+ [Memory-Consistent Neural Networks for Imitation Learning](https://arxiv.org/abs/2310.06171) (ICLR 2024)
  [![Star](https://img.shields.io/github/stars/kaustubhsridhar/MCNN.svg?style=social&label=Star)](https://github.com/kaustubhsridhar/MCNN)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.06171)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/mcnn-imitation)

+ [EDMP: Ensemble-of-costs-guided Diffusion for Motion Planning](https://arxiv.org/abs/2309.11414) (ICRA 2024)
  [![Star](https://img.shields.io/github/stars/vishal-2000/EDMP.svg?style=social&label=Star)](https://github.com/vishal-2000/EDMP)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.11414)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://ensemble-of-costs-diffusion.github.io/)

+ [Diffskill: Improving Reinforcement Learning Through Diffusion-Based Skill Denoiser for Robotic Manipulation](https://www.sciencedirect.com/science/article/abs/pii/S0950705124008244) (Knowledge-Based Systems 2024)

+ [Consistency policy: Accelerated visuomotor policies via consistency distillation](https://arxiv.org/abs/2405.07503) (RSS 2024)
  [![Star](https://img.shields.io/github/stars/Aaditya-Prasad/Consistency-Policy.svg?style=social&label=Star)](https://github.com/Aaditya-Prasad/Consistency-Policy/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.07503)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://consistency-policy.github.io/)

+ [Track2Act: Predicting Point Tracks from Internet Videos enables Generalizable Robot Manipulation](https://arxiv.org/abs/2405.01527) (ECCV 2024)
  [![Star](https://img.shields.io/github/stars/homangab/Track-2-Act.svg?style=social&label=Star)](https://github.com/homangab/Track-2-Act/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2405.01527)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://homangab.github.io/track2act/)

+ [Differentiable Robot Rendering](https://arxiv.org/abs/2410.13851) (CoRL 2024)
  [![Star](https://img.shields.io/github/stars/cvlab-columbia/drrobot.svg?style=social&label=Star)](https://github.com/cvlab-columbia/drrobot)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.13851)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://drrobot.cs.columbia.edu/)

+ [Sparse Diffusion Policy: A Sparse, Reusable, and Flexible Policy for Robot Learning](https://arxiv.org/abs/2407.01531) (CoRL 2024)
  [![Star](https://img.shields.io/github/stars/AnthonyHuo/SDP.svg?style=social&label=Star)](https://github.com/AnthonyHuo/SDP)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.01531)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://forrest-110.github.io/sparse_diffusion_policy/)

+ [Equivariant Diffusion Policy](https://arxiv.org/abs/2407.01812) (CoRL 2024)
  [![Star](https://img.shields.io/github/stars/pointW/equidiff.svg?style=social&label=Star)](https://github.com/pointW/equidiff)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.01812)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://equidiff.github.io/)

+ [GenDP: 3D Semantic Fields for Category-Level Generalizable Diffusion Policy](https://arxiv.org/abs/2410.17488) (CoRL 2024)
  [![Star](https://img.shields.io/github/stars/WangYixuan12/gendp.svg?style=social&label=Star)](https://github.com/WangYixuan12/gendp)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.17488)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://robopil.github.io/GenDP/)

+ [EquiBot: SIM (3)-Equivariant Diffusion Policy for Generalizable and Data Efficient Learning](https://arxiv.org/abs/2407.01479) (CoRL 2024)
  [![Star](https://img.shields.io/github/stars/yjy0625/equibot.svg?style=social&label=Star)](https://github.com/yjy0625/equibot)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.01479)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://equi-bot.github.io/)

+ [3D Diffusion Policy: Generalizable Visuomotor Policy Learning via Simple 3D Representations](https://arxiv.org/abs/2403.03954) (Mar 2024)
  [![Star](https://img.shields.io/github/stars/YanjieZe/3D-Diffusion-Policy.svg?style=social&label=Star)](https://github.com/YanjieZe/3D-Diffusion-Policy)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2403.03954)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://3d-diffusion-policy.github.io/)

+ [Vision-Language-Affordance-based Robot Manipulation with Flow Matching](https://arxiv.org/abs/2409.01083) (Sep 2024)
  [![Star](https://img.shields.io/github/stars/HRI-EU/flow-matching-policy.svg?style=social&label=Star)](https://github.com/HRI-EU/flow-matching-policy)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.01083)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hri-eu.github.io/flow-matching-policy/)

+ [Planning-Guided Diffusion Policy Learning for Generalizable Contact-Rich Bimanual Manipulation](https://arxiv.org/abs/2412.02676) (Sep 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2412.02676)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://glide-manip.github.io/)
  <!-- [![Star](https://img.shields.io/github/stars/HRI-EU/flow-matching-policy.svg?style=social&label=Star)](https://github.com/HRI-EU/flow-matching-policy) -->




#### Humanoid

+ [Generalizable Humanoid Manipulation with Improved 3D Diffusion Policies](https://arxiv.org/abs/2410.10803) (Oct 2024)
  [![Star](https://img.shields.io/github/stars/YanjieZe/Improved-3D-Diffusion-Policy.svg?style=social&label=Star)](https://github.com/YanjieZe/Improved-3D-Diffusion-Policy)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2410.10803)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://humanoid-manipulation.github.io/)




#### Grasping / Rearrangement
+ [Shelving, stacking, hanging: Relational pose diffusion for multi-modal rearrangement](https://arxiv.org/abs/2307.04751) (CoRL 2023)
  [![Star](https://img.shields.io/github/stars/anthonysimeonov/rpdiff.svg?style=social&label=Star)](https://github.com/anthonysimeonov/rpdiff)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2307.04751)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://anthonysimeonov.github.io/rpdiff-multi-modal/)

+ [Learning score-based grasping primitive for human-assisting dexterous grasping](https://arxiv.org/abs/2309.06038) (NeurIPS 2023)
  [![Star](https://img.shields.io/github/stars/tianhaowuhz/human-assisting-dex-grasp.svg?style=social&label=Star)](https://github.com/tianhaowuhz/human-assisting-dex-grasp/)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.06038)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/graspgf)

+ [Reorientdiff: Diffusion model based reorientation for object manipulation](https://arxiv.org/abs/2303.12700) (ICRA 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12700)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://umishra.me/ReorientDiff/)

+ [DexDiffuser: Generating Dexterous Grasps with Diffusion Models](https://arxiv.org/abs/2402.02989) (Feb 2024)
  [![Star](https://img.shields.io/github/stars/YuLiHN/DexDiffuser.svg?style=social&label=Star)](https://github.com/YuLiHN/DexDiffuser)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.02989)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://yulihn.github.io/DexDiffuser_page/)


### Diffusion Policy: Navigation / Task and Motion Planning

+ [Diffusion Forcing: Next-token Prediction Meets Full-Sequence Diffusion](https://arxiv.org/abs/2407.01392) (NeurIPS 2024)
  [![Star](https://img.shields.io/github/stars/buoyancy99/diffusion-forcing.svg?style=social&label=Star)](https://github.com/buoyancy99/diffusion-forcing)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2407.01392)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://boyuan.space/diffusion-forcing/)

### Diffusion Generation Models Powered Robot Learning
+ [DALL-E-Bot: Introducing Web-Scale Diffusion Models to Robotics](https://arxiv.org/abs/2210.02438) (RA-Letters 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.02438)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://www.robot-learning.uk/dall-e-bot)
  <!-- [![Star](https://img.shields.io/github/stars/ErinZhang1998/dmd_diffusion.svg?style=social&label=Star)](https://github.com/ErinZhang1998/dmd_diffusion) -->

+ [[UniPi] Learning Universal Policies via Text-Guided Video Generation](https://arxiv.org/abs/2302.00111) (NeurIPS 2023)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.00111)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://universal-policy.github.io/unipi/)

+ [[AVDC] Learning to Act from Actionless Videos through Dense Correspondences](https://arxiv.org/abs/2310.08576) (ICLR 2024)
  [![Star](https://img.shields.io/github/stars/flow-diffusion/AVDC.svg?style=social&label=Star)](https://github.com/flow-diffusion/AVDC)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.08576)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://flow-diffusion.github.io/)

+ [UniSim: Learning Interactive Real-World Simulators](https://arxiv.org/abs/2310.06114) (ICLR 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.06114)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://universal-simulator.github.io/unisim/)
  <!-- [![Star](https://img.shields.io/github/stars/ErinZhang1998/dmd_diffusion.svg?style=social&label=Star)](https://github.com/ErinZhang1998/dmd_diffusion) -->


+ [Compositional Foundation Models for Hierarchical Planning](https://arxiv.org/abs/2309.08587) (NeurIPS 2023)
  [![Star](https://img.shields.io/github/stars/anuragajay/hip.svg?style=social&label=Star)](https://github.com/anuragajay/hip)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.08587)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://hierarchical-planning-foundation-model.github.io/)

+ [Diffusion Meets DAgger: Supercharging Eye-in-hand Imitation Learning](https://arxiv.org/abs/2402.17768) (Feb 2024)
  [![Star](https://img.shields.io/github/stars/ErinZhang1998/dmd_diffusion.svg?style=social&label=Star)](https://github.com/ErinZhang1998/dmd_diffusion)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2402.17768)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/diffusion-meets-dagger)

+ [Video language planning](https://arxiv.org/abs/2310.10625) (ICLR 2024)
  [![Star](https://img.shields.io/github/stars/video-language-planning/vlp_code.svg?style=social&label=Star)](https://github.com/video-language-planning/vlp_code)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.10625)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://video-language-planning.github.io/)
  
+ [Dreamitate: Real-World Visuomotor Policy Learning via Video Generation](https://arxiv.org/abs/2406.16862) (CoRL 2024)
  [![Star](https://img.shields.io/github/stars/cvlab-columbia/dreamitate.svg?style=social&label=Star)](https://github.com/cvlab-columbia/dreamitate)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.16862)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamitate.cs.columbia.edu/)

+ [ARDuP: Active Region Video Diffusion for Universal Policies](https://arxiv.org/abs/2406.13301) (Jun 2024)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2406.13301)

+ [RoboDreamer: Learning Compositional World Models for Robot Imagination](https://arxiv.org/abs/2404.12377) (ICML 2024)
  [![Star](https://img.shields.io/github/stars/rainbow979/robodreamer.svg?style=social&label=Star)](https://github.com/rainbow979/robodreamer)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2404.12377)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://robovideo.github.io/)

+ [Closed-Loop Visuomotor Control with Generative Expectation for Robotic Manipulation](https://arxiv.org/abs/2409.09016) (NeurIPS 2024)
  [![Star](https://img.shields.io/github/stars/OpenDriveLab/CLOVER.svg?style=social&label=Star)](https://github.com/OpenDriveLab/CLOVER)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2409.09016)
  <!-- [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/diffusion-meets-dagger) -->



This&That: Language-Gesture Controlled Video Generation for Robot Planning

Diffusion Reward: Learning Rewards via Conditional Video Diffusion

SkillDiffuser: Interpretable Hierarchical Planning via Skill Abstractions in Diffusion-Based Task Execution

Large-Scale Actionless Video Pre-Training via Discrete Diffusion for Efficient Policy Learning




#### World models in robotics:

IRASim: Learning Interactive Real-Robot Action Simulators arXiv 2024.6

Structured World Models from Human Videos RSS 2023

HARP: Autoregressive Latent Video Prediction with High-Fidelity Image Generator ICIP 2022

DayDreamer: World Models for Physical Robot Learning CoRL 2022



### Robot Learning Utilizing Diffusion Model Properties
PoCo: Policy Composition from and for Heterogeneous Robot Learning (To be checked)

Diffusion Forcing: Next-token Prediction Meets Full-Sequence Diffusion (To be checked)

+ [Diffusion reward: Learning rewards via conditional video diffusion](https://arxiv.org/abs/2312.14134) (ECCV 2024)
  [![Star](https://img.shields.io/github/stars/TEA-Lab/diffusion_reward.svg?style=social&label=Star)](https://github.com/TEA-Lab/diffusion_reward)
  [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2312.14134)
  [![Website](https://img.shields.io/badge/Website-9cf)](https://diffusion-reward.github.io/)
