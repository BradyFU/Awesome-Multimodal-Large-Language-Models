# A Survey of Unified Multimodal Understanding and Generation: Advances and Challenges

<p align="center">
    <img src="./images/MiG_logo.jpg" width="100%" height="100%">
</p>

<p align="center">
    <img src="./images/tree.svg" width="99%" height="80%">
</p>

<font size=6><div align='center' > [[📖 Paper](https://www.techrxiv.org/users/993777/articles/1355509-a-survey-of-unified-multimodal-understanding-and-generation-advances-and-challenges)] [[💬 WeChat (MLLM微信交流群，欢迎加入)](./images/wechat-group.png)]</div></font>  

<font size=6><div align='center' > A comprehensive overview of the unified multimodal understanding and generation models ! ✨ </div></font>


---

## Table of Contents
- [1.Modeling](#1modeling)
    - [1.1.External Expert Integration Modeling](#11External-Expert-Integration-Modeling)
    - [1.2.Modular Joint Modeling](#12Modular-Joint-Modeling)
        - [Prompt-Mediated](#Prompt-Mediated)
        - [Representation-Mediated](#Representation-Mediated)
    - [1.3.End-to-End Unified Modeling](#13End-to-End-Unified-Modeling)
        - [Autoregressive](#Autoregressive)
        - [Diffusion](#Diffusion)
        - [Hybrid](#Hybrid)
- [2.Encoding](#2Encoding)
    - [2.1.Continuous Representation](#21Continuous-Representation)
    - [2.2.Discrete Representation](#22Discrete-Representation)
    - [2.3.Hybrid Representation](#23Hybrid-Representation)
- [3.Decoding](#3Decoding)
    - [3.1.Continuous Representation](#31Continuous-Representation)
    - [3.2.Discrete Representation](#32Discrete-Representation)
    - [3.3.Hybrid Representation](#33Hybrid-Representation)
- [4.Benchmark](#4Benchmark)
    - [4.1.Understanding](#41Understanding)
    - [4.2.Generation](#42Generation)
    - [4.3.Mix-Modaility Generation](#43Mix-Modaility-Generation)
- [5.Training Datasets](#5Training-Datasets)

# 1.Modeling

## 1.1.External Expert Integration Modeling
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Multimodal Dialogue Response Generation**](https://arxiv.org/pdf/2110.08515) <br> | ACL | 2021-01 | - | - |
| [**Retrieval-Augmented Multimodal Language Modeling**](https://arxiv.org/pdf/2211.12561) <br> | ICML | 2022-11 | - | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/chenfei-wu/TaskMatrix?style=social) <br> [**Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models**](https://arxiv.org/pdf/2303.04671) <br> | arXiv | 2023-03 | [Github](https://github.com/chenfei-wu/TaskMatrix) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/JARVIS?style=social) <br> [**HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face**](https://arxiv.org/pdf/2303.17580) <br> | NeurIPS | 2023-03 | [Github](https://github.com/microsoft/JARVIS) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/AIGC-Audio/AudioGPT?style=social) <br> [**AudioGPT: Understanding and Generating Speech, Music, Sound, and Talking Head**](https://arxiv.org/pdf/2304.12995) <br> | arXiv | 2023-04 | [Github](https://github.com/AIGC-Audio/AudioGPT) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/0nutation/SpeechGPT?style=social) <br> [**SpeechGPT: Empowering Large Language Models with Intrinsic Cross-Modal Conversational Abilities**](https://arxiv.org/pdf/2305.11000) <br> | arXiv | 2023-05 | [Github](https://github.com/0nutation/SpeechGPT) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/SkyworkAI/Vitron?style=social) <br> [**Vitron: A Unified Pixel-level Vision LLM for Understanding, Generating, Segmenting, Editing**](https://arxiv.org/pdf/2305.11000) <br> | NeurIPS | 2024-12 | [Github](https://github.com/SkyworkAI/Vitron) | [Page](https://vitron-llm.github.io/) |


## 1.2.Modular Joint Modeling
### Prompt-Mediated
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/kohjingyu/gill?style=social) <br> [**Generating images with multimodal language models**](https://arxiv.org/pdf/2305.17216) <br> | NeurIPS | 2023-05 | [Github](https://github.com/kohjingyu/gill) | [Page](https://jykoh.com/gill) |
| [**SwitchGPT: Adapting Large Language Models for Non-Text Outputs**](https://arxiv.org/pdf/2309.07623) <br> | arXiv | 2023-09 | -| -|
| ![GitHub Repo stars](https://img.shields.io/github/stars/xiangyu-mm/EasyGen?style=social) <br> [**EasyGen: Easing Multimodal Generation with BiDiffuser and LLMs**](https://arxiv.org/pdf/2310.08949) <br> | ACL | 2023-10 | [Github](https://github.com/xiangyu-mm/EasyGen) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/gpt4video/GPT4Video?style=social) <br> [**GPT4Video: A Unified Multimodal Large Language Model for lnstruction-Followed Understanding and Safety-Aware Generation**](https://arxiv.org/pdf/2311.16511) <br> | ACM MM | 2023-11 | [Github](https://github.com/gpt4video/GPT4Video) | [Page](https://gpt4video.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/leo726/MedXChat?style=social) <br> [**MedXChat: A Unified Multimodal Large Language Model Framework towards CXRs Understanding and Generation**](https://arxiv.org/pdf/2312.02233) <br> | ISBI | 2023-12 | [Github](https://github.com/leo726/MedXChat) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/dvlab-research/MGM?style=social) <br> [**Mini-Gemini: Mining the Potential of Multi-modality Vision Language Models**](https://arxiv.org/pdf/2403.18814) <br> | arXiv | 2024-03 | [Github](https://github.com/dvlab-research/MGM) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/friedrichor/TIGER?style=social) <br> [**TIGER: A Unified Generative Model Framework for Multimodal Dialogue Response Generation**](https://aclanthology.org/2024.lrec-main.1403.pdf) <br> | LREC | 2024-05 | [Github](https://github.com/friedrichor/TIGER) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenGVLab/VisionLLM?style=social) <br> [**VisionLLM v2: An End-to-End Generalist Multimodal Large Language Model for Hundreds of Vision-Language Tasks**](https://arxiv.org/pdf/2406.08394) <br> | NeurIPS | 2024-06 | [Github](https://github.com/OpenGVLab/VisionLLM) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Layjins/Spider?style=social) <br> [**Spider: Any-to-Many Multimodal LLM**](https://arxiv.org/pdf/2411.09439) <br> | arXiv | 2024-11 | [Github](https://github.com/Layjins/Spider) | - |

### Representation-Mediated
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/kohjingyu/fromage?style=social) <br> [**Grounding language models to images for multimodal inputs and outputs**](https://arxiv.org/pdf/2301.13823) <br> | ICML | 2023-01 | [Github](https://github.com/kohjingyu/fromage) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/baaivision/Emu?style=social) <br> [**Emu: Generative Pretraining in Multimodality**](https://arxiv.org/pdf/2307.05222) <br> | ICLR | 2023-07 | [Github](https://github.com/baaivision/Emu) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/eric-ai-lab/MiniGPT-5?style=social) <br> [**MiniGPT-5: Interleaved Vision-and-Language Generation via Generative Vokens**](https://arxiv.org/pdf/2310.02239) <br> | arXiv | 2023-10 | [Github](https://github.com/eric-ai-lab/MiniGPT-5) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/baaivision/Emu?style=social) <br> [**Generative Multimodal Models are In-Context Learners**](https://arxiv.org/pdf/2312.13286) <br> | CVPR | 2023-12 | [Github](https://github.com/baaivision/Emu) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/AILab-CVC/VL-GPT?style=social) <br> [**VL-GPT: A Generative Pre-trained Transformer for Vision and Language Understanding and Generation**](https://arxiv.org/pdf/2312.09251) <br> | arXiv | 2023-12 | [Github](https://github.com/AILab-CVC/VL-GPT) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenGVLab/MM-Interleaved?style=social) <br> [**MM-Interleaved: Interleaved Image-Text Generative Modeling via Multi-modal Feature Synchronizer**](https://arxiv.org/pdf/2401.10208) <br> | arXiv | 2024-01 | [Github](https://github.com/OpenGVLab/MM-Interleaved) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/PKU-YuanGroup/LLMBind?style=social) <br> [**LLMBind: A Unified Modality-Task Integration Framework**](https://arxiv.org/pdf/2402.14891) <br> | arXiv | 2024-02 | [Github](https://github.com/PKU-YuanGroup/LLMBind) | - |
| [**X-VILA: Cross-Modality Alignment for Large Language Models**](https://arxiv.org/pdf/2405.19335) <br> | arXiv | 2024-05 |- | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/bytedance/TextHarmony?style=social) <br> [**Harmonizing Visual Text Comprehension and Generation**](https://arxiv.org/pdf/2407.16364) <br> | NeurIPS | 2024-07 | [Github](https://github.com/bytedance/TextHarmony) | - |
|[**MoMa: Efficient Early-Fusion Pre-training with Mixture of Modality-Aware Experts**](https://arxiv.org/pdf/2407.21770) <br> | arXiv | 2024-07 | - | [Page](https://kavourei.github.io/Moma) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/metamorph?style=social) <br> [**MetaMorph: Multimodal Understanding and Generation via Instruction Tuning**](https://arxiv.org/pdf/2412.14164) <br> | ICCV | 2024-12 | [Github](https://github.com/facebookresearch/metamorph/) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/hzphzp/WeGen?style=social) <br> [**WeGen: AUnified Model for Interactive Multimodal Generation as We Chat**](https://arxiv.org/pdf/2503.01115) <br> | arXiv | 2025-03 | [Github](https://github.com/hzphzp/WeGen) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/VARGPT-family/VARGPT-v1.1?style=social) <br> [**Vargpt-v1. 1: Improve visual autoregressive large unified model via iterative instruction tuning and reinforcement learning**](https://arxiv.org/pdf/2504.02949) <br> | arXiv | 2025-04 | [Github](https://github.com/VARGPT-family/VARGPT-v1.1) | [Page](https://vargpt1-1.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/modelscope/Nexus-Gen?style=social) <br> [**Nexus-Gen: A Unified Model for Image Understanding, Generation, and Editing**](https://arxiv.org/pdf/2504.21356) <br> | arXiv | 2025-04 | [Github](https://github.com/modelscope/Nexus-Gen) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/showlab/UniRL?style=social) <br> [**UniRL: Self-Improving Unified Multimodal Models via Supervised and Reinforcement Learning**](https://arxiv.org/pdf/2505.23380) <br> | arXiv | 2025-05 | [Github](https://github.com/showlab/UniRL) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/JiuhaiChen/BLIP3o?style=social) <br> [**BLIP3-o: A Family of Fully Open Unified Multimodal Models-Architecture, Training and Dataset**](https://arxiv.org/pdf/2505.09568) <br> | arXiv | 2025-06 | [Github](https://github.com/JiuhaiChen/BLIP3o) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/VectorSpaceLab/OmniGen2?style=social) <br> [**OmniGen2: Exploration to Advanced Multimodal Generation**](https://arxiv.org/pdf/2506.18871) <br> | arXiv | 2025-06 | [Github](https://github.com/VectorSpaceLab/OmniGen2) | [Page](https://vectorspacelab.github.io/OmniGen2/) |



## 1.3.End-to-End Unified Modeling
### Autoregressive
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/LargeWorldModel/LWM?style=social) <br> [**World Model on Million-Length Video And Language With Blockwise RingAttention**](https://arxiv.org/pdf/2402.08268) <br> | ICLR | 2024-02 | [Github](https://github.com/LargeWorldModel/LWM) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/chameleon?style=social) <br> [**Chameleon: Mixed-Modal Early-Fusion Foundation Models**](https://arxiv.org/pdf/2405.09818) <br> | arXiv | 2024-05 | [Github](https://github.com/facebookresearch/chameleon) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/GAIR-NLP/anole?style=social) <br> [**ANOLE: An Open, Autoregressive, Native Large Multimodal Models for Interleaved Image-Text Generation**](https://arxiv.org/pdf/2407.06135) <br> | arXiv | 2024-07 | [Github](https://github.com/GAIR-NLP/anole) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Alpha-VLLM/Lumina-mGPT?style=social) <br> [**Lumina-mGPT: Illuminate Flexible Photorealistic Text-to-Image Generation with Multimodal Generative Pretraining**](https://arxiv.org/pdf/2408.02657) <br> | arXiv | 2024-08 | [Github](https://github.com/Alpha-VLLM/Lumina-mGPT) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/baaivision/Emu3?style=social) <br> [**Emu3: Next-Token Prediction is All You Need**](https://arxiv.org/pdf/2409.18869) <br> | arXiv | 2024-09 | [Github](https://github.com/baaivision/Emu3) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/nv-tlabs/LLaMa-Mesh?style=social) <br> [**LLaMA-Mesh: Unifying 3D Mesh Generation with Language Models**](https://arxiv.org/pdf/2409.18869) <br> | arXiv | 2024-11 | [Github](https://github.com/nv-tlabs/LLaMa-Mesh) | [Page](https://research.nvidia.com/labs/toronto-ai/LLaMA-Mesh/) |
| [**SynerGen-VL: Towards Synergistic Image Understanding and Generation with Vision Experts and Token Folding**](https://arxiv.org/pdf/2409.18869) <br> | CVPR | 2024-12 | - | - |
| [**X-Prompt: Towards Universal In-Context Image Generation in Auto-Regressive Vision Language Foundation Models**](https://arxiv.org/pdf/2412.01824) <br> | arXiv | 2024-12 | - | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/Janus?style=social) <br> [**Janus-Pro: Unified Multimodal Understanding and Generation with Data and Model Scaling**](https://arxiv.org/pdf/2501.17811) <br> | arXiv | 2025-01 | [Github](https://github.com/deepseek-ai/Janus) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/finyorko/armor?style=social) <br> [**ARMOR: Empowering Multimodal Understanding Model with Interleaved Multimodal Generation Capability**](https://arxiv.org/pdf/2503.06542) <br> | arXiv | 2025-03 | [Github](https://github.com/finyorko/armor) | - |

### Diffusion
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/mhh0318/UniD3?style=social) <br> [**Unified Discrete Diffusion for Simultaneous Vision-Language Generation**](https://arxiv.org/pdf/2211.08332) <br> | ICLR | 2022-11 | [Github](https://github.com/mhh0318/UniD3) | [Page](https://mhh0318.github.io/unid3/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/SHI-Labs/Versatile-Diffusion?style=social) <br> [**Versatile Diffusion: Text, Images and Variations All in One Diffusion Model**](https://arxiv.org/pdf/2211.08332) <br> | ICCV | 2022-11 | [Github](https://github.com/SHI-Labs/Versatile-Diffusion) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/thu-ml/unidiffuser?style=social) <br> [**One Transformer Fits All Distributions in Multi-Modal Diffusion at Scale**](https://arxiv.org/pdf/2303.06555) <br> | ICML | 2023-03 | [Github](https://github.com/thu-ml/unidiffuser) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/i-Code?style=social) <br> [**Any-to-Any Generation via Composable Diffusion**](https://arxiv.org/pdf/2305.11846) <br> | NeurIPS | 2023-05 | [Github](https://github.com/microsoft/i-Code/tree/main/i-Code-V3) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/JordanZh/C3Net?style=social) <br> [**C3Net: Compound Conditioned ControlNet for Multimodal Content Generation**](https://arxiv.org/pdf/2311.17951) <br> | CVPR | 2023-11 | [Github](https://github.com/JordanZh/C3Net) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/jacklishufan/OmniFlows?style=social) <br> [**OmniFlow: Any-to-Any Generation with Multi-Modal Rectified Flows**](https://arxiv.org/pdf/2412.01169) <br> | arXiv | 2024-12 | [Github](https://github.com/jacklishufan/OmniFlows) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/sanowl/Multimodal-Latent-Language-Modeling-with-Next-Token-Diffusion?style=social) <br> [**Multimodal Latent Language Modeling with Next-Token Diffusion**](https://arxiv.org/pdf/2412.08635) <br> | arXiv | 2024-12 | [Github](https://github.com/sanowl/Multimodal-Latent-Language-Modeling-with-Next-Token-Diffusion) | [Page](https://thegenerality.com/agi/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/zhijie-group/UniCMs?style=social) <br> [**UniCMs: A Unified Consistency Model For Efficient Multimodal Generation and Understanding**](https://arxiv.org/pdf/2502.05415) <br> | arXiv | 2025-02 | [Github](https://github.com/zhijie-group/UniCMs) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/alexanderswerdlow/unidisc?style=social) <br> [**Unified Multimodal Discrete Diffusion**](https://arxiv.org/pdf/2503.20853) <br> | arXiv | 2025-03 | [Github](https://github.com/alexanderswerdlow/unidisc) | [Page](https://unidisc.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Gen-Verse/MMaDA?style=social) <br> [**MMaDA: Multimodal Large Diffusion Language Models**](https://arxiv.org/pdf/2505.15809) <br> | arXiv | 2025-05 | [Github](https://github.com/Gen-Verse/MMaDA) | - |

### Hybrid
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**CM3: A Causal Masked Multimodal Model of the Internet**](https://arxiv.org/pdf/2201.07520) <br> | arXiv | 2022-01 | -| - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/XuyangBai/TransFusion?style=social) <br> [**Transfusion: Predict the Next Token and Diffuse Images with One Multi-Modal Model**](https://arxiv.org/pdf/2408.11039) <br> | ICLR | 2024-08 | [Github](https://github.com/XuyangBai/TransFusion) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/showlab/Show-o?style=social) <br> [**Show-o: One Single Transformer to Unify Multimodal Understanding and Generation**](https://arxiv.org/pdf/2408.12528) <br> | ICLR | 2024-09 | [Github](https://github.com/showlab/Show-o) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/MonoFormer/MonoFormer?style=social) <br> [**MonoFormer: One Transformer for Both Diffusion and Autoregression**](https://arxiv.org/pdf/2409.16280) <br> | arXiv | 2024-09 | [Github](https://github.com/MonoFormer/MonoFormer) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/Janus?style=social) <br> [**JanusFlow: Harmonizing Autoregression and Rectified Flow for Unified Multimodal Understanding and Generation**](https://arxiv.org/pdf/2411.07975) <br> | CVPR | 2024-11 | [Github](https://github.com/deepseek-ai/Janus) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/Mixture-of-Transformers?style=social) <br> [**Mixture-of-Transformers: A Sparse and Scalable Architecture for Multi-Modal Foundation Models**](https://arxiv.org/pdf/2411.04996) <br> | ICLR | 2024-11 | [Github](https://github.com/facebookresearch/Mixture-of-Transformers) | - |
| [**LMFusion: Adapting Pretrained Language Models for Multimodal Generation**](https://arxiv.org/pdf/2412.15188) <br> | arXiv | 2024-12 | - | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/bytedance-seed/BAGEL?style=social) <br> [**Emerging Properties in Unified Multimodal Pretraining**](https://arxiv.org/pdf/2505.14683) <br> | arXiv | 2025-05 | [Github](https://github.com/bytedance-seed/BAGEL) | [Page](https://bagel-ai.org/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/arctanxarc/UniCTokens?style=social) <br> [**UniCTokens: Boosting Personalized Understanding and Generation via Unified Concept Tokens**](https://arxiv.org/pdf/2505.14671v1) <br> | arXiv | 2025-05 | [Github](https://github.com/arctanxarc/UniCTokens) | - |

# 2.Encoding
## 2.1.Continuous Representation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/OFA-Sys/OFA?style=social) <br> [**OFA: Unifying Architectures, Tasks, and Modalities Through a Simple Sequence-to-Sequence Learning Framework**](https://arxiv.org/pdf/2202.03052) <br> | ICML | 2022-02 | [Github](https://github.com/OFA-Sys/OFA) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/allenai/unified-io-inference?style=social) <br> [**Unified-IO: A Unified Model for Vision, Language, and Multi-Modal Tasks**](https://arxiv.org/pdf/2206.08916) <br> | ICLR | 2022-06 | [Github](https://github.com/allenai/unified-io-inference) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/shizhediao/DaVinci?style=social) <br> [**WRITE AND PAINT: GENERATIVE VISION-LANGUAGE MODELS ARE UNIFIED MODAL LEARNERS**](https://arxiv.org/pdf/2206.07699) <br> | arXiv | 2022-06 | [Github](https://github.com/shizhediao/DaVinci) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/TXH-mercury/VALOR?style=social) <br> [**VALOR: Vision-Audio-Language Omni-Perception Pretraining Model and Dataset**](https://arxiv.org/pdf/2304.08345) <br> | arXiv | 2023-04 | [Github](https://github.com/TXH-mercury/VALOR) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/RunpeiDong/DreamLLM?style=social) <br> [**DreamLLM: Synergistic Multimodal Comprehension and Creation**](https://arxiv.org/pdf/2309.11499) <br> | ICLR | 2023-09 | [Github](https://github.com/RunpeiDong/DreamLLM) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/xinke-wang/ModaVerse?style=social) <br> [**ModaVerse: Efficiently Transforming Modalities with LLMs**](https://arxiv.org/pdf/2401.06395) <br> | CVPR | 2024-01 | [Github](https://github.com/xinke-wang/ModaVerse) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/rongyaofang/PUMA?style=social) <br> [**PUMA: Empowering Unified MLLM with Multi-granular Visual Generation**](https://arxiv.org/pdf/2410.13861) <br> | arXiv | 2024-10 | [Github](https://github.com/rongyaofang/PUMA) | - |
|[**Unified Generative and Discriminative Training for Multi-modal Large Language Models**](https://arxiv.org/pdf/2411.00304) <br> | NeurIPS | 2024-11 | - | [Page](https://sugar-mllm.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/zhijie-group/Orthus?style=social) <br> [**Orthus: Autoregressive Interleaved Image-Text Generation with Modality-Specific Experts**](https://arxiv.org/pdf/2412.00127) <br> | ICML | 2024-12 | [Github](https://github.com/zhijie-group/Orthus) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/zijieli-Jlee/Dual-Diffusion?style=social) <br> [**Dual Diffusion for Unified Image Generation and Understanding**](https://arxiv.org/pdf/2501.00289) <br> | CVPR | 2025-01 | [Github](https://github.com/zijieli-Jlee/Dual-Diffusion) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/VARGPT-family/VARGPT?style=social) <br> [**VARGPT: Next-Generation Multi-Modal AI Agent with Unified Vision-Audio-Text Generation**](https://arxiv.org/pdf/2501.12327) <br> | arXiv | 2025-01 | [Github](https://github.com/VARGPT-family/VARGPT) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/wusize/Harmon?style=social) <br> [**Harmonizing visual representations for unified multimodal understanding and generation**](https://arxiv.org/pdf/2503.21979v1) <br> | arXiv | 2025-03 | [Github](https://github.com/wusize/Harmon) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/inclusionAI/Ming?style=social) <br> [**Ming-Omni: A Unified Multimodal Model for Perception and Generation**](http://arxiv.org/pdf/2506.09344v1) <br> | arXiv | 2025-06 | [Github](https://github.com/inclusionAI/Ming/tree/main) | [Page](https://lucaria-academy.github.io/Ming-Omni/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/showlab/Show-o?style=social) <br> [**Show-o2: Improved Native Unified Multimodal Models**](https://arxiv.org/pdf/2506.15564) <br> | arXiv | 2025-06 | [Github](https://github.com/showlab/Show-o) | - |


## 2.2.Discrete Representation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Jointly Training Large Autoregressive Multimodal Models**](https://arxiv.org/pdf/2309.15564) <br> | ICLR | 2023-09 | - | [Page](https://zhangtemplar.github.io/large-auto-regressive/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/MIO-Team/MIO?style=social) <br> [**MIO: A Foundation Model on Multimodal Tokens**](https://arxiv.org/pdf/2409.17692) <br> | arXiv | 2024-09 | [Github](https://github.com/MIO-Team/MIO) | - |
| [**MUSE-VL: Modeling Unified VLM through Semantic Discrete Encoding**](https://arxiv.org/pdf/2411.17762) <br> | ICCV | 2024-11 |- | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/FoundationVision/Liquid?style=social) <br> [**Liquid: Language Models are Scalable Multi-modal Generators**](https://arxiv.org/pdf/2412.04332) <br> | arXiv | 2024-12 | [Github](https://github.com/FoundationVision/Liquid) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/tliby/UniFork?style=social) <br> [**UniFork: Exploring Modality Alignment for Unified Multimodal Understanding and Generation**](https://arxiv.org/pdf/2506.17202) <br> | arXiv | 2025-06 | [Github](https://github.com/tliby/UniFork) | - |

## 2.3.Hybrid Representation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/AILab-CVC/SEED?style=social) <br> [**Planting a SEED of Vision in Large Language Model**](https://arxiv.org/pdf/2310.01218) <br> | ICLR | 2023-10 | [Github](https://github.com/AILab-CVC/SEED) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenMOSS/AnyGPT?style=social) <br> [**AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling**](https://arxiv.org/pdf/2402.12226) <br> | ACL | 2024-02 | [Github](https://github.com/OpenMOSS/AnyGPT) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/jy0205/LaVIT?style=social) <br> [**Video-LaVIT: Unified Video-Language Pre-training with Decoupled Visual-Motional Tokenization**](https://arxiv.org/pdf/2402.03161) <br> | ICML | 2024-02 | [Github](https://github.com/jy0205/LaVIT) | - |
|[**C3LLM: Conditional Multimodal Content Generation Using Large Language Models**](https://arxiv.org/pdf/2405.16136) <br> | arXiv | 2024-05 | - | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/vila-u?style=social) <br> [**VILA-U: An Unified Foundation Model Integrating Visual Understanding and Generation**](https://arxiv.org/pdf/2409.04429) <br> | arXiv | 2024-09 | [Github](https://github.com/mit-han-lab/vila-u) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/Janus?style=social) <br> [**Janus: Decoupling Visual Encoding for Unified Multimodal Understanding and Generation**](https://arxiv.org/pdf/2410.13848) <br> | CVPR | 2024-10 | [Github](https://github.com/deepseek-ai/Janus) | - |
| [**ILLUME: Illuminating Your LLMs to See, Draw, and Self-Enhance**](https://arxiv.org/pdf/2412.06673) <br> | ICCV | 2024-12 |-| - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/ByteVisionLab/TokenFlow?style=social) <br> [**TokenFlow: Unified Image Tokenizer for Multimodal Understanding and Generation**](https://arxiv.org/pdf/2412.03069) <br> | CVPR | 2024-12 | [Github](https://github.com/ByteVisionLab/TokenFlow) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/hustvl/OmniMamba?style=social) <br> [**Omnimamba: Efficient and unified multimodal understanding and generation via state space models**](https://arxiv.org/pdf/2503.08686) <br> | arXiv | 2025-03 | [Github](https://github.com/hustvl/OmniMamba) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/illume-unified-mllm/ILLUME_plus?style=social) <br> [**Illume+: Illuminating unified mllm with dual visual tokenization and diffusion refinement**](https://arxiv.org/pdf/2504.01934) <br> | arXiv | 2025-04 | [Github](https://github.com/illume-unified-mllm/ILLUME_plus) | [Page](https://illume-unified-mllm.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/SxJyJay/UniToken?style=social) <br> [**UniToken: Harmonizing Multimodal Understanding and Generation through Unified Visual Encoding**](https://arxiv.org/pdf/2504.04423v1) <br> | CVPR | 2025-04 | [Github](https://github.com/SxJyJay/UniToken) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/mm-vl/ULM-R1?style=social) <br> [**Co-Reinforcement Learning for Unified Multimodal Understanding and Generation**](https://arxiv.org/pdf/2505.17534) <br> | arXiv | 2025-05 | [Github](https://github.com/mm-vl/ULM-R1) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/FreedomIntelligence/ShareGPT-4o-Image?style=social) <br> [**ShareGPT-4o-Image: Aligning Multimodal Models with GPT-4o-Level Image Generation**](https://arxiv.org/pdf/2506.18095) <br> | arXiv | 2025-06 | [Github](https://github.com/FreedomIntelligence/ShareGPT-4o-Image) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/csuhan/Tar?style=social) <br> [**Vision as a Dialect: Unifying Visual Understanding and Generation via Text-Aligned Representations**](https://arxiv.org/pdf/2506.18898) <br> | arXiv | 2025-06 | [Github](https://github.com/csuhan/Tar) | [Page](https://tar.csuhan.com/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/wren93/tuna?style=social) <br> [**TUNA: Taming Unified Visual Representations for Native Unified Multimodal Models**](https://arxiv.org/pdf/2512.02014) <br> | arXiv | 2025-12 | [Github](https://github.com/wren93/tuna) | [Page](https://tuna-ai.org/) |


# 3.Decoding
## 3.1.Continuous Representation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/NExT-GPT/NExT-GPT?style=social) <br> [**NExT-GPT: Any-to-Any Multimodal LLM**](https://arxiv.org/pdf/2309.05519) <br> | ICML | 2023-09 | [Github](https://github.com/NExT-GPT/NExT-GPT) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/i-Code?style=social) <br> [**CoDi-2: In-Context, Interleaved, and Interactive Any-to-Any Generation**](https://arxiv.org/pdf/2311.18775) <br> | CVPR | 2023-11 | [Github](https://github.com/microsoft/i-Code/tree/main/CoDi-2) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/AILab-CVC/SEED-X?style=social) <br> [**SEED-X: Multimodal Models with Unified Multi-granularity Comprehension and Generation**](https://arxiv.org/pdf/2404.14396) <br> | arXiv | 2024-04 | [Github](https://github.com/AILab-CVC/SEED-X) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/shansongliu/MuMu-LLaMA?style=social) <br> [**MuMu-LLaMA: Multi-modal Music Understanding and Generation via Large Language Models**](https://arxiv.org/pdf/2412.06660) <br> | arXiv | 2024-12 | [Github](https://github.com/shansongliu/MuMu-LLaMA) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/metaquery?style=social) <br> [**Transfer between Modalities with MetaQueries**](https://arxiv.org/pdf/2504.06256) <br> | arXiv | 2025-04 | [Github](https://github.com/facebookresearch/metaquery) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/inclusionAI/Ming?style=social) <br> [**Ming-Lite-Uni: Advancements in Unified Architecture for Natural Multimodal Interaction**](https://arxiv.org/pdf/2505.02471) <br> | arXiv | 2025-05 | [Github](https://github.com/inclusionAI/Ming/tree/Ming-Lite-Omni-Preview) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/wusize/OpenUni?style=social) <br> [**OpenUni: A Simple Baseline for Unified Multimodal Understanding and Generation**](https://arxiv.org/pdf/2505.23661) <br> | arXiv | 2025-05 | [Github](https://github.com/wusize/OpenUni) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/AIDC-AI/Ovis-U1?style=social) <br> [**Ovis-U1 Technical Report**](https://arxiv.org/pdf/2506.23044v1) <br> | arXiv | 2025-06 | [Github](https://github.com/AIDC-AI/Ovis-U1) | - |

## 3.2.Discrete Representation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/hyn2028/llm-cxr?style=social) <br> [**LLM-CXR: Instruction-Finetuned LLM for CXR Image Understanding and Generation**](https://arxiv.org/pdf/2305.11490) <br> | ICLR | 2023-05 | [Github](https://github.com/hyn2028/llm-cxr) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/CM3Leon?style=social) <br> [**Scaling Autoregressive Multi-Modal Models: Pretraining and Instruction Tuning**](https://arxiv.org/pdf/2309.02591) <br> | arXiv | 2023-09 | [Github](https://github.com/kyegomez/CM3Leon) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/allenai/unified-io-2?style=social) <br> [**Unified-IO 2: Scaling Autoregressive Multimodal Models with Vision, Language, Audio, and Action**](https://arxiv.org/pdf/2312.17172) <br> | CVPR | 2023-12 | [Github](https://github.com/allenai/unified-io-2) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/NVlabs/QLIP?style=social) <br> [**QLIP: Text-Aligned Visual Tokenization Unifies Auto-Regressive Multimodal Understanding and Generation**](https://arxiv.org/pdf/2502.05178) <br> | arXiv | 2025-02 | [Github](https://github.com/NVlabs/QLIP/tree/main) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/FoundationVision/UniTok?style=social) <br> [**UniTok: A Unified Tokenizer for Visual Generation and Understanding**](https://arxiv.org/pdf/2502.20321) <br> | arXiv | 2025-02 | [Github](https://github.com/FoundationVision/UniTok) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/TencentARC/TokLIP?style=social) <br> [**TokLIP: Marry Visual Tokens to CLIP for Multimodal Comprehension and Generation**](https://www.arxiv.org/pdf/2505.05422) <br> | arXiv | 2025-05 | [Github](https://github.com/TencentARC/TokLIP) | - |

## 3.3.Hybrid Representation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/jy0205/LaVIT?style=social) <br> [**Unified Language-Vision Pretraining in LLM with Dynamic Discrete Visual Tokenization**](https://arxiv.org/pdf/2309.04669) <br> | ICLR | 2023-09 | [Github](https://github.com/jy0205/LaVIT) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/DCDmllm/HealthGPT?style=social) <br> [**HealthGPT: A Medical Large Vision-Language Model for Unifying Comprehension and Generation via Heterogeneous Knowledge Adaptation**](https://arxiv.org/pdf/2502.09838) <br> | ICML | 2025-02 | [Github](https://github.com/DCDmllm/HealthGPT) | [Page](https://llsuzy.github.io/HealthGPT.github.io/) |

<!-- # Training Dataset
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|


# Benchmark
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:| -->

# 4.Benchmark
## 4.1.Understanding
### Image
|  Capability&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  |  Benchmarks  |
|:-------------|:-------------|
| **Foundation Capability**|  [VizWiz](https://arxiv.org/abs/1802.08218), [VQA v2.0](https://arxiv.org/abs/1612.00837), [LVLM-eHub](https://arxiv.org/abs/2306.09265), [LAMM](https://arxiv.org/pdf/2306.06687v1), [OwlEval](https://arxiv.org/abs/2304.14178), [MMBench](https://arxiv.org/abs/2307.06281), [Seed-Bench](https://arxiv.org/abs/2307.16125), [Seed-Benchv2](https://arxiv.org/abs/2311.17092), [MME](https://arxiv.org/abs/2306.13394), [MMT-Bench](https://arxiv.org/abs/2404.16006), [Blink](https://arxiv.org/abs/2404.12390), [MMStar](https://arxiv.org/abs/2403.20330), [TouchStone](https://arxiv.org/abs/2411.03670), [MMR](https://arxiv.org/abs/2406.09121), [CV-Bench](https://arxiv.org/abs/2406.16860v1), [CapArena](https://arxiv.org/abs/2503.12329), [FaceXBench](https://arxiv.org/abs/2501.10360), [MuirBench](https://arxiv.org/abs/2406.09411), [MMVP](https://arxiv.org/abs/2401.06209), [ViP-Bench](https://arxiv.org/abs/2312.00784), [MME-RealWorld](https://arxiv.org/abs/2408.13257), [VisIT-Bench](https://arxiv.org/abs/2308.06595), [RealUnify](https://arxiv.org/abs/2509.24897) |
|**World Knowledge** |[MM-Vet](https://arxiv.org/abs/2308.02490), [ScienceQA](https://arxiv.org/abs/2209.09513), [MMMU](https://arxiv.org/abs/2401.11944), [CMMU](https://arxiv.org/abs/2401.14011), [CMMMU](https://arxiv.org/abs/2401.11944), [MMMU-Pro](https://arxiv.org/abs/2409.02813), [MDI-Benchmark](https://arxiv.org/abs/2412.12606), [WorldSense](https://arxiv.org/abs/2311.15930), [EmbodiedEval](https://arxiv.org/abs/2501.11858), [MSEarth](https://arxiv.org/abs/2505.20740) |
|**Reasoning**|  [InfiMM-Eval](https://arxiv.org/abs/2311.11567), [MMRel](https://arxiv.org/abs/2406.09121), [VisualCoT](https://arxiv.org/abs/2403.16999), [M3CoT](https://arxiv.org/abs/2405.16473), [CRPE](https://arxiv.org/abs/2308.01907), [MiCEval](https://arxiv.org/abs/2410.14668), [GVLQA](https://proceedings.neurips.cc/paper_files/paper/2024/hash/00295cede6e1600d344b5cd6d9fd4640-Abstract-Conference.html), [MMCR](https://arxiv.org/abs/2503.18533), [CoMT](https://arxiv.org/abs/2412.12932) |
|**OCR**|  [TextVQA](https://arxiv.org/abs/2502.07411), [Ocr-VQA](https://anandmishra22.github.io/files/mishra-OCR-VQA.pdf), [Websrc](https://arxiv.org/abs/2101.09465), [OCRBench](https://arxiv.org/abs/2501.00321), [OCRBench-v2](https://arxiv.org/abs/2501.00321), [Seed-bench-2-plus](https://arxiv.org/abs/2404.16790), [VCR-Wiki](https://arxiv.org/abs/2406.06462), [ViOCRVQA](https://arxiv.org/abs/2404.18397) |
|**Chart and Documentation**|  [ChartQA](https://arxiv.org/abs/2203.10244), [DocVQA](https://arxiv.org/abs/2007.00398), [InfoVQA](https://arxiv.org/abs/2104.12756), [DocGenome](https://arxiv.org/abs/2406.11633), [MMLongBench-Doc](https://arxiv.org/abs/2407.01523), [CharXiv](https://arxiv.org/abs/2406.18521), [AI2D](https://arxiv.org/abs/1603.07396), [VisualMRC](https://arxiv.org/abs/2101.11272), [LEAF-QA](https://arxiv.org/abs/1907.12861), [FigureQA](https://arxiv.org/abs/1710.07300), [Charting-New-Territories](https://arxiv.org/abs/2311.14656), [MMC-Benchmark](https://arxiv.org/abs/2311.10774), [EvoChart](https://arxiv.org/abs/2409.01577), [TableBench](https://arxiv.org/abs/2408.09174) |
|**Math**|  [MathVista](https://arxiv.org/abs/2310.02255), [MATH-Vision](https://arxiv.org/abs/2402.14804), [OlympiadBench](https://arxiv.org/abs/2402.14008), [MathVerse](https://arxiv.org/abs/2403.14624), [We-Math](https://arxiv.org/abs/2407.01284), [MATH-Perturb](https://arxiv.org/abs/2502.06453) |
|**Multi-lingual**|  [CMMMU](https://arxiv.org/abs/2401.11944), [CMMU](https://arxiv.org/abs/2401.14011), [AlignMMBench](https://arxiv.org/abs/2406.09295), [MTVQA](https://arxiv.org/abs/2405.11985), [M3Exam](https://arxiv.org/abs/2306.05179), [Urdu-VQA](https://arxiv.org/abs/2405.12533), [Swahili-STR](https://arxiv.org/abs/2405.11437), [CVLUE](https://arxiv.org/abs/2407.01081) |
|**Hallucination**|  [POPE](https://arxiv.org/abs/2305.10355), [GAVIE](https://arxiv.org/abs/2306.14565), [M-HalDetect](https://arxiv.org/abs/2308.06394), [HaELM](https://arxiv.org/abs/2308.15126), [MMHal-Bench](https://arxiv.org/abs/2309.14525), [Bingo](https://arxiv.org/abs/2311.03287), [PhD](https://aclanthology.org/2023.findings-emnlp.256/), [HallusionBench](https://arxiv.org/abs/2310.14566), [AMBER](https://arxiv.org/abs/2311.07397), [OpenChair](https://arxiv.org/abs/2312.03631), [MHaluBench](https://arxiv.org/abs/2402.03190), [VHTest](https://arxiv.org/abs/2402.14683), [VALOR-Eval](https://arxiv.org/abs/2404.13874), [HQH](https://arxiv.org/abs/2406.17115), [R-Bench](https://arxiv.org/abs/2503.14935), [VLind-Bench](https://arxiv.org/abs/2406.08702), [VQAv2-IDK](https://arxiv.org/abs/2402.08348) |
|**Safety and Bias**|  [VLLM-safety-bench](https://arxiv.org/abs/2311.16101), [MultiTrust](https://arxiv.org/abs/2406.07057), [MMSafeAware](https://arxiv.org/abs/2502.11184), [MOSSBench](https://arxiv.org/abs/2406.17806), [VLBiasBench](https://arxiv.org/abs/2406.14194), [Bingo](https://arxiv.org/abs/2311.03287) |

### Video
|  Capability&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  |  Benchmarks  |
|:-------------|:-------------|
|**Foundation Capability**|  [Video-MME](https://arxiv.org/abs/2405.21075), [MVBench](https://arxiv.org/abs/2311.17005), [MLVU](https://arxiv.org/abs/2406.04264), [MMBench-Video](https://arxiv.org/abs/2406.14515), [VN-Bench](https://arxiv.org/abs/2406.09367), [TempCompass](https://arxiv.org/abs/2403.00476), [MSVD-QA](https://dl.acm.org/doi/10.1145/3123266.3123427#), [VEU-Bench](https://arxiv.org/abs/2504.17828), [ActivityNet-QA](https://arxiv.org/abs/1906.02467), [MSRVTT-QA](https://dl.acm.org/doi/10.1145/3123266.3123427#), [EPIC-KITCHENS-100](https://arxiv.org/abs/2006.13256), [V2P-Bench](https://arxiv.org/abs/2503.17736), [MotionBench](https://arxiv.org/abs/2501.02955), [H2VU-Benchmark](https://arxiv.org/abs/2503.24008), [FAVOR-Bench](https://arxiv.org/abs/2503.14935), [VELOCIT](https://arxiv.org/abs/2406.10889), [TGIF-QA](https://link.springer.com/article/10.1007/s11263-019-01189-x) |
|**Long Context**|  [VideoWebArena](https://arxiv.org/abs/2410.19100), [SVBench](https://arxiv.org/abs/2502.10810), [CG-Bench](https://arxiv.org/abs/2412.12075), [Neptune](https://arxiv.org/abs/2505.00681), [LongViTU](https://arxiv.org/abs/2501.05037), [X-LeBench](https://arxiv.org/abs/2501.06835), [HLV-1K](https://arxiv.org/abs/2501.01645), [LVBench](https://arxiv.org/abs/2406.08035), [Event-Bench](https://arxiv.org/abs/2406.14129), [MLVU](https://arxiv.org/abs/2406.04264), [EgoSchema](https://arxiv.org/abs/2308.09126) |
|**World Knowledge**|  [Video-MMLU](https://arxiv.org/abs/2504.14693), [Video-MMMU](https://arxiv.org/abs/2501.13826), [STI-Bench](https://arxiv.org/abs/2503.23765), [UrbanVideo-Bench](https://arxiv.org/abs/2503.06157), [Video SimpleQA](https://arxiv.org/abs/2503.18923) |
|**Reasoning**|  [V-STaR](https://arxiv.org/abs/2503.11495), [MINERVA](https://arxiv.org/abs/2505.00681), [InstructionBench](https://arxiv.org/abs/2504.05040), [OVO-Bench](https://arxiv.org/abs/2501.05510), [VCBench](https://arxiv.org/abs/2411.09105), [VisuLogic](https://arxiv.org/abs/2504.15279) |
|**Safety and Bias**|  [MVTamperBench](https://arxiv.org/abs/2412.19794), [VidLBEval](https://arxiv.org/abs/2502.16602) |
|**Hallucination**|  [MHBench](https://github.com/xzhouzeng/MHBench), [VidHal](https://arxiv.org/abs/2411.16771), [VideoHallucer](https://arxiv.org/abs/2406.16338) |
|**OCR**|  [EgoTextVQA](https://arxiv.org/abs/2502.07411), [MME-VideoOCR](https://arxiv.org/abs/2505.21333), [FG-Bench](https://arxiv.org/abs/2412.20613) |

### Audio
|  Capability&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  |  Benchmarks  |
|:-------------|:-------------|
|**Foundation Capability**|  [MMAU](https://arxiv.org/abs/2407.18961), [Salmon](https://arxiv.org/pdf/2409.07437), [AIR-Bench](https://arxiv.org/abs/2402.07729), [AudioBench](https://arxiv.org/abs/2406.16020), [MuChoMusic](https://arxiv.org/abs/2408.01337), [VoiceBench](https://arxiv.org/abs/2410.17196), [Audio Entailment](https://arxiv.org/abs/2407.18062), [VoxEval](https://arxiv.org/abs/2501.04962), [Audiopedia](https://arxiv.org/abs/2412.20619) |

### Mix
|  Capability&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  |  Benchmarks  |
|:-------------|:-------------|
| **Multi-Modality <br> Understanding**|  [ACVUBench](https://arxiv.org/abs/2503.19951), [MAVERIX](https://arxiv.org/abs/2503.21699), [MME-Unify](https://arxiv.org/abs/2504.03641), [RealUnify](https://arxiv.org/abs/2509.24897) |

## 4.2.Generation
### Image
|  Capability&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  |  Benchmarks  |
|:-------------|:-------------|
| **Text-to-Image Generation**|  <br>*Quality*: [EvalMi-50K](https://arxiv.org/abs/2504.08358), [DPGBench](https://github.com/TencentQQGYLab/ELLA/tree/main/dpg_bench), [ConceptMix](https://arxiv.org/abs/2408.14339), [DreamBooth](https://arxiv.org/abs/2208.12242), [Pick-a-Pic](https://arxiv.org/abs/2305.01569), [AIGI-VC](https://arxiv.org/abs/2412.15677), [T2I-CompBench](https://karine-h.github.io/T2I-CompBench/), [DrawBench](https://huggingface.co/datasets/shunk031/DrawBench), [TIFA](https://arxiv.org/abs/2303.11897), [Davidsonian](https://arxiv.org/abs/2310.18235), [GenEval](https://arxiv.org/abs/2310.11513), [PartiPrompts](https://arxiv.org/abs/2206.10789), [T2I-CompBench++](https://arxiv.org/abs/2307.06350), [HRS-Bench](https://arxiv.org/abs/2304.05390), [I-HallA](https://arxiv.org/abs/2409.12784) <br>*Safety and Bias*: [PAINTSKILLS](https://arxiv.org/abs/2202.04053), [TrustGen](https://arxiv.org/abs/2502.14296), [BigBench](https://arxiv.org/abs/2407.15240), [FaintBench](https://arxiv.org/abs/2405.17814), [T2ISafety](https://arxiv.org/abs/2501.12612), [HEIM](https://arxiv.org/abs/2311.04287) <br>*World Knowledge*: [WISE](https://arxiv.org/abs/2503.07265), [Commonsense-T2I](https://arxiv.org/abs/2406.07546), [PhyBench](https://arxiv.org/abs/2406.11802), [RealUnify](https://arxiv.org/abs/2509.24897) |
| **Image Editing**|  <br>*Quality*: [UltraEdit](https://arxiv.org/abs/2407.05282), [EmuEdit](https://arxiv.org/abs/2311.10089), [DreamEdit](https://arxiv.org/abs/2306.12624), [PIE-Bench](https://openreview.net/forum?id=FoMZ4ljhVw), [GEdit-Bench](https://arxiv.org/abs/2504.17761), [KRIS-Bench](https://arxiv.org/abs/2505.16707), [ImgEdit](https://arxiv.org/abs/2505.20275), [ByteMorph-Bench](https://arxiv.org/abs/2506.03107), [MagicBench](https://arxiv.org/abs/2503.16421) <br> *Reasoning and Bias*: [RISEBench](https://arxiv.org/abs/2504.02826), [AURORA-Bench](https://arxiv.org/abs/2407.03471), [RealUnify](https://arxiv.org/abs/2509.24897) <br>*Bias*: [ICEB](https://arxiv.org/abs/2403.13807) |

### Video
|  Capability&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  |  Benchmarks  |
|:-------------|:-------------|
| **Text-to-Video Generation**|  <br>*Quality*: [ETVABench](https://arxiv.org/abs/2503.16867), [VideoBench](https://arxiv.org/abs/2504.04907), [EvalCrafter](https://arxiv.org/abs/2310.11440), [MiraBench](https://arxiv.org/abs/2407.06358), [T2VQA](https://arxiv.org/abs/2403.11956), [GAIA](https://arxiv.org/abs/2406.06087), [T2V-CompBench](https://arxiv.org/abs/2407.14505), [T2VBench](https://openaccess.thecvf.com/content/CVPR2024W/EvGenFM/papers/Ji_T2VBench_Benchmarking_Temporal_Dynamics_for_Text-to-Video_Generation_CVPRW_2024_paper.pdf), [DEVIL](https://arxiv.org/abs/2105.05332), [Human-AGVQA](https://arxiv.org/abs/2411.16619), [DIVIDE-3K](https://github.com/VQAssessment/ExplainableVQA), [VideoFeedBack](https://arxiv.org/abs/2406.15252), [LGVQ](https://arxiv.org/abs/2407.21408), [VBench](https://arxiv.org/abs/2502.10810), [VBench2.0](https://vchitect.github.io/VBench-2.0-project/), [T2VTextBench](https://arxiv.org/abs/2505.04946) <br>*World Knowledge*: [ChronoMagic-Bench](https://arxiv.org/abs/2406.18522), [WorldSimBench](https://arxiv.org/abs/2410.18072), [PhyGenBench](https://arxiv.org/abs/2410.05363), [WorldScore](https://arxiv.org/abs/2504.00983), [Morpheus](https://arxiv.org/abs/2504.02918), [StoryEval](https://arxiv.org/abs/2412.16211), [T2VPhysBench](https://arxiv.org/abs/2505.00337), [PhyWorldBench](https://arxiv.org/abs/2507.13428) <br>*Safety*: [T2VSafetyBench](https://arxiv.org/abs/2407.05965) |
| **Text-Guided Video Editing**| [VE-Bench](https://arxiv.org/abs/2408.11481), [EditBoard](https://arxiv.org/abs/2409.09668), [TGVE](https://arxiv.org/abs/2310.16003) |
|**Image-to-Video Generation**|  [AIGCBench](https://arxiv.org/abs/2401.01651), [TIP-Eval](https://arxiv.org/html/2411.04709v1), [I2V-Bench](https://arxiv.org/abs/2402.04324) |

### Audio
|  Capability&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  |  Benchmarks  |
|:-------------|:-------------|
|**Text and Speech to Speech** |  [S2S-Arena](https://arxiv.org/abs/2503.05085), [EmphAssess](https://arxiv.org/abs/2312.14069), [TTSDS](https://arxiv.org/abs/2407.12707) |

### Mix
|  Capability&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  |  Benchmarks  |
|:-------------|:-------------|
|**Multi-Task Generation** |[ICE-Bench](https://arxiv.org/abs/2503.14482), [ImagenHub](https://arxiv.org/abs/2310.01596), [TC-Bench](https://arxiv.org/abs/2406.08656), [VideoGen-Eval](https://arxiv.org/abs/2503.23452), [GenAI-Bench](https://arxiv.org/abs/2406.04485) |

## 4.3.Mix-Modaility Generation
|  Capability&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  |  Benchmarks  |
|:-------------|:-------------|
|**Text-and-Image <br> Interleaved Generation** |[InterleavedEval](https://arxiv.org/abs/2406.14643), [SEED-Bench2](https://arxiv.org/abs/2311.17092), [MMIE](https://arxiv.org/abs/2410.10139), [CoMM](https://arxiv.org/abs/2412.15677), [UniEval](https://arxiv.org/abs/2505.10483), [MME-Unify](https://arxiv.org/abs/2504.03641), [RealUnify](https://arxiv.org/abs/2509.24897) |

# 5.Training Datasets
| Format&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; | Datasets |
|---|---|
| **conversation for generation** | [InstructPix2Pix](https://arxiv.org/abs/2211.09800), [Magicbrush](https://arxiv.org/abs/2306.13042), [MidJouney](https://huggingface.co/datasets/CortexLM/midjourney-v6), [SEED-Data-Edit](https://arxiv.org/abs/2405.04007), [OpenVid-1M](https://arxiv.org/abs/2407.02371), [text-to-image-2M](https://huggingface.co/datasets/jackyhate/text-to-image-2M), [Hive](https://arxiv.org/abs/2311.08381), [HQ-Edit](https://arxiv.org/abs/2404.09990), [OpenGPT-4o-Image](https://arxiv.org/abs/2509.24900), [UltraEdit](https://arxiv.org/abs/2407.05282), [ImgEdit](https://arxiv.org/abs/2505.20275), [SynCD](https://arxiv.org/abs/2502.01720), [MultiGen-20M](https://arxiv.org/abs/2305.11147) |
| **conversation for understanding** | [M3IT](https://arxiv.org/abs/2306.04387), [MIMIC-IT](https://arxiv.org/abs/2306.05425), [LLaVA 1.0](https://arxiv.org/abs/2304.08485), [LLaVA Instruct-665k](https://arxiv.org/abs/2304.08485), [LRV-Instruction](https://arxiv.org/abs/2306.14565), [LLaVA-OneVision](https://arxiv.org/abs/2408.03326), [VIST](https://arxiv.org/abs/1604.01698), [VisDial](https://arxiv.org/abs/1611.08669), [LLaVAR pretraining](https://arxiv.org/abs/2306.17107), [LVIS-Instruct4V](https://arxiv.org/abs/2311.07574), [LLaVAR finetuning](https://arxiv.org/abs/2306.17107), [LVIS-Instruct4V](https://arxiv.org/abs/2311.07574), [LLaVA-ReCap-CC3M](https://huggingface.co/datasets/lmms-lab/LLaVA-ReCap-CC3M), [AesMMIT](https://arxiv.org/abs/2404.14810), [Infinity-MM-Stage2](https://arxiv.org/abs/2410.18558), [Infinity-MM-Stage3](https://arxiv.org/abs/2410.18558), [Infinity-MM-Stage4](https://arxiv.org/abs/2410.18558), [ALLaVA-Instruct-VFLAN](https://arxiv.org/abs/2402.11684), [ALLaVA-Instruct-LAION](https://arxiv.org/abs/2402.11684) |
| **AgentTrajectories** | [ProcTHOR-10K](https://arxiv.org/abs/2206.06994), [Habitat-Web](https://arxiv.org/abs/2209.07469), [VIMA-Bench](https://arxiv.org/abs/2210.03094), [AITW](https://arxiv.org/abs/2307.15112), [ANDROIDCONTROL](https://arxiv.org/abs/2406.03679) |
| **Multi-View** | [CroCo Habitat](https://arxiv.org/abs/2310.02413), [Objaverse (1.0)](https://arxiv.org/abs/2212.08051), [BlendedMVS](https://arxiv.org/abs/2004.04412), [MVImgNet2.0](https://arxiv.org/abs/2412.01430) |
| **Interleaved Image/Text** | [OBELICS](https://huggingface.co/datasets/HuggingFaceTB/obelix), [MMC4-core-ff](https://arxiv.org/abs/2304.06939), [MMC4](https://arxiv.org/abs/2304.06939), [WikiHow](https://arxiv.org/abs/1810.09305), [WIT](https://arxiv.org/abs/2103.01913), [OmniCorpus](https://arxiv.org/abs/2406.01893), [DocStruct4M](https://arxiv.org/abs/2403.12895), [Pixelprose_commonpool](https://arxiv.org/abs/2406.10328), [CoMM](https://arxiv.org/abs/2406.10462) |
| **Audio** | [VGG-SOUND](https://arxiv.org/abs/2004.12843), [Kinetics-Sounds](https://arxiv.org/abs/1710.01135), [AudioSet](https://research.google/pubs/pub45857/), [LJ Speech](https://keithito.com/LJ-Speech-Dataset/), [MLS](https://arxiv.org/abs/2012.03411), [GigaSpeech](https://arxiv.org/abs/2106.06909), [MACS](https://arxiv.org/abs/1711.00282), [AudioCaps](https://aclanthology.org/N19-1011/), [Clotho](https://arxiv.org/abs/1910.09387), [MusicCaps](https://arxiv.org/abs/2301.11325), [Libriheavy](https://arxiv.org/abs/2210.06241), [MusicGen-Synthesis](https://huggingface.co/datasets/ogbanugot/musicgen) |
| **video-text** | [VATEX](https://arxiv.org/abs/1904.03493), [WebVid-2M](https://arxiv.org/abs/2102.08969), [MSR-VTT](https://aclanthology.org/P16-1141/), [YouTube-BB](https://arxiv.org/abs/1705.00641), [WebVid-10M](https://arxiv.org/abs/2102.08969), [Vript](https://arxiv.org/abs/2305.15525), [InternVid-14M-AES](https://arxiv.org/abs/2307.06942), [InternVid](https://arxiv.org/abs/2307.06942), [HowTo-100M](https://arxiv.org/abs/1906.03327), [LaSOT](https://arxiv.org/abs/1809.07845), [GOT-10k](https://arxiv.org/abs/1810.11981), [AVA](https://arxiv.org/abs/1705.08421), [Koala-36M](https://arxiv.org/abs/2306.02704), [LLaVA-Video](https://arxiv.org/abs/2410.02713) |
| **Video** | [YT-Temporal-180M](https://arxiv.org/abs/2112.06138), [YT-Temporal-1B](https://arxiv.org/abs/2205.09313), [ACAV](https://arxiv.org/abs/2103.01112), [HD-VILA-100M](https://arxiv.org/abs/2106.05389), [UCF101](https://arxiv.org/abs/1212.0402), [Ego4D](https://arxiv.org/abs/2110.07058), [Kinetics-700](https://arxiv.org/abs/1705.06950), [Something-Something V2](https://arxiv.org/abs/1706.04261), [EPIC-KITCHENS-100](https://epic-kitchens.github.io/2021) |
| **Html/xml** | [Common Crawl News (CC-NEWS)-CM3](https://github.com/Web-scrobbler/news-please), [En-Wikipedia](https://dumps.wikimedia.org/), [Wikipedia](https://dumps.wikimedia.org/) |
| **VQA** | [VQA v2.0](https://arxiv.org/abs/1612.00837), [GQA](https://arxiv.org/abs/1902.09506), [VizWizVQA](https://arxiv.org/abs/1802.08218), [OKVQA](https://arxiv.org/abs/1906.00282), [A-OKVQA](https://arxiv.org/abs/2206.01718), [SciGraphQA](https://arxiv.org/abs/2308.03349), [TallyQA](https://arxiv.org/abs/2112.06283), [OCR-VQA-200K](https://arxiv.org/abs/1910.09654), [ScienceQA](https://arxiv.org/abs/2209.09513), [VCR](https://arxiv.org/abs/1811.07435), [MSVD-QA](https://www.cs.utexas.edu/~gjyoo/video-qa/about.html), [Geo170K](https://arxiv.org/abs/2312.11370), [MSRVTT-QA](https://github.com/antoine77340/MSRVTT-QA), [STAR](https://arxiv.org/abs/2405.09711), [M4-ViteVQA](https://arxiv.org/abs/2205.07688), [DVQA](https://arxiv.org/abs/1905.04940), [ALLaVA-Instruct-4V](https://arxiv.org/abs/2402.11684), [ChartQA](https://arxiv.org/abs/2203.09028), [WebSRC](https://arxiv.org/abs/2104.00790) |
| **Image/Text** | [LAION Aesthetics v2.5](https://laion.ai/blog/laion-aesthetics/), [LAION-400M](https://arxiv.org/abs/2111.02114), [LAION-2B-en](https://arxiv.org/abs/2210.08402), [WebLI](https://arxiv.org/abs/2209.06794), [Subjects200K](https://arxiv.org/abs/2411.15098), [LAION-5B](https://arxiv.org/abs/2210.08402), [LAION-COCO](https://laion.ai/blog/laion-coco/), [Conceptual 12M (CC-12M)](https://arxiv.org/abs/2102.08981), [RedCaps](https://arxiv.org/abs/2111.11431), [APDDv2](https://arxiv.org/abs/2411.08545), [MSCOCO image captions (COCO)](https://arxiv.org/abs/1405.0312), [RefCOCO](https://arxiv.org/abs/1405.0312), [RefCOCO+](https://arxiv.org/abs/1405.0312), [DenseFusion-4V-100K](), [RefCOCOg](https://arxiv.org/abs/1511.02283), [CC3M train](https://aclanthology.org/P18-1238/), [OpenImages-v4-boxes](https://arxiv.org/abs/1811.00982), [Objects365](https://arxiv.org/abs/1905.06361), [YFCC100M](https://dl.acm.org/doi/10.1145/2647868), [LVIS](https://arxiv.org/abs/1908.03195), [NLVR](https://aclanthology.org/Q17-1025/), [NLVR2](https://arxiv.org/abs/1811.00491), [VSR-randomsplit](https://arxiv.org/abs/1912.08493), [VSR-zero-shot-split](https://arxiv.org/abs/1912.08493), [PDFA](https://huggingface.co/datasets/pixparse/pdfa-eng-wds), [OMNI3D](https://arxiv.org/abs/2207.10660), [OmniLabel](https://arxiv.org/abs/2206.05226), [COCO-Text](https://arxiv.org/abs/1601.07140), [Taskonomy](https://arxiv.org/abs/1806.02466), [SBU](https://aclanthology.org/P11-1052/), [TextOCR](https://arxiv.org/abs/2103.11977), [JourneyDB](https://arxiv.org/abs/2306.10951), [COCO-stuff](https://arxiv.org/abs/1612.03716), [PACO-LVIS](https://arxiv.org/abs/2106.05929), [PartImageNet](https://arxiv.org/abs/2201.08893), [DATACOMP-1B](https://arxiv.org/abs/2304.14113), [PASCAL-Part](https://www.eecs.berkeley.edu/~sgupta/pdf/chen_cvpr2014.pdf), [ALLaVA-Caption-4V](https://arxiv.org/abs/2402.11684), [LAION-GPT-4V](https://huggingface.co/datasets/jackyhate/text-to-image-2M), [ADE20K](http://people.csail.mit.edu/bzhou/publication/scene-parse-cvpr17.pdf), [Unsplash-Lite](https://unsplash.com/data), [Unsplash-Full](https://unsplash.com/data), [MARIO-LAION](https://arxiv.org/abs/2302.09415), [ShareGPT4V](https://arxiv.org/abs/2311.12793), [ShareGPT4V-PT](https://arxiv.org/abs/2311.12793), [COYO-700M](https://github.com/kakaobrain/coyo-dataset), [CapsFusion](https://arxiv.org/abs/2306.12213), [GRIT-20M](https://arxiv.org/abs/2306.14824), [Infinity-MM-Stage1](https://arxiv.org/abs/2410.18558), [BLIP3o-Pretrain-Long-Caption](https://arxiv.org/abs/2505.09568), [DenseFusion-1M](https://arxiv.org/abs/2405.02324) |
| **Image** | [NYU Depth Dataset V2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html), [ImageNet 2012](http://www.image-net.org/challenges/LSVRC/2012/), [ImageNet-21K](http://www.image-net.org/about-stats), [Places365-Standard](http://places2.csail.mit.edu/download.html), [Places365-Challenge](http://places2.csail.mit.edu/download.html), [Sun397](https://vision.princeton.edu/projects/2010/SUN/), [inaturalist (iNat2017)](https://arxiv.org/abs/1707.06642), [Flying Chairs](https://arxiv.org/abs/1504.06852), [CUB-200](http://www.vision.caltech.edu/visguide/CUB-200-2011.html), [Segment Anything 1B (SA-1B)](https://arxiv.org/abs/2304.02643), [MPI Sintel](http://sintel.is.tue.mpg.de/), [TAD66K](https://arxiv.org/abs/2204.12683) |


# Citation
If you find our work helpful for your research, please consider citing our work.

```plain
@article{yang2025survey,
  title={A Survey of Unified Multimodal Understanding and Generation: Advances and Challenges},
  author={Yang, Yan and Tian, Haochen and Shi, Yang and Xie, Wulin and Zhang, Yi-Fan and Dong, Yuhao and Hu, Yibo and Wang, Liang and He, Ran and Shan, Caifeng and others},
  journal={Authorea Preprints},
  year={2025},
  publisher={Authorea}
}
```