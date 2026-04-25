<div align="center">
    <h1>🧭 Awesome Visual Language Navigation</h1>
</div>

<p align="center">
    <a href="https://github.com/sindresorhus/awesome"><img src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" alt="Awesome list badge"></a>
    <a href="bib/awesome_visual_language_navigation.bib"><img src="https://img.shields.io/badge/BibTeX-curated-8B5E3C?logo=bookstack&logoColor=white" alt="BibTeX"></a>
</p>

## 🌟 Overview
- [📚 Preliminaries](#-preliminaries)
- [🧠 Context Modeling](#-context-modeling)
- [🔮 Imaginative Prediction](#-imaginative-prediction)
- [🎯 Decision Planning](#-decision-planning)
- [⚠️ Reflection from Error](#-reflection-from-error)
- [🌐 Broader Navigation Literature](#-broader-navigation-literature)
- [🚀 Future Directions](#-future-directions)
- [📊 Statistics](#-statistics)

## 📚 Preliminaries
### Simulation, Data and Control
#### Toward More Realistic Simulation
| Year | Paper | Venue |
|---:|---|---|
| 2025 | **[Rethinking the embodied gap in vision-and-language navigation: A holistic study of physical and visual disparities](https://arxiv.org/abs/2507.13019)** | 2025 ICCV |
| 2025 | **[Towards Physically Executable 3D Gaussian for Embodied Navigation](https://arxiv.org/abs/2510.21307)** | 2025 arXiv |
| 2025 | **[VLNVerse: A Benchmark for Vision-Language Navigation with Versatile, Embodied, Realistic Simulation and Evaluation](https://arxiv.org/abs/2512.19021)** | 2025 arXiv |
| 2021 | **[Habitat-Matterport 3D Dataset (HM3D): 1000 Large-scale 3D Environments for Embodied AI](https://arxiv.org/abs/2109.08238)** | 2021 NeurIPS D&B |
| 2019 | **[Habitat: A Platform for Embodied AI Research](https://openaccess.thecvf.com/content_ICCV_2019/html/Savva_Habitat_A_Platform_for_Embodied_AI_Research_ICCV_2019_paper.html)** | 2019 ICCV |
| 2019 | **[PyRobot: An Open-source Robotics Framework for Research and Benchmarking](https://arxiv.org/abs/1906.08236)** | 2019 arXiv |
| 2020 | **[Beyond the nav-graph: Vision-and-language navigation in continuous environments](https://arxiv.org/abs/2004.02857)** | 2020 ECCV |
| 2017 | **[Matterport3D: Learning from RGB-D Data in Indoor Environments](https://vision.princeton.edu/projects/2017/Matterport3D/)** | 2017 3DV |

#### Towards More Diverse Datasets
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[AirNav: A Large-Scale Real-World UAV Vision-and-Language Navigation Dataset with Natural and Diverse Instructions](https://arxiv.org/abs/2601.03707)** | 2026 arXiv |
| 2025 | **[CityWalker: Learning Embodied Urban Navigation from Web-Scale Videos](https://arxiv.org/abs/2411.17820)** | 2025 CVPR |
| 2025 | **[OpenFly: A Comprehensive Platform for Aerial Vision-Language Navigation](https://arxiv.org/abs/2502.18041)** | 2025 arXiv |
| 2025 | **[RoomTour3D: Geometry-Aware Video-Instruction Tuning for Embodied Navigation](https://arxiv.org/abs/2412.08591)** | 2025 CVPR |
| 2025 | **[Towards long-horizon vision-language navigation: Platform, benchmark and method](https://arxiv.org/abs/2412.09082)** | 2025 CVPR |
| 2025 | **[IndoorUAV: Benchmarking Vision-Language UAV Navigation in Continuous Indoor Environments](https://arxiv.org/abs/2512.19024)** | 2025 arXiv |
| 2025 | **[VL-LN Bench: Towards Long-horizon Goal-oriented Navigation with Active Dialogs](https://arxiv.org/abs/2512.22342)** | 2025 arXiv |
| 2024 | **[InstruGen: Automatic Instruction Generation for Vision-and-Language Navigation Via Large Multimodal Models](https://arxiv.org/abs/2411.11394)** | 2024 arXiv |
| 2024 | **[Hazard challenge: Embodied decision making in dynamically changing environments](https://arxiv.org/abs/2401.12975)** | 2024 arXiv |
| 2024 | **[Mind the error! detection and localization of instruction errors in vision-and-language navigation](https://arxiv.org/abs/2403.10700)** | 2024 IROS |
| 2024 | **[CityNav: Language-goal aerial navigation dataset with geographic information](https://arxiv.org/abs/2406.14240)** | 2024 arXiv |
| 2024 | **[Towards realistic uav vision-language navigation: Platform, benchmark, and methodology](https://arxiv.org/abs/2410.07087)** | 2024 arXiv |
| 2023 | **[Scaling Data Generation in Vision-and-Language Navigation](https://openaccess.thecvf.com/content/ICCV2023/html/Wang_Scaling_Data_Generation_in_Vision-and-Language_Navigation_ICCV_2023_paper.html)** | 2023 ICCV |
| 2023 | **[AerialVLN: Vision-and-Language Navigation for UAVs](https://arxiv.org/abs/2308.06735)** | 2023 ICCV |
| 2022 | **[REVE-CE: Remote Embodied Visual Referring Expression in Continuous Environment](https://ieeexplore.ieee.org/document/9674225/)** | 2022 RA-L |
| 2023 | **[Iterative vision-and-language navigation](https://arxiv.org/abs/2210.03087)** | 2023 CVPR |
| 2020 | **[Room-across-room: Multilingual vision-and-language navigation with dense spatiotemporal grounding](https://arxiv.org/abs/2010.07954)** | 2020 arXiv |
| 2018 | **[Vision-and-language navigation: Interpreting visually-grounded navigation instructions in real environments](https://arxiv.org/abs/1711.07280)** | 2018 CVPR |

#### Towards More Continuous Control
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[LiveVLN: Breaking the Stop-and-Go Loop in Vision-Language Navigation](https://arxiv.org/abs/2604.19536)** | 2026 arXiv |
| 2025 | **[Embodied Navigation Foundation Model](https://arxiv.org/abs/2509.12129)** | 2025 arXiv |
| 2024 | **[π0: A Vision-Language-Action Flow Model for General Robot Control](https://arxiv.org/abs/2410.24164)** | 2024 arXiv |
| 2024 | **[OpenVLA: An Open-Source Vision-Language-Action Model](https://arxiv.org/abs/2406.09246)** | 2024 arXiv |
| 2022 | **[Bridging the gap between learning in discrete and continuous environments for vision-and-language navigation](https://arxiv.org/abs/2203.02764)** | 2022 CVPR |
| 2021 | **[Hierarchical cross-modal agent for robotics vision-and-language navigation](https://arxiv.org/abs/2104.10674)** | 2021 ICRA |

## 🧠 Context Modeling
### Context Perception
#### Spatial Perception
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[DyGeoVLN: Infusing Dynamic Geometry Foundation Model into Vision-Language Navigation](https://arxiv.org/abs/2603.21269)** | 2026 arXiv |
| 2026 | **[SPAN-Nav: Generalized Spatial Awareness for Versatile Vision-Language Navigation](https://arxiv.org/abs/2603.09163)** | 2026 arXiv |
| 2026 | **[Spatial-VLN: Zero-Shot Vision-and-Language Navigation With Explicit Spatial Perception and Exploration](https://arxiv.org/abs/2601.12766)** | 2026 arXiv |
| 2025 | **[Efficient-VLN: A Training-Efficient Vision-Language Navigation Model](https://arxiv.org/abs/2512.10310)** | 2025 arXiv |
| 2025 | **[JanusVLN: Decoupling Semantics and Spatiality with Dual Implicit Memory for Vision-Language Navigation](https://arxiv.org/abs/2509.22548)** | 2025 arXiv |
| 2025 | **[MG-Nav: Dual-Scale Visual Navigation via Sparse Spatial Memory](https://arxiv.org/abs/2511.22609)** | 2025 arXiv |
| 2024 | **[NaVid: Video-based VLM Plans the Next Step for Vision-and-Language Navigation](https://arxiv.org/abs/2402.15852)** | 2024 RSS |

#### Temporal Perception
| Year | Paper | Venue |
|---:|---|---|
| 2025 | **[ActiveVLN: Towards Active Exploration via Multi-Turn RL in Vision-and-Language Navigation](https://arxiv.org/abs/2509.12618)** | 2025 arXiv |
| 2025 | **[NaVILA: Legged Robot Vision-Language-Action Model for Navigation](https://arxiv.org/abs/2412.04453)** | 2025 RSS |
| 2025 | **[StreamVLN: Streaming Vision-and-Language Navigation via SlowFast Context Modeling](https://arxiv.org/abs/2507.05240)** | 2025 arXiv |
| 2021 | **[VLN-BERT: A Recurrent Vision-and-Language BERT for Navigation](https://arxiv.org/abs/2011.13922)** | 2021 CVPR |

### Context Memory
#### Memory Representation
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[HiMemVLN: Enhancing Reliability of Open-Source Zero-Shot Vision-and-Language Navigation with Hierarchical Memory System](https://arxiv.org/abs/2603.14807)** | 2026 arXiv |
| 2026 | **[HaltNav: Reactive Visual Halting over Lightweight Topological Priors for Robust Vision-Language Navigation](https://arxiv.org/abs/2603.12696)** | 2026 arXiv |
| 2026 | **[GSMem: 3D Gaussian Splatting as Persistent Spatial Memory for Zero-Shot Embodied Exploration and Reasoning](https://arxiv.org/abs/2603.19137)** | 2026 arXiv |
| 2026 | **[Structured Observation Language for Efficient and Generalizable Vision-Language Navigation](https://arxiv.org/abs/2603.27577)** | 2026 arXiv |
| 2025 | **[MapNav: A Novel Memory Representation via Annotated Semantic Maps for VLM-based Vision-and-Language Navigation](https://aclanthology.org/2025.acl-long.638/)** | 2025 ACL |
| 2025 | **[Open-Nav: Exploring Zero-Shot Vision-and-Language Navigation in Continuous Environment with Open-Source LLMs](https://arxiv.org/abs/2409.18794)** | 2025 ICRA |
| 2024 | **[MapGPT: Map-Guided Prompting with Adaptive Path Planning for Vision-and-Language Navigation](https://arxiv.org/abs/2401.07314)** | 2024 ACL |
| 2023 | **[GridMM: Grid Memory Map for Vision-and-Language Navigation](https://arxiv.org/abs/2307.12907)** | 2023 ICCV |
| 2022 | **[BEVBert: Multimodal Map Pre-training for Language-guided Navigation](https://arxiv.org/abs/2212.04385)** | 2022 arXiv |
| 2021 | **[Structured Scene Memory for Vision-Language Navigation](https://arxiv.org/abs/2103.03454)** | 2021 CVPR |

#### Memory Retrieval and Utilization
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[CMMR-VLN: Vision-and-Language Navigation via Continual Multimodal Memory Retrieval](https://arxiv.org/abs/2603.07997)** | 2026 arXiv |
| 2026 | **[Dual-Anchoring: Addressing State Drift in Vision-Language Navigation](https://arxiv.org/abs/2604.17473)** | 2026 arXiv |
| 2026 | **[SpatialNav: Leveraging Spatial Scene Graphs for Zero-Shot Vision-and-Language Navigation](https://arxiv.org/abs/2601.06806)** | 2026 arXiv |
| 2025 | **[MemoryVLA: Perceptual-Cognitive Memory in Vision-Language-Action Models for Robotic Manipulation](https://arxiv.org/abs/2508.19236)** | 2025 arXiv |
| 2025 | **[Dream to Recall: Imagination-Guided Experience Retrieval for Memory-Persistent Vision-and-Language Navigation](https://arxiv.org/abs/2510.08553)** | 2025 arXiv |
| 2025 | **[FSR-VLN: Fast and Slow Reasoning for Vision-Language Navigation with Hierarchical Multi-modal Scene Graph](https://arxiv.org/abs/2509.13733)** | 2025 arXiv |
| 2025 | **[OpenIN: Open-Vocabulary Instance-Oriented Navigation in Dynamic Domestic Environments](https://arxiv.org/abs/2501.04279)** | 2025 RA-L |
| 2025 | **[Progress-Think: Semantic Progress Reasoning for Vision-Language Navigation](https://arxiv.org/abs/2511.17097)** | 2025 arXiv |
| 2024 | **[OrionNav: Online Planning for Robot Autonomy with Context-Aware LLM and Open-Vocabulary Semantic Scene Graphs](https://arxiv.org/abs/2410.06239)** | 2024 arXiv |

### Context Efficiency
#### Reducing Temporal Redundancy
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[DecoVLN: Decoupling Observation, Reasoning, and Correction for Vision-and-Language Navigation](https://arxiv.org/abs/2603.13133)** | 2026 arXiv |
| 2025 | **[AstraNav-Memory: Contexts Compression for Long Memory](https://arxiv.org/abs/2512.21627)** | 2025 arXiv |
| 2025 | **[COSMO: Combination of Selective Memorization for Low-cost Vision-and-Language Navigation](https://arxiv.org/abs/2503.24065)** | 2025 ICCV |

#### Reducing Spatial Redundancy
| Year | Paper | Venue |
|---:|---|---|
| 2025 | **[Uni-NaVid: A Video-based Vision-Language-Action Model for Unifying Embodied Navigation Tasks](https://arxiv.org/abs/2412.06224)** | 2025 RSS |

#### Computational Reuse and Acceleration
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[VLN-Cache: Enabling Token Caching for VLN Models with Visual/Semantic Dynamics Awareness](https://arxiv.org/abs/2603.07080)** | 2026 arXiv |

## 🔮 Imaginative Prediction
### Spatial Imagination
#### Occupancy Prediction
| Year | Paper | Venue |
|---:|---|---|
| 2024 | **[Occllama: An Occupancy-Language-Action Generative World Model for Autonomous Driving](https://arxiv.org/abs/2409.03272)** | 2024 arXiv |

#### View Completion
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[MapDream: Task-Driven Map Learning for Vision-Language Navigation](https://arxiv.org/abs/2602.00222)** | 2026 arXiv |
| 2025 | **[MonoDream: Monocular Vision-Language Navigation with Panoramic Dreaming](https://arxiv.org/abs/2508.02549)** | 2025 arXiv |
| 2025 | **[PanoGen++: Domain-Adapted Text-Guided Panoramic Environment Generation for Vision-and-Language Navigation](https://arxiv.org/abs/2503.09938)** | 2025 Neural Networks |
| 2024 | **[Imagine Before Go: Self-Supervised Generative Map for Object Goal Navigation](https://openaccess.thecvf.com/content/CVPR2024/html/Zhang_Imagine_Before_Go_Self-Supervised_Generative_Map_for_Object_Goal_Navigation_CVPR_2024_paper.html)** | 2024 CVPR |
| 2023 | **[PanoGen: Text-Conditioned Panoramic Environment Generation for Vision-and-Language Navigation](https://arxiv.org/abs/2305.19195)** | 2023 NeurIPS |
| 2023 | **[PEANUT: Predicting and Navigating to Unseen Targets](https://openaccess.thecvf.com/content/ICCV2023/html/Zhai_PEANUT_Predicting_and_Navigating_to_Unseen_Targets_ICCV_2023_paper.html)** | 2023 ICCV |

#### 3D Representation
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[ThinkMatter: Panoramic-Aware Instructional Semantics for Monocular Vision-and-Language Navigation](https://doi.org/10.1109/TIP.2026.3652003)** | 2026 TIP |
| 2025 | **[monoVLN: Bridging the Observation Gap between Monocular and Panoramic Vision and Language Navigation](https://openaccess.thecvf.com/content/ICCV2025/html/Lu_monoVLN_Bridging_the_Observation_Gap_between_Monocular_and_Panoramic_Vision_ICCV_2025_paper.html)** | 2025 ICCV |
| 2024 | **[UnitedVLN: Generalizable Gaussian Splatting for Continuous Vision-Language Navigation](https://arxiv.org/abs/2411.16053)** | 2024 arXiv |

### Temporal Imagination
#### Pixel Level
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[NavDreamer: Video Models as Zero-Shot 3D Navigators](https://arxiv.org/abs/2602.09765)** | 2026 arXiv |
| 2026 | **[Sparse Video Generation Propels Real-World Beyond-the-View Vision-Language Navigation](https://arxiv.org/abs/2602.05827)** | 2026 arXiv |
| 2025 | **[DreamNav: A Trajectory-Based Imaginative Framework for Zero-Shot Vision-and-Language Navigation](https://arxiv.org/abs/2509.11197)** | 2025 arXiv |
| 2025 | **[AstraNav-World: World Model for Foresight Control and Consistency](https://arxiv.org/abs/2512.21714)** | 2025 arXiv |
| 2025 | **[Navigation World Models](https://openaccess.thecvf.com/content/CVPR2025/html/Bar_Navigation_World_Models_CVPR_2025_paper.html)** | 2025 CVPR |
| 2025 | **[Do Visual Imaginations Improve Vision-and-Language Navigation Agents?](https://openaccess.thecvf.com/content/CVPR2025/html/Perincherry_Do_Visual_Imaginations_Improve_Vision-and-Language_Navigation_Agents_CVPR_2025_paper.html)** | 2025 CVPR |
| 2025 | **[VISTA: Generative Visual Imagination for Vision-and-Language Navigation](https://arxiv.org/abs/2505.07868)** | 2025 arXiv |
| 2025 | **[VISTAv2: World Imagination for Indoor Vision-and-Language Navigation](https://arxiv.org/abs/2512.00041)** | 2025 arXiv |
| 2021 | **[PathDreamer: A World Model for Indoor Navigation](https://arxiv.org/abs/2105.08756)** | 2021 ICCV |

#### Feature Level
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[FantasyVLN: Unified Multimodal Chain-of-Thought Reasoning for Vision-Language Navigation](https://arxiv.org/abs/2601.13976)** | 2026 arXiv |
| 2026 | **[LatentPilot: Scene-Aware Vision-and-Language Navigation by Dreaming Ahead with Latent Visual Reasoning](https://arxiv.org/abs/2603.29165)** | 2026 arXiv |
| 2026 | **[PROSPECT: Unified Streaming Vision-Language Navigation via Semantic-Spatial Fusion and Latent Predictive Representation](https://arxiv.org/abs/2603.03739)** | 2026 arXiv |
| 2025 | **[NavForesee: A Unified Vision-Language World Model for Hierarchical Planning and Dual-Horizon Navigation Prediction](https://arxiv.org/abs/2512.01550)** | 2025 arXiv |
| 2025 | **[NavMorph: A Self-Evolving World Model for Vision-and-Language Navigation in Continuous Environments](https://arxiv.org/abs/2506.23468)** | 2025 arXiv |

### Inverse Dynamics Modeling and Causality
#### Inverse Dynamics
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[ImagiNav: Scalable Embodied Navigation via Generative Visual Prediction and Inverse Dynamics](https://arxiv.org/abs/2603.13833)** | 2026 arXiv |
| 2026 | **[NaVIDA: Vision-Language Navigation with Inverse Dynamics Augmentation](https://arxiv.org/abs/2601.18188)** | 2026 arXiv |

#### Causal Learning
| Year | Paper | Venue |
|---:|---|---|
| 2025 | **[CVLN-Think: Causal Inference with Counterfactual Style Adaptation for Continuous Vision-and-Language Navigation](https://doi.org/10.1109/IROS60139.2025.11247004)** | 2025 IROS |
| 2024 | **[Causality-based cross-modal representation learning for vision-and-language navigation](https://arxiv.org/abs/2403.03405)** | 2024 arXiv |
| 2024 | **[Vision-and-Language Navigation via Causal Learning](https://openaccess.thecvf.com/content/CVPR2024/html/Wang_Vision-and-Language_Navigation_via_Causal_Learning_CVPR_2024_paper.html)** | 2024 CVPR |
| 2022 | **[Counterfactual Cycle-Consistent Learning for Instruction Following and Generation in Vision-Language Navigation](https://arxiv.org/abs/2203.16586)** | 2022 CVPR |

## 🎯 Decision Planning
### Structured Decision
#### Instruction Decomposition
| Year | Paper | Venue |
|---:|---|---|
| 2025 | **[Constraint-aware zero-shot vision-language navigation in continuous environments](https://arxiv.org/abs/2412.10137)** | 2025 TPAMI |
| 2025 | **[GC-VLN: Instruction as graph constraints for training-free vision-and-language navigation](https://arxiv.org/abs/2509.10454)** | 2025 arXiv |
| 2024 | **[Boosting efficient reinforcement learning for vision-and-language navigation with open-sourced llm](https://ieeexplore.ieee.org/document/10777561)** | 2024 RA-L |

#### Sub-Goal Formulation
| Year | Paper | Venue |
|---:|---|---|
| 2025 | **[Landmark-Guided Knowledge for Vision-and-Language Navigation](https://arxiv.org/abs/2509.25655)** | 2025 ICIC |
| 2025 | **[Affordances-oriented planning using foundation models for continuous vision-language navigation](https://arxiv.org/abs/2407.05890)** | 2025 AAAI |
| 2025 | **[Ground Slow, Move Fast: A Dual-System Foundation Model for Generalizable Vision-and-Language Navigation](https://arxiv.org/abs/2512.08186)** | 2025 arXiv |
| 2025 | **[Hierarchical semantic-augmented navigation: Optimal transport and graph-driven reasoning for vision-language navigation](https://neurips.cc/virtual/2025/poster/115108)** | 2025 NeurIPS |
| 2025 | **[SmartWay: Enhanced Waypoint Prediction and Backtracking for Zero-Shot Vision-and-Language Navigation](https://arxiv.org/abs/2503.10069)** | 2025 IROS |

#### Navigation Progress Estimation
| Year | Paper | Venue |
|---:|---|---|
| 2024 | **[PASTS: Progress-Aware Spatio-Temporal Transformer Speaker for Vision-and-Language Navigation](https://arxiv.org/abs/2305.11918)** | 2024 EAAI |
| 2022 | **[One step at a time: Long-horizon vision-and-language navigation with milestones](https://arxiv.org/abs/2202.07028)** | 2022 CVPR |
| 2020 | **[Vision-Language Navigation with Self-Supervised Auxiliary Reasoning Tasks](https://arxiv.org/abs/1911.07883)** | 2020 CVPR |
| 2019 | **[The regretful agent: Heuristic-aided navigation through progress estimation](https://arxiv.org/abs/1903.01602)** | 2019 CVPR |
| 2019 | **[Self-monitoring navigation agent via auxiliary progress estimation](https://arxiv.org/abs/1901.03035)** | 2019 ICLR |

### Reasoning-based Decision
#### LLM as External Reasoner
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[ReasonNavi: Human-Inspired Global Map Reasoning for Zero-Shot Embodied Navigation](https://arxiv.org/abs/2602.15864)** | 2026 arXiv |
| 2025 | **[SpatialGPT: Zero-Shot Vision-and-Language Navigation via Spatial CoT over Structured Spatial Memory](https://doi.org/10.1145/3748636.3762753)** | 2025 SIGSPATIAL |
| 2025 | **[GeoNav: Empowering MLLMs with Explicit Geospatial Reasoning Abilities for Language-Goal Aerial Navigation](https://arxiv.org/abs/2504.09587)** | 2025 arXiv |
| 2024 | **[NavGPT-2: Unleashing Navigational Reasoning Capability for Large Vision-Language Models](https://arxiv.org/abs/2407.12366)** | 2024 ECCV |
| 2024 | **[NavGPT: Explicit Reasoning in Vision-and-Language Navigation with Large Language Models](https://arxiv.org/abs/2305.16986)** | 2024 AAAI |
| 2024 | **[End-to-end navigation with vision language models: Transforming spatial reasoning into question-answering](https://arxiv.org/abs/2411.05755)** | 2024 arXiv |
| 2024 | **[InstructNav: Zero-Shot System for Generic Instruction Navigation in Unexplored Environment](https://arxiv.org/abs/2406.04882)** | 2024 arXiv |

#### Integrated Perception-Reasoning-Action Model
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[AgentVLN: Towards Agentic Vision-and-Language Navigation](https://arxiv.org/abs/2603.17670)** | 2026 arXiv |
| 2026 | **[HiRO-Nav: Hybrid Reasoning Enables Efficient Embodied Navigation](https://arxiv.org/abs/2604.08232)** | 2026 arXiv |
| 2026 | **[ABot-N0: Technical Report on the VLA Foundation Model for Versatile Embodied Navigation](https://arxiv.org/abs/2602.11598)** | 2026 arXiv |
| 2026 | **[VLingNav: Embodied Navigation with Adaptive Reasoning and Visual-Assisted Linguistic Memory](https://arxiv.org/abs/2601.08665)** | 2026 arXiv |
| 2025 | **[AdaNav: Adaptive Reasoning with Uncertainty for Vision-Language Navigation](https://arxiv.org/abs/2509.24387)** | 2025 arXiv |
| 2025 | **[Aux-Think: Exploring Reasoning Strategies for Data-Efficient Vision-Language Navigation](https://arxiv.org/abs/2505.11886)** | 2025 arXiv |
| 2025 | **[D3D-VLP: Dynamic 3D Vision-Language-Planning Model for Embodied Grounding and Navigation](https://arxiv.org/abs/2512.12622)** | 2025 arXiv |
| 2025 | **[CompassNav: Steering from Path Imitation to Decision Understanding in Navigation](https://arxiv.org/abs/2510.10154)** | 2025 arXiv |
| 2025 | **[MobileVLA-R1: Reinforcing Vision-Language-Action for Mobile Robots](https://arxiv.org/abs/2511.17889)** | 2025 arXiv |
| 2025 | **[Nav-r1: Reasoning and navigation in embodied scenes](https://arxiv.org/abs/2509.10884)** | 2025 arXiv |
| 2025 | **[NavCoT: Boosting LLM-based Vision-and-Language Navigation via Learning Disentangled Reasoning](https://arxiv.org/abs/2403.07376)** | 2025 TPAMI |
| 2025 | **[OctoNav: Towards Generalist Embodied Navigation](https://arxiv.org/abs/2506.09839)** | 2025 arXiv |

#### Predictive Reasoning Model
| Year | Paper | Venue |
|---:|---|---|
| 2025 | **[ImagineNav++: Prompting Vision-Language Models as Embodied Navigator through Scene Imagination](https://arxiv.org/abs/2512.17435)** | 2025 arXiv |

### Hierarchical Decision
#### High-Level System
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[OpenFrontier: General Navigation with Visual-Language Grounded Frontiers](https://arxiv.org/abs/2603.05377)** | 2026 arXiv |
| 2025 | **[Breaking down and building up: Mixture of skill-based vision-and-language navigation agents](https://arxiv.org/abs/2508.07642)** | 2025 arXiv |
| 2024 | **[ETPNav: Evolving Topological Planning for Vision-Language Navigation in Continuous Environments](https://arxiv.org/abs/2304.03047)** | 2024 TPAMI |
| 2024 | **[VLFM: Vision-Language Frontier Maps for Zero-Shot Semantic Navigation](https://arxiv.org/abs/2312.03275)** | 2024 ICRA |
| 2022 | **[Think Global, Act Local: Dual-Scale Graph Transformer for Vision-and-Language Navigation](https://arxiv.org/abs/2202.11742)** | 2022 CVPR |

#### Low-Level System
| Year | Paper | Venue |
|---:|---|---|
| 2025 | **[LoGoPlanner: Localization Grounded Navigation Policy with Metric-aware Visual Geometry](https://arxiv.org/abs/2512.19629)** | 2025 arXiv |
| 2025 | **[LaViRA: Language-Vision-Robot Actions Translation for Zero-Shot Vision Language Navigation in Continuous Environments](https://arxiv.org/abs/2510.19655)** | 2025 arXiv |
| 2024 | **[NoMaD: Goal Masked Diffusion Policies for Navigation and Exploration](https://arxiv.org/abs/2310.07896)** | 2024 ICRA |
| 2024 | **[ViPlanner: Visual Semantic Imperative Learning for Local Navigation](https://www.research-collection.ethz.ch/handle/20.500.11850/722589)** | 2024 ICRA |
| 2023 | **[iPlanner: Imperative Path Planning](https://arxiv.org/abs/2302.11434)** | 2023 arXiv |
| 2022 | **[Learning Forward Dynamics Model and Informed Trajectory Sampler for Safe Quadruped Navigation](https://roboticsconference.org/2022/program/papers/069/)** | 2022 RSS |
| 2020 | **[DD-PPO: Learning Near-Perfect PointGoal Navigators from 2.5 Billion Frames](https://openreview.net/forum?id=H1gX8C4YPr)** | 2020 ICLR |

#### Hybrid Architecture
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[TIC-VLA: A Think-in-Control Vision-Language-Action Model for Robot Navigation in Dynamic Environments](https://arxiv.org/abs/2602.02459)** | 2026 arXiv |
| 2025 | **[InternVLA-N1: An Open Dual-System Navigation Foundation Model with Learned Latent Plans](https://internrobotics.github.io/internvla-n1.github.io/)** | 2025 arXiv |
| 2025 | **[OmniNav: A Unified Framework for Prospective Exploration and Visual-Language Navigation](https://arxiv.org/abs/2509.25687)** | 2025 arXiv |
| 2025 | **[FlexVLN: Flexible Adaptation for Diverse Vision-and-Language Navigation Tasks](https://arxiv.org/abs/2503.13966)** | 2025 arXiv |

## ⚠️ Reflection from Error
### Sources and Taxonomy of Errors in VLN
#### Instruction Errors
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[VLN-NF: Feasibility-Aware Vision-and-Language Navigation with False-Premise Instructions](https://arxiv.org/abs/2604.10533)** | 2026 arXiv |

#### Perceptual Errors
- Covered by papers already listed above.

#### Planning and Decision Errors
- Covered by papers already listed above.

### Error Prevention
#### Prevent Instruction Errors
| Year | Paper | Venue |
|---:|---|---|
| 2025 | **[Seeing with Partial Certainty: Conformal Prediction for Robotic Scene Recognition in Built Environments](https://arxiv.org/abs/2501.04947)** | 2025 arXiv |
| 2024 | **[I2EDL: Interactive Instruction Error Detection and Localization](https://arxiv.org/abs/2406.05080)** | 2024 RO-MAN |

#### Prevent Perception Errors
- Covered by papers already listed above.

#### Prevent Planning and Decision Errors
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[EvolveNav: Empowering LLM-Based Vision-Language Navigation via Self-Improving Embodied Reasoning](https://arxiv.org/abs/2506.01551)** | 2026 TPAMI |
| 2026 | **[SeqWalker: Sequential-Horizon Vision-and-Language Navigation with Hierarchical Planning](https://arxiv.org/abs/2601.04699)** | 2026 arXiv |

### Learn From Error
#### Distribution Alignment
| Year | Paper | Venue |
|---:|---|---|
| 2025 | **[CAST: Counterfactual Labels Improve Instruction Following in Vision-Language-Action Models](https://arxiv.org/abs/2508.13446)** | 2025 arXiv |
| 2024 | **[Vision-Language Navigation with Energy-Based Policy](https://arxiv.org/abs/2410.14250)** | 2024 NeurIPS |

#### DAgger-based
| Year | Paper | Venue |
|---:|---|---|
| 2025 | **[CorrectNav: Self-Correction Flywheel Empowers Vision-Language-Action Navigation Model](https://arxiv.org/abs/2508.10416)** | 2025 arXiv |
| 2025 | **[DAgger Diffusion Navigation: DAgger Boosted Diffusion Policy for Vision-Language Navigation](https://arxiv.org/abs/2508.09444)** | 2025 arXiv |

#### Exploration-based
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[Let's Reward Step-by-Step: Step-Aware Contrastive Alignment for Vision-Language Navigation in Continuous Environments](https://arxiv.org/abs/2603.09740)** | 2026 arXiv |
| 2026 | **[Nipping the Drift in the Bud: Retrospective Rectification for Robust Vision-Language Navigation](https://arxiv.org/abs/2602.06356)** | 2026 arXiv |
| 2026 | **[Trajectory-Diversity-Driven Robust Vision-and-Language Navigation](https://arxiv.org/abs/2603.15370)** | 2026 arXiv |
| 2025 | **[SeeNav-Agent: Enhancing Vision-Language Navigation with Visual Prompt and Step-Level Policy Optimization](https://arxiv.org/abs/2512.02631)** | 2025 arXiv |

#### Test-time Adaptation
| Year | Paper | Venue |
|---:|---|---|
| 2025 | **[Active Test-time Vision-Language Navigation](https://arxiv.org/abs/2506.06630)** | 2025 arXiv |
| 2025 | **[Test-Time Adaptation for Online Vision-Language Navigation with Feedback-based Reinforcement Learning](https://proceedings.mlr.press/v267/kim25ad.html)** | 2025 ICML |
| 2023 | **[Fast-slow test-time adaptation for online vision-and-language navigation](https://arxiv.org/abs/2311.13209)** | 2023 arXiv |


## 🌐 Broader Navigation Literature

### Surveys and Evaluation
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[A comprehensive review of recent advancements in vision-and-language navigation](https://link.springer.com/article/10.1007/s10791-026-09977-z)** | 2026 Discover Computing |
| 2026 | **[Robot Navigation via Foundation Language Models: A Review](https://doi.org/10.1145/3802539)** | 2026 ACM CSUR |
| 2024 | **[Vision-and-language navigation today and tomorrow: A survey in the era of foundation models](https://arxiv.org/abs/2407.07035)** | 2024 arXiv |
| 2024 | **[Vision-language navigation: a survey and taxonomy](https://doi.org/10.1007/s00521-023-09217-1)** | 2024 Neural Computing and Applications |
| 2023 | **[Advances in embodied navigation using large language models: A survey](https://arxiv.org/abs/2311.00530)** | 2023 arXiv |
| 2023 | **[Visual language navigation: A survey and open challenges](https://doi.org/10.1007/s10462-022-10174-9)** | 2023 Artificial Intelligence Review |
| 2022 | **[Vision-and-language navigation: A survey of tasks, methods, and future directions](https://aclanthology.org/2022.acl-long.524/)** | 2022 ACL |
| 2023 | **[A2Nav: Action-Aware Zero-Shot Robot Navigation by Exploiting Vision-and-Language Ability of Foundation Models](https://arxiv.org/abs/2308.07997)** | 2023 arXiv |
| 2019 | **[General evaluation for instruction conditioned navigation using dynamic time warping](https://arxiv.org/abs/1907.05446)** | 2019 arXiv |
| 2018 | **[On evaluation of embodied navigation agents](https://arxiv.org/abs/1807.06757)** | 2018 arXiv |

### Platforms, Benchmarks, and Embodied Environments
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[CoNavBench: Collaborative Long-Horizon Vision-Language Navigation Benchmark](https://openreview.net/forum?id=bMrH2PFMsi)** | 2026 ICLR |
| 2026 | **[Habitat-GS: A High-Fidelity Navigation Simulator with Dynamic Gaussian Splatting](https://arxiv.org/abs/2604.12626)** | 2026 arXiv |
| 2026 | **[NavGSim: High-Fidelity Gaussian Splatting Simulator for Large-Scale Navigation](https://arxiv.org/abs/2603.15186)** | 2026 arXiv |
| 2026 | **[Explore with Long-term Memory: A Benchmark and Multimodal LLM-based Reinforcement Learning Framework for Embodied Exploration](https://arxiv.org/abs/2601.10744)** | 2026 arXiv |
| 2025 | **[UrbanNav: Learning Language-Guided Urban Navigation from Web-Scale Human Trajectories](https://arxiv.org/abs/2512.09607)** | 2025 arXiv |
| 2025 | **[UAV-Flow Colosseo: A Real-World Benchmark for Flying-on-a-Word UAV Imitation Learning](https://arxiv.org/abs/2505.15725)** | 2025 arXiv |
| 2024 | **[Embodiedcity: A benchmark platform for embodied agent in real-world city environment](https://arxiv.org/abs/2410.09604)** | 2024 arXiv |
| 2023 | **[Habitat 3.0: A co-habitat for humans, avatars and robots](https://arxiv.org/abs/2310.13724)** | 2023 arXiv |
| 2021 | **[Talk2Nav: Long-Range Vision-and-Language Navigation with Dual Attention and Spatial Memory](https://link.springer.com/article/10.1007/s11263-020-01374-3)** | 2021 IJCV |

### General Navigation and Object Navigation
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[Hydra-Nav: Object Navigation via Adaptive Dual-Process Reasoning](https://arxiv.org/abs/2602.09972)** | 2026 arXiv |
| 2026 | **[MerNav: A Highly Generalizable Memory-Execute-Review Framework for Zero-Shot Object Goal Navigation](https://arxiv.org/abs/2602.05467)** | 2026 arXiv |
| 2025 | **[SocialNav-Map: Dynamic Mapping with Human Trajectory Prediction for Zero-Shot Social Navigation](https://arxiv.org/abs/2511.12232)** | 2025 arXiv |
| 2025 | **[NavSpace: How Navigation Agents Follow Spatial Intelligence Instructions](https://arxiv.org/abs/2510.08173)** | 2025 arXiv |
| 2025 | **[C-NAV: Towards self-evolving continual object navigation in open world](https://arxiv.org/abs/2510.20685)** | 2025 arXiv |
| 2025 | **[RANGER: A Monocular Zero-Shot Semantic Navigation Framework through Contextual Adaptation](https://arxiv.org/abs/2512.24212)** | 2025 arXiv |
| 2025 | **[3D-Mem: 3D Scene Memory for Embodied Exploration and Reasoning](https://arxiv.org/abs/2411.17735)** | 2025 arXiv |
| 2024 | **[TopV-Nav: Unlocking the top-view spatial reasoning potential of MLLM for zero-shot object navigation](https://arxiv.org/abs/2411.16425)** | 2024 arXiv |
| 2023 | **[ViNT: A foundation model for visual navigation](https://arxiv.org/abs/2306.14846)** | 2023 arXiv |
| 2022 | **[GNM: A general navigation model to drive any robot](https://arxiv.org/abs/2210.03370)** | 2022 arXiv |

### Policies, Efficiency, and Applied Navigation
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[P3Nav: End-to-End Perception, Prediction and Planning for Vision-and-Language Navigation](https://arxiv.org/abs/2603.17459)** | 2026 arXiv |
| 2026 | **[Beyond Imitation: Reinforcement Learning Fine-Tuning for Adaptive Diffusion Navigation Policies](https://arxiv.org/abs/2603.12868)** | 2026 arXiv |
| 2025 | **[OmniVLA: An omni-modal vision-language-action model for robot navigation](https://arxiv.org/abs/2509.19480)** | 2025 arXiv |
| 2025 | **[NavDP: Learning sim-to-real navigation diffusion policy with privileged information guidance](https://arxiv.org/abs/2505.08712)** | 2025 arXiv |
| 2025 | **[Nav-EE: Navigation-Guided Early Exiting for Efficient Vision-Language Models in Autonomous Driving](https://arxiv.org/abs/2510.01795)** | 2025 arXiv |
| 2025 | **[EgoPrune: Efficient token pruning for egomotion video reasoning in embodied agent](https://arxiv.org/abs/2507.15428)** | 2025 arXiv |

## 🚀 Future Directions
Representative outlook papers explicitly discussed in the manuscript are listed below.

### Toward Action-Aware Policies
- Action grounding beyond static image-text reasoning.

### Toward Visual Predictive CoT
- Reasoning grounded in predicted visual futures.

### Towards Unified Visual Geometry Navigation Model
- Tighter coupling between geometry and policy learning.

### Towards Dynamic Environment
| Year | Paper | Venue |
|---:|---|---|
| 2025 | **[From Cognition to Precognition: A Future-Aware Framework for Social Navigation](https://arxiv.org/abs/2409.13244)** | 2025 ICRA |
| 2025 | **[HA-VLN: A Benchmark for Human-Aware Navigation in Discrete-Continuous Environments with Dynamic Multi-Human Interactions, Real-World Validation, and an Open Leaderboard](https://arxiv.org/abs/2503.14229)** | 2025 arXiv |
| 2025 | **[VLN-ChEnv: Vision-language Navigation in Changeable Environments](https://doi.org/10.1145/3746027.3755202)** | 2025 ACM MM |
| 2024 | **[VLM-Social-Nav: Socially Aware Robot Navigation through Scoring using Vision-Language Models](https://arxiv.org/abs/2404.00210)** | 2024 RA-L |

### Towards Collaborative VLN
| Year | Paper | Venue |
|---:|---|---|
| 2026 | **[CA-VLN: Collaborative Agents in MLLM-Powered Visual-Language Navigation](https://www.mdpi.com/1424-8220/26/4/1254)** | 2026 Sensors |
| 2026 | **[MA-CoNav: A Master-Slave Multi-Agent Framework with Hierarchical Collaboration and Dual-Level Reflection for Long-Horizon Embodied VLN](https://arxiv.org/abs/2603.03024)** | 2026 arXiv |
| 2025 | **[Enhancing Multi-Robot Semantic Navigation through Multimodal Chain-of-Thought Score Collaboration](https://arxiv.org/abs/2412.18292)** | 2025 AAAI |
| 2023 | **[Co-NavGPT: Multi-Robot Cooperative Visual Semantic Navigation Using Vision Language Models](https://arxiv.org/abs/2310.07937)** | 2023 arXiv |

## 📊 Statistics
- Curated papers in current README: **205**
- 📚 Preliminaries: **32**
- 🧠 Context Modeling: **35**
- 🔮 Imaginative Prediction: **30**
- 🎯 Decision Planning: **49**
- ⚠️ Reflection from Error: **16**
- 🌐 Broader Navigation Literature: **35**
- 🚀 Future Directions: **8**