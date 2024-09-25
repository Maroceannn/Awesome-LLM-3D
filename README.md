
# LLM-3D-Generation 


## 🏠 About
Here is a curated list of papers about LLM-3D-Generation. 
The repository is forked from [Awesome-LLM-3D](https://yashbhalgat.github.io/).


## Table of Content

- [Awesome-LLM-3D](#awesome-llm-3d)
  - [3D Scene Generation](#3d-scene-generation)
  - [3D Understanding (other Foundation Models)](#3d-understanding-via-other-foundation-models)
  - [3D Reasoning](#3d-reasoning)
  - [3D Generation](#3d-generation)
  - [3D Embodied Agent](#3d-embodied-agent)
  - [3D Benchmarks](#3d-benchmarks)
  - [Contributing](#contributing)



## 3D Scene Generation

|  Date |       Keywords       | Paper                                                                                                                                                                               | Publication | Project | Code |
| :-----: | :------------------: | :--------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------: |
| 2 Feb 2023 | SceneScape | [SceneScape: Text-Driven Consistent Scene Generation](https://arxiv.org/abs/2302.01133) | NeurIPS 2023 | [project](https://scenescape.github.io/) | [code](https://github.com/RafailFridman/SceneScape) |
| 21 Mar 2023 | Text2Room | [Text2Room: Extracting Textured 3D Meshes from 2D Text-to-Image Models](https://arxiv.org/abs/2303.11989) | ICCV 2023 | [project](https://lukashoel.github.io/text-to-room/) | [code](https://github.com/lukasHoel/text2room) |
| 22 Nov 2023 | LucidDreamer | [LucidDreamer: Domain-free Generation of 3D Gaussian Splatting Scenes](https://arxiv.org/abs/2311.13384) | Arxiv 2023 | [project](https://luciddreamer-cvlab.github.io/) | [code](https://github.com/luciddreamer-cvlab/LucidDreamer) |
| 19 May 2023 | Text2NeRF | [Text2NeRF: Text-Driven 3D Scene Generation with Neural Radiance Fields](https://arxiv.org/abs/2305.11588) | TVCG 2024
 | [project](https://eckertzhang.github.io/Text2NeRF.github.io/) | [code](https://github.com/eckertzhang/Text2NeRF) |
| 14 Dec 2023 | Text2Immersion | [Text2Immersion: Generative Immersive Scene with 3D Gaussians]([Text2Immersion: Generative Immersive Scene with 3D Gaussians)](https://arxiv.org/abs/2312.09242)) | Arxiv 2023 | [project](https://ken-ouyang.github.io/text2immersion/index.html) |  |
| 10 Apr 2024 | DreamScene360 | [DreamScene360: Unconstrained Text-to-3D Scene Generation with Panoramic Gaussian Splatting](https://arxiv.org/abs/2404.06903) | ECCV 2024 | [project](https://dreamscene360.github.io/) |  |
| 9 May 2024 | FastScene | [FastScene: Text-Driven Fast 3D Indoor Scene Generation via Panoramic Gaussian Splatting](https://arxiv.org/abs/2405.05768) | IJCAI 2024 |  | [code](https://github.com/Mr-Ma-yikun/FastScene) |
| 4 Jun 2024 | RoomTex | [RoomTex: Texturing Compositional Indoor Scenes via Iterative Inpainting](https://web3.arxiv.org/abs/2406.02461) | ECCV 2024 | [project](https://qwang666.github.io/RoomTex/) | [code](https://github.com/qwang666/RoomTex-) |
| 21 Jul 2024 | HoloDreamer | [HoloDreamer: Holistic 3D Panoramic World Generation from Text Descriptions](https://arxiv.org/abs/2407.15187) | Arxiv 2024 | [project](https://zhouhyocean.github.io/holodreamer/) |  |
| 25 Aug 2024 | SceneDreamer360 | [SceneDreamer360: Text-Driven 3D-Consistent Scene Generation with Panoramic Gaussian Splatting](https://arxiv.org/abs/2408.13711) | Arxiv 2024 | [project](https://scenedreamer360.github.io/) | [code](https://github.com/liwrui/SceneDreamer360) |



## 3D Understanding via other Foundation Models
|  ID |       keywords       |    Institute (first)    | Paper                                                                                                                                                                               | Publication | Others |
| :-----: | :------------------: | :--------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------: 
| 2024-04-07 |  Any2Point |    Shanghai AI Lab  | [Any2Point: Empowering Any-modality Large Models for Efficient 3D Understanding](https://arxiv.org/pdf/2404.07989) | ECCV 2024 | [github](https://github.com/Ivan-Tang-3D/Any2Point) |
| 2024-03-16 |  N2F2 |    Oxford-VGG  | [N2F2: Hierarchical Scene Understanding with Nested Neural Feature Fields](https://arxiv.org/pdf/2403.10997.pdf) | Arxiv | - |
| 2023-12-17 |  SAI3D |    PKU  | [SAI3D: Segment Any Instance in 3D Scenes](https://arxiv.org/pdf/2312.11557.pdf)                                                                                | Arxiv | [project](https://yd-yin.github.io/SAI3D) |
| 2023-12-17 |  Open3DIS |    VinAI  | [Open3DIS: Open-vocabulary 3D Instance Segmentation with 2D Mask Guidance](https://arxiv.org/pdf/2312.10671.pdf)                                                                                | Arxiv | [project](https://open3dis.github.io/) |
| 2023-11-6 |  OVIR-3D |    Rutgers University  | [OVIR-3D: Open-Vocabulary 3D Instance Retrieval Without Training on 3D Data](https://arxiv.org/pdf/2311.02873.pdf) | CoRL '23 | [github](https://github.com/shiyoung77/OVIR-3D/) |
| 2023-10-29|  OpenMask3D |    ETH  | [OpenMask3D: Open-Vocabulary 3D Instance Segmentation](https://openmask3d.github.io/static/pdf/openmask3d.pdf)                                                                                | NeurIPS '23 | [project](https://openmask3d.github.io/) |
| 2023-10-5 |     Open-Fusion     |      -     | [Open-Fusion: Real-time Open-Vocabulary 3D Mapping and Queryable Scene Representation](https://arxiv.org/pdf/2310.03923.pdf)                                                                            |Arxiv|  [github](https://github.com/UARK-AICV/OpenFusion) |
| 2023-9-22 |  OV-3DDet |    HKUST  | [CoDA: Collaborative Novel Box Discovery and Cross-modal Alignment for Open-vocabulary 3D Object Detection](https://arxiv.org/pdf/2310.02960.pdf)                                                                                | NeurIPS '23 | [github](https://github.com/yangcaoai/CoDA_NeurIPS2023) |
| 2023-9-19 | LAMP |      -      | [From Language to 3D Worlds: Adapting Language Model for Point Cloud Perception](https://openreview.net/forum?id=H49g8rRIiF)                                                              |    OpenReview     | - |
| 2023-9-15 |  OpenNerf |    -    | [OpenNerf: Open Set 3D Neural Scene Segmentation with Pixel-Wise Features and Rendered Novel Views](https://openreview.net/pdf?id=SgjAojPKb3)                                                                                | OpenReview | [github]() |
| 2023-9-1|  OpenIns3D |    Cambridge  | [OpenIns3D: Snap and Lookup for 3D Open-vocabulary Instance Segmentation](https://arxiv.org/pdf/2309.00616.pdf)                                                                                | Arxiv | [project](https://zheninghuang.github.io/OpenIns3D/) |
| 2023-6-7 |         Contrastive Lift         |     Oxford-VGG     | [Contrastive Lift: 3D Object Instance Segmentation by Slow-Fast Contrastive Fusion](https://arxiv.org/pdf/2306.04633.pdf)                                                                                        |   NeurIPS '23| [github](https://github.com/yashbhalgat/Contrastive-Lift) |
| 2023-6-4 |  Multi-CLIP |    ETH  | [Multi-CLIP: Contrastive Vision-Language Pre-training for Question Answering tasks in 3D Scenes](https://arxiv.org/pdf/2306.02329.pdf)                                                                                | Arxiv | - |
| 2023-5-23 |  3D-OVS |    NTU  | [Weakly Supervised 3D Open-vocabulary Segmentation](https://arxiv.org/pdf/2305.14093.pdf)                                                                                | NeurIPS '23 | [github](https://github.com/Kunhao-Liu/3D-OVS) |
| 2023-5-21 |  VL-Fields |    University of Edinburgh  | [VL-Fields: Towards Language-Grounded Neural Implicit Spatial Representations](https://arxiv.org/pdf/2305.12427.pdf)                                                                                | ICRA '23 | [project](https://tsagkas.github.io/vl-fields/)  |
| 2023-5-8 |  CLIP-FO3D |    Tsinghua University  | [CLIP-FO3D: Learning Free Open-world 3D Scene Representations from 2D Dense CLIP](https://arxiv.org/pdf/2303.04748.pdf)                                                                                | ICCVW '23 | - |
| 2023-4-12 |  3D-VQA |    ETH  | [CLIP-Guided Vision-Language Pre-training for Question Answering in 3D Scenes](https://arxiv.org/pdf/2304.06061.pdf)                                                                                | CVPRW '23 | [github](https://github.com/AlexDelitzas/3D-VQA) |
| 2023-4-3 |  RegionPLC |    HKU | [RegionPLC: Regional Point-Language Contrastive Learning for Open-World 3D Scene Understanding](https://arxiv.org/pdf/2304.00962.pdf)                                                                                | Arxiv | [project](https://jihanyang.github.io/projects/RegionPLC) |
| 2023-3-20 |        CG3D        |      JHU      | [CLIP goes 3D: Leveraging Prompt Tuning for Language Grounded 3D Recognition](https://arxiv.org/pdf/2303.11313.pdf)                                                                                                 |Arxiv|  [github](https://github.com/deeptibhegde/CLIP-goes-3D) |
| 2023-3-16 | LERF |     UC Berkeley     | [LERF: Language Embedded Radiance Fields](https://arxiv.org/pdf/2303.09553.pdf)                                                   | ICCV '23   | [github](https://github.com/kerrj/lerf) |
| 2023-2-14 |  ConceptFusion |    MIT  | [ConceptFusion: Open-set Multimodal 3D Mapping](https://arxiv.org/pdf/2302.07241.pdf)                                                                                | RSS '23 | [project](https://concept-fusion.github.io/) |
| 2023-1-12 |         CLIP2Scene         |      HKU      | [CLIP2Scene: Towards Label-efficient 3D Scene Understanding by CLIP](https://arxiv.org/pdf/2301.04926.pdf)                                                                                        |    CVPR '23 | [github](https://github.com/runnanchen/CLIP2Scene) |
| 2022-12-1 |         UniT3D         |      TUM     | [UniT3D: A Unified Transformer for 3D Dense Captioning and Visual Grounding](https://openaccess.thecvf.com/content/ICCV2023/papers/Chen_UniT3D_A_Unified_Transformer_for_3D_Dense_Captioning_and_Visual_ICCV_2023_paper.pdf)                                                                          |   ICCV '23| [github]() |
| 2022-11-29 |        PLA        |     HKU    | [PLA: Language-Driven Open-Vocabulary 3D Scene Understanding](https://arxiv.org/pdf/2211.16312.pdf)                                                                 |CVPR '23|  [github](https://github.com/CVMI-Lab/PLA) |
| 2022-11-28 |       OpenScene       |      ETHz      | [OpenScene: 3D Scene Understanding with Open Vocabularies](https://arxiv.org/pdf/2211.15654.pdf)                                                             |   CVPR '23  | [github](https://github.com/pengsongyou/openscene) |
| 2022-10-11 |  CLIP-Fields |    NYU  | [CLIP-Fields: Weakly Supervised Semantic Fields for Robotic Memory](https://arxiv.org/pdf/2210.05663.pdf)                                                                                | Arxiv | [project](https://mahis.life/clip-fields/) |
| 2022-7-23 |  Semantic Abstraction |    Columbia  | [Semantic Abstraction: Open-World 3D Scene Understanding from 2D Vision-Language Models](https://arxiv.org/pdf/2207.11514.pdf)                                                                                | CoRL '22 | [project](https://semantic-abstraction.cs.columbia.edu/) |
| 2022-4-26 |   ScanNet200 |    TUM  | [Language-Grounded Indoor 3D Semantic Segmentation in the Wild](https://arxiv.org/pdf/2204.07761.pdf)                                                                                | ECCV '22 | [project](https://rozdavid.github.io/scannet200) |




## 3D Reasoning
|  Date |       keywords       |    Institute (first)    | Paper                                                                                                                                                                               | Publication | Others |
| :-----: | :------------------: | :--------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------: 
| 2023-5-20|       3D-CLR      |      UCLA     | [3D Concept Learning and Reasoning from Multi-View Images](https://arxiv.org/pdf/2303.11327.pdf)                                                 |   CVPR '23  | [github](https://github.com/evelinehong/3D-CLR-Official) |
| - |         Transcribe3D         |     TTI, Chicago     | [Transcribe3D: Grounding LLMs Using Transcribed Information for 3D Referential Reasoning with Self-Corrected Finetuning](https://openreview.net/pdf?id=7j3sdUZMTF)                                                                                                  |CoRL '23|  [github]() |


## 3D Generation
|  Date |       keywords       |    Institute    | Paper                                                                                                                                                                               | Publication | Others |
| :-----: | :------------------: | :--------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------: 
| 2023-11-29 |         ShapeGPT         |     Fudan University     | [ShapeGPT: 3D Shape Generation with A Unified Multi-modal Language Model](https://arxiv.org/pdf/2311.17618.pdf)                                                                                                  |Arxiv|  [github](https://github.com/OpenShapeLab/ShapeGPT) |                                                                                              | Arxiv  |  [github]() |
| 2023-11-27|         MeshGPT         |     TUM     | [MeshGPT: Generating Triangle Meshes with Decoder-Only Transformers](https://arxiv.org/pdf/2311.15475.pdf)                                                                                                  |Arxiv |  [project](https://nihalsid.github.io/mesh-gpt/) |
| 2023-10-19 |         3D-GPT        |     ANU   | [3D-GPT: Procedural 3D Modeling with Large Language Models](https://arxiv.org/pdf/2310.12945.pdf)                                                                                                   |Arxiv|  [github](https://dreamllm.github.io/) |
| 2023-9-21 |         LLMR         |     MIT     | [LLMR: Real-time Prompting of Interactive Worlds using Large Language Models](https://arxiv.org/pdf/2309.12276.pdf)                                                                                                  |Arxiv|  [github]() |
| 2023-9-20 |         DreamLLM         |     MEGVII    | [DreamLLM: Synergistic Multimodal Comprehension and Creation](https://arxiv.org/pdf/2309.11499.pdf) | Arxiv | [github](https://github.com/RunpeiDong/DreamLLM)
| 2023-4-1 |      ChatAvatar      |       Deemos Tech            | [DreamFace: Progressive Generation of Animatable 3D Faces under Text Guidance](https://dl.acm.org/doi/abs/10.1145/3592094)                                               |  ACM TOG    | [website](https://hyperhuman.deemos.com/) |

## 3D Embodied Agent
|  Date |       keywords       |    Institute   | Paper                                                                                                                                                                               | Publication | Others |
| :-----: | :------------------: | :--------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------: 
| 2024-01-22 |  SpatialVLM |    Deepmind  | [SpatialVLM: Endowing Vision-Language Models with Spatial Reasoning Capabilities](https://arxiv.org/abs/2401.12168)                                                                                | CVPR '24 | [project](https://spatial-vlm.github.io/) |
| 2023-11-27 | Dobb-E | NYU | [On Bringing Robots Home](https://arxiv.org/pdf/2311.16098.pdf)        |    Arxiv  |  [github](https://github.com/notmahi/dobb-e) |
| 2023-11-26 | STEVE | ZJU | [See and Think: Embodied Agent in Virtual Environment](https://arxiv.org/abs/2311.15209) | Arxiv | [github](https://github.com/rese1f/STEVE) |
| 2023-11-18 | LEO  |   BIGAI  | [An Embodied Generalist Agent in 3D World](https://arxiv.org/pdf/2311.12871.pdf)   |    Arxiv  |  [github](https://github.com/embodied-generalist/embodied-generalist) |
| 2023-9-14 |        UniHSI      |      Shanghai AI Lab     | [Unified Human-Scene Interaction via Prompted Chain-of-Contacts](https://arxiv.org/pdf/2309.07918.pdf)                                                                                                 |   Arxiv |  [github](https://github.com/OpenRobotLab/UniHSI) |
| 2023-7-28 |         RT-2         |     Google-DeepMind     | [RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control](https://arxiv.org/pdf/2307.15818.pdf)                                                                                                  |Arxiv|  [github](https://robotics-transformer2.github.io/) |
| 2023-7-12 |         SayPlan        |     QUT Centre for Robotics    | [SayPlan: Grounding Large Language Models using 3D Scene Graphs for Scalable Robot Task Planning](https://arxiv.org/pdf/2307.06135.pdf)                                                                                                  |CoRL '23|  [github](https://sayplan.github.io/) |
| 2023-7-12 |          VoxPoser          |      Stanford      | [VoxPoser: Composable 3D Value Maps for Robotic Manipulation with Language Models](https://voxposer.github.io/voxposer.pdf)                                                           |    Arxiv  |  [github](https://github.com/huangwl18/VoxPoser) |
| 2022-12-13|         RT-1         |     Google     | [RT-1: Robotics Transformer for Real-World Control at Scale](https://robotics-transformer1.github.io/assets/rt1.pdf)                                                                                                  |Arxiv|  [github](https://robotics-transformer1.github.io/) |
| 2022-12-8 |         LLM-Planner         |     The Ohio State University    | [LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models](https://arxiv.org/pdf/2212.04088.pdf)                                                                                                  |ICCV '23|  [github](https://github.com/OSU-NLP-Group/LLM-Planner/) |
| 2022-10-11 |          CLIP-Fields          |      NYU, Meta      | [CLIP-Fields: Weakly Supervised Semantic Fields for Robotic Memory](https://arxiv.org/pdf/2210.05663.pdf)                                                           |    RSS '23  |  [github](https://github.com/notmahi/clip-fields) |
| 2022-09-20|       NLMap-SayCan       |     Google     | [Open-vocabulary Queryable Scene Representations for Real World Planning](https://arxiv.org/abs/2209.09874)                                                                    | ICRA '23|  [github](https://nlmap-saycan.github.io/) |

## 3D Benchmarks
|  Date |       keywords       |    Institute    | Paper                                                                                                                                                                               | Publication | Others |
| :-----: | :------------------: | :--------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------: 
| 2024-09-08 | MSQA / MSNN | BIGAI | [Multi-modal Situated Reasoning in 3D Scenes](https://arxiv.org/abs/2409.02389) | Axiv| [project](https://msr3d.github.io/) |
| 2024-06-10 | 3D-GRAND / 3D-POPE | UMich | [3D-GRAND: A Million-Scale Dataset for 3D-LLMs with Better Grounding and Less Hallucination](https://arxiv.org/pdf/2406.05132.pdf) | Arxiv | [project](https://3d-grand.github.io) |
| 2024-1-18 | SceneVerse | BIGAI | [SceneVerse: Scaling 3D Vision-Language Learning for Grounded Scene Understanding](https://arxiv.org/pdf/2401.09340.pdf) | Arxiv | [github](https://github.com/scene-verse/sceneverse) |
| 2023-12-26 | EmbodiedScan | Shanghai AI Lab | [EmbodiedScan: A Holistic Multi-Modal 3D Perception Suite Towards Embodied AI](https://arxiv.org/pdf/2312.16170.pdf) | Arxiv | [github](https://github.com/OpenRobotLab/EmbodiedScan) |
| 2023-12-17 |         M3DBench        |     Fudan University     | [M3DBench: Let's Instruct Large Models with Multi-modal 3D Prompts](https://arxiv.org/abs/2312.10763)                                                                                                  |Arxiv|  [github](https://github.com/OpenM3D/M3DBench) |
| 2023-11-29 |         -         |     DeepMind  | [Evaluating VLMs for Score-Based, Multi-Probe Annotation of 3D Objects](https://arxiv.org/pdf/2311.17851.pdf)                                                                                                  |Arxiv|  [github]() |
| 2022-10-14 |     SQA3D     |      BIGAI    | [SQA3D: Situated Question Answering in 3D Scenes](https://arxiv.org/pdf/2210.07474.pdf)                                                                                                        | ICLR '23| [github](https://github.com/SilongYong/SQA3D) |
| 2021-12-20|     ScanQA     |      RIKEN AIP    | [ScanQA: 3D Question Answering for Spatial Scene Understanding](https://arxiv.org/pdf/2112.10482.pdf)                                                                                                        | CVPR '23| [github](https://github.com/ATR-DBI/ScanQA) |
| 2020-12-3 |     Scan2Cap     |      TUM    | [Scan2Cap: Context-aware Dense Captioning in RGB-D Scans](https://arxiv.org/pdf/2012.02206.pdf)                                                                                                        | CVPR '21| [github](https://github.com/daveredrum/Scan2Cap) |
| 2020-8-23 | ReferIt3D | Stanford | [ReferIt3D: Neural Listeners for Fine-Grained 3D Object Identification in Real-World Scenes](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123460409.pdf) | ECCV '20 | [github](https://github.com/referit3d/referit3d) 
| 2019-12-18 |     ScanRefer     |      TUM   | [ScanRefer: 3D Object Localization in RGB-D Scans using Natural Language](https://arxiv.org/pdf/2112.10482.pdf)                                                                                                        | ECCV '20 | [github](https://daveredrum.github.io/ScanRefer/) |

## Contributing

Your contributions are always welcome!

I will keep some pull requests open if I'm not sure if they are awesome for 3D LLMs, you could vote for them by adding 👍 to them.

---

If you have any questions about this opinionated list, please get in touch at xianzheng@robots.ox.ac.uk or Wechat ID: mxz1997112.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ActiveVisionLab/Awesome-LLM-3D&type=Date)](https://star-history.com/#ActiveVisionLab/Awesome-LLM-3D&Date)

## Citation
If you find this repository useful, please consider citing this paper:
```
@misc{ma2024llmsstep3dworld,
      title={When LLMs step into the 3D World: A Survey and Meta-Analysis of 3D Tasks via Multi-modal Large Language Models}, 
      author={Xianzheng Ma and Yash Bhalgat and Brandon Smart and Shuai Chen and Xinghui Li and Jian Ding and Jindong Gu and Dave Zhenyu Chen and Songyou Peng and Jia-Wang Bian and Philip H Torr and Marc Pollefeys and Matthias Nießner and Ian D Reid and Angel X. Chang and Iro Laina and Victor Adrian Prisacariu},
      year={2024},
      journal={arXiv preprint arXiv:2405.10255},
}
```

## Acknowledgement
This repo is inspired by [Awesome-LLM](https://github.com/Hannibal046/Awesome-LLM?tab=readme-ov-file#other-awesome-lists)

