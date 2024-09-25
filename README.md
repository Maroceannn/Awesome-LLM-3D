
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
| :----------: | :------------------: | :--------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------: |
| 2 Feb 2023 | SceneScape | [SceneScape: Text-Driven Consistent Scene Generation](https://arxiv.org/abs/2302.01133) | NeurIPS 2023 | [project](https://scenescape.github.io/) | [code](https://github.com/RafailFridman/SceneScape) |
| 21 Mar 2023 | Text2Room | [Text2Room: Extracting Textured 3D Meshes from 2D Text-to-Image Models](https://arxiv.org/abs/2303.11989) | ICCV 2023 | [project](https://lukashoel.github.io/text-to-room/) | [code](https://github.com/lukasHoel/text2room) |
| 22 Nov 2023 | LucidDreamer | [LucidDreamer: Domain-free Generation of 3D Gaussian Splatting Scenes](https://arxiv.org/abs/2311.13384) | Arxiv 2023 | [project](https://luciddreamer-cvlab.github.io/) | [code](https://github.com/luciddreamer-cvlab/LucidDreamer) |
| 19 May 2023 | Text2NeRF | [Text2NeRF: Text-Driven 3D Scene Generation with Neural Radiance Fields](https://arxiv.org/abs/2305.11588) | TVCG 2024 | [project](https://eckertzhang.github.io/Text2NeRF.github.io/) | [code](https://github.com/eckertzhang/Text2NeRF) |
| 14 Dec 2023 | Text2Immersion | [Text2Immersion: Generative Immersive Scene with 3D Gaussians]([Text2Immersion: Generative Immersive Scene with 3D Gaussians)](https://arxiv.org/abs/2312.09242)) | Arxiv 2023 | [project](https://ken-ouyang.github.io/text2immersion/index.html) |  |
| 10 Apr 2024 | DreamScene360 | [DreamScene360: Unconstrained Text-to-3D Scene Generation with Panoramic Gaussian Splatting](https://arxiv.org/abs/2404.06903) | ECCV 2024 | [project](https://dreamscene360.github.io/) |  |
| 9 May 2024 | FastScene | [FastScene: Text-Driven Fast 3D Indoor Scene Generation via Panoramic Gaussian Splatting](https://arxiv.org/abs/2405.05768) | IJCAI 2024 |  | [code](https://github.com/Mr-Ma-yikun/FastScene) |
| 4 Jun 2024 | RoomTex | [RoomTex: Texturing Compositional Indoor Scenes via Iterative Inpainting](https://web3.arxiv.org/abs/2406.02461) | ECCV 2024 | [project](https://qwang666.github.io/RoomTex/) | [code](https://github.com/qwang666/RoomTex-) |
| 21 Jul 2024 | HoloDreamer | [HoloDreamer: Holistic 3D Panoramic World Generation from Text Descriptions](https://arxiv.org/abs/2407.15187) | Arxiv 2024 | [project](https://zhouhyocean.github.io/holodreamer/) |  |
| 25 Aug 2024 | SceneDreamer360 | [SceneDreamer360: Text-Driven 3D-Consistent Scene Generation with Panoramic Gaussian Splatting](https://arxiv.org/abs/2408.13711) | Arxiv 2024 | [project](https://scenedreamer360.github.io/) | [code](https://github.com/liwrui/SceneDreamer360) |



## 3D Understanding via other Foundation Models
|  Date |       Keywords       | Paper                                                                                                                                                                               | Publication | Project | Code |
| :----------: | :------------------: | :--------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------: | :---------: |
| 29 Nov 2023 | ShapeGPT | [ShapeGPT: 3D Shape Generation with A Unified Multi-modal Language Model](https://arxiv.org/abs/2311.17618) | Arxiv 2023 | [project](https://shapegpt.github.io/) |  |
| 27 Nov 2023 | MeshGPT | [MeshGPT: Generating Triangle Meshes with Decoder-Only Transformers](https://arxiv.org/abs/2311.15475) | CVPR 2024 | [project](https://nihalsid.github.io/mesh-gpt/) | [code](https://github.com/lucidrains/meshgpt-pytorch) |
| 14 Apr 2024 | DreamScape | [DreamScape: 3D Scene Creation via Gaussian Splatting joint Correlation Modeling](https://arxiv.org/abs/2404.09227) | Arxiv 2024 |  |  |
| 4 Apr 2024 | DreamScene | [DreamScene: 3D Gaussian-based Text-to-3D Scene Generation via Formation Pattern Sampling](https://arxiv.org/abs/2404.03575) | ECCV 2024 | [project](https://dreamscene-project.github.io/) | [code](https://dreamscene-project.github.io/) |
| 30 Nov 2023 | GraphDreamer | [GraphDreamer: Compositional 3D Scene Synthesis from Scene Graphs](https://arxiv.org/abs/2312.00093) | CVPR 2024 | [project](https://graphdreamer.github.io/) | [code](https://github.com/GGGHSL/GraphDreamer) |
| 24 May 2023 | LayoutGPT | [LayoutGPT: Compositional Visual Planning and Generation with Large Language Models](https://arxiv.org/abs/2305.15393) | NeurIPS 2023 | [project](https://layoutgpt.github.io/) | [code](https://github.com/weixi-feng/LayoutGPT) |
| 11 Feb 2024 | GALA3D | [GALA3D: Towards Text-to-3D Complex Scene Generation via Layout-guided Generative Gaussian Splatting](https://arxiv.org/abs/2402.07207) | ICML 2024 | [project](https://gala3d.github.io/) |  |
| 30 Jul 2024 | SceneTeller | [SceneTeller: Language-to-3D Scene Generation](https://arxiv.org/abs/2407.20727) | ECCV 2024 | [project](https://sceneteller.github.io/) |  |
| 19 Oct 2023 | 3D-GPT | [3D-GPT: Procedural 3D MODELING WITH LARGE LANGUAGE MODELS](https://arxiv.org/abs/2310.12945) | Arxiv 2023 | [project](https://chuny1.github.io/3DGPT/3dgpt.html) |  |
| 2 Mar 2024 | SceneCraft | [SceneCraft: An LLM Agent for Synthesizing 3D Scene as Blender Code](https://arxiv.org/abs/2403.01248) | ICML 2024 |  |  |
| 14 Dec 2023 | Holodeck | [Holodeck: Language Guided Generation of 3D Embodied AI Environments](https://arxiv.org/abs/2312.09067) | CVPR 2024 | [project](https://yueyang1996.github.io/holodeck/) | [code](https://github.com/allenai/Holodeck) |
| 11 Dec 2023 | AnyHome | [AnyHome: Open-Vocabulary Generation of Structured and Textured 3D Homes](https://arxiv.org/abs/2312.06644) | ECCV 2024 |  | [code](https://github.com/FreddieRao/anyhome_github) |




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

