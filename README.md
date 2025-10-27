# A Survey of Unified Multimodal Understanding and Generation: Advances and Challenges


<p align="center">
    <img src="./images/tree.svg" width="99%" height="80%">
</p>

<font size=7><div align='center' > [[📖 arXiv Paper](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)] [[💬 WeChat (MLLM微信交流群，欢迎加入)](./images/wechat-group.png)]</div></font>  

<font size=7><div align='center' > The first systematic survey dedicated to MLLM alignment!  ✨ </div></font>


---

## Table of Contents
- [Modeling](#modeling)
    - [External Expert Integration Modeling](#External-Expert-Integration-Modeling)
    - [Modular Joint Modeling](#Modular-Joint-Modeling)
        - [Prompt-Mediated](#Prompt-Mediated)
        - [Representation-Mediated](#Representation-Mediated)
    - [End-to-End Unified Modeling](#End-to-End-Unified-Modeling)
        - [Autoregressive](#Autoregressive)
        - [Diffusion](#Diffusion)
        - [Hybrid](#Hybrid)
- [Encoding](#Encoding)
    - [Continuous Representation](#Continuous-Representation)
    - [Discrete Representation](#Discrete-Representation)
    - [Hybrid Representation](#Hybrid-Representation)
- [Decoding](#Decoding)
    - [Continuous Representation](#Continuous-Representation-1)
    - [Discrete Representation](#Discrete-Representation-1)
    - [Hybrid Representation](#Hybrid-Representation-1)
- [Training Dataset](#Training-Dataset)
- [Benchmark](#Benchmark)

# Modeling

## External Expert Integration Modeling
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/chenfei-wu/TaskMatrix?style=social) <br> [**Visual ChatGPT: Talking, Drawing and Editing with Visual Foundation Models**](https://arxiv.org/pdf/2303.04671) <br> | arXiv | 2023-03 | [Github](https://github.com/chenfei-wu/TaskMatrix) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/JARVIS?style=social) <br> [**HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face**](https://arxiv.org/pdf/2303.17580) <br> | NeurIPS | 2023-03 | [Github](https://github.com/microsoft/JARVIS) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/AIGC-Audio/AudioGPT?style=social) <br> [**AudioGPT: Understanding and Generating Speech, Music, Sound, and Talking Head**](https://arxiv.org/pdf/2304.12995) <br> | arXiv | 2023-04 | [Github](https://github.com/AIGC-Audio/AudioGPT) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/0nutation/SpeechGPT?style=social) <br> [**SpeechGPT: Empowering Large Language Models with Intrinsic Cross-Modal Conversational Abilities**](https://arxiv.org/pdf/2305.11000) <br> | arXiv | 2023-05 | [Github](https://github.com/0nutation/SpeechGPT) | - |


## Modular Joint Modeling
### Prompt-Mediated
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/xiangyu-mm/EasyGen?style=social) <br> [**EasyGen: Easing Multimodal Generation with BiDiffuser and LLMs**](https://arxiv.org/pdf/2310.08949) <br> | ACL | 2023-10 | [Github](https://github.com/xiangyu-mm/EasyGen) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/dvlab-research/MGM?style=social) <br> [**Mini-Gemini: Mining the Potential of Multi-modality Vision Language Models**](https://arxiv.org/pdf/2403.18814) <br> | arXiv | 2024-03 | [Github](https://github.com/dvlab-research/MGM) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/friedrichor/TIGER?style=social) <br> [**TIGER: A Unified Generative Model Framework for Multimodal Dialogue Response Generation**](https://aclanthology.org/2024.lrec-main.1403.pdf) <br> | LREC | 2024-05 | [Github](https://github.com/friedrichor/TIGER) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Layjins/Spider?style=social) <br> [**Spider: Any-to-Many Multimodal LLM**](https://arxiv.org/pdf/2411.09439) <br> | arXiv | 2024-11 | [Github](https://github.com/Layjins/Spider) | - |

### Representation-Mediated
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/baaivision/Emu?style=social) <br> [**Emu: Generative Pretraining in Multimodality**](https://arxiv.org/pdf/2307.05222) <br> | ICLR | 2023-07 | [Github](https://github.com/baaivision/Emu) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/eric-ai-lab/MiniGPT-5?style=social) <br> [**MiniGPT-5: Interleaved Vision-and-Language Generation via Generative Vokens**](https://arxiv.org/pdf/2310.02239) <br> | arXiv | 2023-10 | [Github](https://github.com/eric-ai-lab/MiniGPT-5) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/baaivision/Emu?style=social) <br> [**Generative Multimodal Models are In-Context Learners**](https://arxiv.org/pdf/2312.13286) <br> | CVPR | 2023-12 | [Github](https://github.com/baaivision/Emu) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/AILab-CVC/VL-GPT?style=social) <br> [**VL-GPT: A Generative Pre-trained Transformer for Vision and Language Understanding and Generation**](https://arxiv.org/pdf/2312.09251) <br> | arXiv | 2023-12 | [Github](https://github.com/AILab-CVC/VL-GPT) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenGVLab/MM-Interleaved?style=social) <br> [**MM-Interleaved: Interleaved Image-Text Generative Modeling via Multi-modal Feature Synchronizer**](https://arxiv.org/pdf/2401.10208) <br> | arXiv | 2024-01 | [Github](https://github.com/OpenGVLab/MM-Interleaved) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/bytedance/TextHarmony?style=social) <br> [**Harmonizing Visual Text Comprehension and Generation**](https://arxiv.org/pdf/2407.16364) <br> | NeurIPS | 2024-07 | [Github](https://github.com/bytedance/TextHarmony) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/metamorph?style=social) <br> [**MetaMorph: Multimodal Understanding and Generation via Instruction Tuning**](https://arxiv.org/pdf/2412.14164) <br> | ICCV | 2024-12 | [Github](https://github.com/facebookresearch/metamorph/) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/hzphzp/WeGen?style=social) <br> [**WeGen: AUnified Model for Interactive Multimodal Generation as We Chat**](https://arxiv.org/pdf/2503.01115) <br> | arXiv | 2025-03 | [Github](https://github.com/hzphzp/WeGen) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/VARGPT-family/VARGPT-v1.1?style=social) <br> [**Vargpt-v1. 1: Improve visual autoregressive large unified model via iterative instruction tuning and reinforcement learning**](https://arxiv.org/pdf/2504.02949) <br> | arXiv | 2025-04 | [Github](https://github.com/VARGPT-family/VARGPT-v1.1) | [Page](https://vargpt1-1.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/modelscope/Nexus-Gen?style=social) <br> [**Nexus-Gen: A Unified Model for Image Understanding, Generation, and Editing**](https://arxiv.org/pdf/2504.21356) <br> | arXiv | 2025-04 | [Github](https://github.com/modelscope/Nexus-Gen) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/showlab/UniRL?style=social) <br> [**UniRL: Self-Improving Unified Multimodal Models via Supervised and Reinforcement Learning**](https://arxiv.org/pdf/2505.23380) <br> | arXiv | 2025-05 | [Github](https://github.com/showlab/UniRL) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/JiuhaiChen/BLIP3o?style=social) <br> [**BLIP3-o: A Family of Fully Open Unified Multimodal Models-Architecture, Training and Dataset**](https://arxiv.org/pdf/2505.09568) <br> | arXiv | 2025-06 | [Github](https://github.com/JiuhaiChen/BLIP3o) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/VectorSpaceLab/OmniGen2?style=social) <br> [**OmniGen2: Exploration to Advanced Multimodal Generation**](https://arxiv.org/pdf/2506.18871) <br> | arXiv | 2025-06 | [Github](https://github.com/VectorSpaceLab/OmniGen2) | [Page](https://vectorspacelab.github.io/OmniGen2/) |



## End-to-End Unified Modeling
### Autoregressive
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/LargeWorldModel/LWM?style=social) <br> [**World Model on Million-Length Video And Language With Blockwise RingAttention**](https://arxiv.org/pdf/2402.08268) <br> | ICLR | 2024-02 | [Github](https://github.com/LargeWorldModel/LWM) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/chameleon?style=social) <br> [**Chameleon: Mixed-Modal Early-Fusion Foundation Models**](https://arxiv.org/pdf/2405.09818) <br> | arXiv | 2024-05 | [Github](https://github.com/facebookresearch/chameleon) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/GAIR-NLP/anole?style=social) <br> [**ANOLE: An Open, Autoregressive, Native Large Multimodal Models for Interleaved Image-Text Generation**](https://arxiv.org/pdf/2407.06135) <br> | arXiv | 2024-07 | [Github](https://github.com/GAIR-NLP/anole) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Alpha-VLLM/Lumina-mGPT?style=social) <br> [**Lumina-mGPT: Illuminate Flexible Photorealistic Text-to-Image Generation with Multimodal Generative Pretraining**](https://arxiv.org/pdf/2408.02657) <br> | arXiv | 2024-08 | [Github](https://github.com/Alpha-VLLM/Lumina-mGPT) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/baaivision/Emu3?style=social) <br> [**Emu3: Next-Token Prediction is All You Need**](https://arxiv.org/pdf/2409.18869) <br> | arXiv | 2024-09 | [Github](https://github.com/baaivision/Emu3) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/Janus?style=social) <br> [**Janus-Pro: Unified Multimodal Understanding and Generation with Data and Model Scaling**](https://arxiv.org/pdf/2501.17811) <br> | arXiv | 2025-01 | [Github](https://github.com/deepseek-ai/Janus) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/finyorko/armor?style=social) <br> [**ARMOR: Empowering Multimodal Understanding Model with Interleaved Multimodal Generation Capability**](https://arxiv.org/pdf/2503.06542) <br> | arXiv | 2025-03 | [Github](https://github.com/finyorko/armor) | - |

### Diffusion
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/SHI-Labs/Versatile-Diffusion?style=social) <br> [**Versatile Diffusion: Text, Images and Variations All in One Diffusion Model**](https://arxiv.org/pdf/2211.08332) <br> | ICCV | 2022-11 | [Github](https://github.com/SHI-Labs/Versatile-Diffusion) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/thu-ml/unidiffuser?style=social) <br> [**One Transformer Fits All Distributions in Multi-Modal Diffusion at Scale**](https://arxiv.org/pdf/2303.06555) <br> | ICML | 2023-03 | [Github](https://github.com/thu-ml/unidiffuser) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/microsoft/i-Code?style=social) <br> [**Any-to-Any Generation via Composable Diffusion**](https://arxiv.org/pdf/2305.11846) <br> | NeurIPS | 2023-05 | [Github](https://github.com/microsoft/i-Code/tree/main/i-Code-V3) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/jacklishufan/OmniFlows?style=social) <br> [**OmniFlow: Any-to-Any Generation with Multi-Modal Rectified Flows**](https://arxiv.org/pdf/2412.01169) <br> | arXiv | 2024-12 | [Github](https://github.com/jacklishufan/OmniFlows) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/zhijie-group/UniCMs?style=social) <br> [**UniCMs: A Unified Consistency Model For Efficient Multimodal Generation and Understanding**](https://arxiv.org/pdf/2502.05415) <br> | arXiv | 2025-02 | [Github](https://github.com/zhijie-group/UniCMs) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/alexanderswerdlow/unidisc?style=social) <br> [**Unified Multimodal Discrete Diffusion**](https://arxiv.org/pdf/2503.20853) <br> | arXiv | 2025-03 | [Github](https://github.com/alexanderswerdlow/unidisc) | [Page](https://unidisc.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Gen-Verse/MMaDA?style=social) <br> [**MMaDA: Multimodal Large Diffusion Language Models**](https://arxiv.org/pdf/2505.15809) <br> | arXiv | 2025-05 | [Github](https://github.com/Gen-Verse/MMaDA) | - |

### Hybrid
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/showlab/Show-o?style=social) <br> [**Show-o: One Single Transformer to Unify Multimodal Understanding and Generation**](https://arxiv.org/pdf/2408.12528) <br> | ICLR | 2024-09 | [Github](https://github.com/showlab/Show-o) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/MonoFormer/MonoFormer?style=social) <br> [**MonoFormer: One Transformer for Both Diffusion and Autoregression**](https://arxiv.org/pdf/2409.16280) <br> | arXiv | 2024-09 | [Github](https://github.com/MonoFormer/MonoFormer) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/Janus?style=social) <br> [**JanusFlow: Harmonizing Autoregression and Rectified Flow for Unified Multimodal Understanding and Generation**](https://arxiv.org/pdf/2411.07975) <br> | CVPR | 2024-11 | [Github](https://github.com/deepseek-ai/Janus) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/Mixture-of-Transformers?style=social) <br> [**Mixture-of-Transformers: A Sparse and Scalable Architecture for Multi-Modal Foundation Models**](https://arxiv.org/pdf/2411.04996) <br> | ICLR | 2024-11 | [Github](https://github.com/facebookresearch/Mixture-of-Transformers) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/bytedance-seed/BAGEL?style=social) <br> [**Emerging Properties in Unified Multimodal Pretraining**](https://arxiv.org/pdf/2505.14683) <br> | arXiv | 2025-05 | [Github](https://github.com/bytedance-seed/BAGEL) | [Page](https://bagel-ai.org/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/arctanxarc/UniCTokens?style=social) <br> [**UniCTokens: Boosting Personalized Understanding and Generation via Unified Concept Tokens**](https://arxiv.org/pdf/2505.14671v1) <br> | arXiv | 2025-05 | [Github](https://github.com/arctanxarc/UniCTokens) | - |

# Encoding
## Continuous Representation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/OFA-Sys/OFA?style=social) <br> [**OFA: Unifying Architectures, Tasks, and Modalities Through a Simple Sequence-to-Sequence Learning Framework**](https://arxiv.org/pdf/2202.03052) <br> | ICML | 2022-02 | [Github](https://github.com/OFA-Sys/OFA) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/allenai/unified-io-inference?style=social) <br> [**Unified-IO: A Unified Model for Vision, Language, and Multi-Modal Tasks**](https://arxiv.org/pdf/2206.08916) <br> | ICLR | 2022-06 | [Github](https://github.com/allenai/unified-io-inference) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/shizhediao/DaVinci?style=social) <br> [**WRITE AND PAINT: GENERATIVE VISION-LANGUAGE MODELS ARE UNIFIED MODAL LEARNERS**](https://arxiv.org/pdf/2206.07699) <br> | arXiv | 2022-06 | [Github](https://github.com/shizhediao/DaVinci) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/TXH-mercury/VALOR?style=social) <br> [**VALOR: Vision-Audio-Language Omni-Perception Pretraining Model and Dataset**](https://arxiv.org/pdf/2304.08345) <br> | arXiv | 2023-04 | [Github](https://github.com/TXH-mercury/VALOR) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/RunpeiDong/DreamLLM?style=social) <br> [**DreamLLM: Synergistic Multimodal Comprehension and Creation**](https://arxiv.org/pdf/2309.11499) <br> | ICLR | 2023-09 | [Github](https://github.com/RunpeiDong/DreamLLM) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/xinke-wang/ModaVerse?style=social) <br> [**ModaVerse: Efficiently Transforming Modalities with LLMs**](https://arxiv.org/pdf/2401.06395) <br> | CVPR | 2024-01 | [Github](https://github.com/xinke-wang/ModaVerse) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/rongyaofang/PUMA?style=social) <br> [**PUMA: Empowering Unified MLLM with Multi-granular Visual Generation**](https://arxiv.org/pdf/2410.13861) <br> | arXiv | 2024-10 | [Github](https://github.com/rongyaofang/PUMA) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/zhijie-group/Orthus?style=social) <br> [**Orthus: Autoregressive Interleaved Image-Text Generation with Modality-Specific Experts**](https://arxiv.org/pdf/2412.00127) <br> | ICML | 2024-12 | [Github](https://github.com/zhijie-group/Orthus) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/zijieli-Jlee/Dual-Diffusion?style=social) <br> [**Dual Diffusion for Unified Image Generation and Understanding**](https://arxiv.org/pdf/2501.00289) <br> | CVPR | 2025-01 | [Github](https://github.com/zijieli-Jlee/Dual-Diffusion) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/VARGPT-family/VARGPT?style=social) <br> [**VARGPT: Next-Generation Multi-Modal AI Agent with Unified Vision-Audio-Text Generation**](https://arxiv.org/pdf/2501.12327) <br> | arXiv | 2025-01 | [Github](https://github.com/VARGPT-family/VARGPT) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/wusize/Harmon?style=social) <br> [**Harmonizing visual representations for unified multimodal understanding and generation**](https://arxiv.org/pdf/2503.21979v1) <br> | arXiv | 2025-03 | [Github](https://github.com/wusize/Harmon) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/inclusionAI/Ming?style=social) <br> [**Ming-Omni: A Unified Multimodal Model for Perception and Generation**](http://arxiv.org/pdf/2506.09344v1) <br> | arXiv | 2025-06 | [Github](https://github.com/inclusionAI/Ming/tree/main) | [Page](https://lucaria-academy.github.io/Ming-Omni/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/showlab/Show-o?style=social) <br> [**Show-o2: Improved Native Unified Multimodal Models**](https://arxiv.org/pdf/2506.15564) <br> | arXiv | 2025-06 | [Github](https://github.com/showlab/Show-o) | - |


## Discrete Representation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/MIO-Team/MIO?style=social) <br> [**MIO: A Foundation Model on Multimodal Tokens**](https://arxiv.org/pdf/2409.17692) <br> | arXiv | 2024-09 | [Github](https://github.com/MIO-Team/MIO) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/FoundationVision/Liquid?style=social) <br> [**Liquid: Language Models are Scalable Multi-modal Generators**](https://arxiv.org/pdf/2412.04332) <br> | arXiv | 2024-12 | [Github](https://github.com/FoundationVision/Liquid) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/tliby/UniFork?style=social) <br> [**UniFork: Exploring Modality Alignment for Unified Multimodal Understanding and Generation**](https://arxiv.org/pdf/2506.17202) <br> | arXiv | 2025-06 | [Github](https://github.com/tliby/UniFork) | - |

## Hybrid Representation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/AILab-CVC/SEED?style=social) <br> [**Planting a SEED of Vision in Large Language Model**](https://arxiv.org/pdf/2310.01218) <br> | ICLR | 2023-10 | [Github](https://github.com/AILab-CVC/SEED) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenMOSS/AnyGPT?style=social) <br> [**AnyGPT: Unified Multimodal LLM with Discrete Sequence Modeling**](https://arxiv.org/pdf/2402.12226) <br> | ACL | 2024-02 | [Github](https://github.com/OpenMOSS/AnyGPT) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/jy0205/LaVIT?style=social) <br> [**Video-LaVIT: Unified Video-Language Pre-training with Decoupled Visual-Motional Tokenization**](https://arxiv.org/pdf/2402.03161) <br> | ICML | 2024-02 | [Github](https://github.com/jy0205/LaVIT) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/mit-han-lab/vila-u?style=social) <br> [**VILA-U: An Unified Foundation Model Integrating Visual Understanding and Generation**](https://arxiv.org/pdf/2409.04429) <br> | arXiv | 2024-09 | [Github](https://github.com/mit-han-lab/vila-u) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/deepseek-ai/Janus?style=social) <br> [**Janus: Decoupling Visual Encoding for Unified Multimodal Understanding and Generation**](https://arxiv.org/pdf/2410.13848) <br> | CVPR | 2024-10 | [Github](https://github.com/deepseek-ai/Janus) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/ByteVisionLab/TokenFlow?style=social) <br> [**TokenFlow: Unified Image Tokenizer for Multimodal Understanding and Generation**](https://arxiv.org/pdf/2412.03069) <br> | CVPR | 2024-12 | [Github](https://github.com/ByteVisionLab/TokenFlow) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/hustvl/OmniMamba?style=social) <br> [**Omnimamba: Efficient and unified multimodal understanding and generation via state space models**](https://arxiv.org/pdf/2503.08686) <br> | arXiv | 2025-03 | [Github](https://github.com/hustvl/OmniMamba) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/illume-unified-mllm/ILLUME_plus?style=social) <br> [**Illume+: Illuminating unified mllm with dual visual tokenization and diffusion refinement**](https://arxiv.org/pdf/2504.01934) <br> | arXiv | 2025-04 | [Github](https://github.com/illume-unified-mllm/ILLUME_plus) | [Page](https://illume-unified-mllm.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/SxJyJay/UniToken?style=social) <br> [**UniToken: Harmonizing Multimodal Understanding and Generation through Unified Visual Encoding**](https://arxiv.org/pdf/2504.04423v1) <br> | CVPR | 2025-04 | [Github](https://github.com/SxJyJay/UniToken) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/mm-vl/ULM-R1?style=social) <br> [**Co-Reinforcement Learning for Unified Multimodal Understanding and Generation**](https://arxiv.org/pdf/2505.17534) <br> | arXiv | 2025-05 | [Github](https://github.com/mm-vl/ULM-R1) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/FreedomIntelligence/ShareGPT-4o-Image?style=social) <br> [**ShareGPT-4o-Image: Aligning Multimodal Models with GPT-4o-Level Image Generation**](https://arxiv.org/pdf/2506.18095) <br> | arXiv | 2025-06 | [Github](https://github.com/FreedomIntelligence/ShareGPT-4o-Image) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/csuhan/Tar?style=social) <br> [**Vision as a Dialect: Unifying Visual Understanding and Generation via Text-Aligned Representations**](https://arxiv.org/pdf/2506.18898) <br> | arXiv | 2025-06 | [Github](https://github.com/csuhan/Tar) | [Page](https://tar.csuhan.com/) |


# Decoding
## Continuous Representation
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

## Discrete Representation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/allenai/unified-io-2?style=social) <br> [**Unified-IO 2: Scaling Autoregressive Multimodal Models with Vision, Language, Audio, and Action**](https://arxiv.org/pdf/2312.17172) <br> | CVPR | 2023-12 | [Github](https://github.com/allenai/unified-io-2) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/NVlabs/QLIP?style=social) <br> [**QLIP: Text-Aligned Visual Tokenization Unifies Auto-Regressive Multimodal Understanding and Generation**](https://arxiv.org/pdf/2502.05178) <br> | arXiv | 2025-02 | [Github](https://github.com/NVlabs/QLIP/tree/main) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/FoundationVision/UniTok?style=social) <br> [**UniTok: A Unified Tokenizer for Visual Generation and Understanding**](https://arxiv.org/pdf/2502.20321) <br> | arXiv | 2025-02 | [Github](https://github.com/FoundationVision/UniTok) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/TencentARC/TokLIP?style=social) <br> [**TokLIP: Marry Visual Tokens to CLIP for Multimodal Comprehension and Generation**](https://www.arxiv.org/pdf/2505.05422) <br> | arXiv | 2025-05 | [Github](https://github.com/TencentARC/TokLIP) | - |

## Hybrid Representation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/jy0205/LaVIT?style=social) <br> [**Unified Language-Vision Pretraining in LLM with Dynamic Discrete Visual Tokenization**](https://arxiv.org/pdf/2309.04669) <br> | ICLR | 2023-09 | [Github](https://github.com/jy0205/LaVIT) | - |

<!-- # Training Dataset
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|


# Benchmark
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:| -->
