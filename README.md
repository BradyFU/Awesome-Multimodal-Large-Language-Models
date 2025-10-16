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
    - [Modular Joint Modeling](#multi-image-video-and-audio)
        - [Prompt-Mediated](#Prompt-Mediated)
        - [Representation-Mediated](#Representation-Mediated)
    - [End-to-End Unified Modeling](#End-to-End-Unified-Modeling)
        - [Autoregressive](#Autoregressive)
        - [Diffusion](#Diffusion)
        - [Hybrid](#Hybrid)
- [ENCODING](#ENCODING)
    - [Continuous Representation](#Continuous-Representation)
    - [Discrete Representation](#Discrete-Representation)
    - [Hybrid Representation](#Hybrid-Representation)
        - [Cascade Encoding Strategy](#Cascade-Encoding-Strategy)
        - [Dual-Branch Hybrid Encoding](#Dual-Branch-Hybrid-Encoding)
- [DECODING](#DECODING)
    - [Continuous Representation](#Continuous-Representation)
        - [External Generation](#External-Generation)
        - [Internal Generation](#Internal-Generation)
    - [Discrete Representation](#Discrete-Representation)
    - [Hybrid Representation](#Hybrid-Representation)
- [Training Dataset](#Training-Dataset)
- [Benchmark](#Benchmark)

# Application Scenarios
## General Image Understanding
### Mitigating Hallucinations
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/taco-group/Re-Align?style=social) <br> [**Re-Align: Aligning Vision Language Models via Retrieval-Augmented Direct Preference Optimization**](https://www.arxiv.org/abs/2502.13146) <br> | arXiv | 2025-02 | [Github](https://github.com/taco-group/Re-Align) | [Page](https://taco-group.github.io/Re-Align/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/injadlu/DAMA?style=social) <br> [**DAMA: Data- and Model-aware Alignment of Multi-modal LLMs**](https://arxiv.org/abs/2502.01943) <br> | arXiv | 2025-02 | [Github](https://github.com/injadlu/DAMA) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/zhyang2226/OPA-DPO?style=social) <br> [**Mitigating Hallucinations in Large Vision-Language Models via DPO: On-Policy Data Hold the Key**](https://arxiv.org/abs/2501.09695) <br> | arXiv | 2025-01 | [Github](https://github.com/zhyang2226/OPA-DPO) | [Page](https://opa-dpo.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/zhyang2226/OPA-DPO?style=social) <br> [**Mitigating Hallucinations in Large Vision-Language Models via DPO: On-Policy Data Hold the Key**](https://arxiv.org/abs/2501.09695) <br> | arXiv | 2025-01 | [Github](https://github.com/zhyang2226/OPA-DPO) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/LVUGAI/CHiP?style=social) <br> [**CHiP: Cross-modal Hierarchical Direct Preference Optimization for Multimodal LLMs**](https://arxiv.org/abs/2501.16629) <br> | arXiv | 2025-01 | [Github](https://github.com/LVUGAI/CHiP) | - |
| [**Mitigating Hallucination in Multimodal Large Language Model via Hallucination-targeted Direct Preference Optimization**](https://arxiv.org/abs/2411.10436) <br> | arXiv | 2024-11 | - | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/salesforce/LAVIS?style=social) <br> [**xGen-MM (BLIP-3): A Family of Open Large Multimodal Models**](https://arxiv.org/abs/2408.08872) <br> | arXiv | 2024-08 | [Github](https://github.com/salesforce/LAVIS/tree/xgen-mm) | [Page](https://www.salesforceairesearch.com/opensource/xGen-MM/index.html) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/luka-group/mDPO?style=social) <br> [**mDPO: Conditional Preference Optimization for Multimodal Large Language Models**](https://arxiv.org/abs/2406.11839) <br> | arXiv | 2024-06 | [Github](https://github.com/luka-group/mDPO) | [Page](https://feiwang96.github.io/mDPO/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/RLHF-V/RLAIF-V?style=social) <br> [**RLAIF-V: Open-Source AI Feedback Leads to Super GPT-4V Trustworthiness**](https://arxiv.org/abs/2405.17220) <br> | arXiv | 2024-05 | [Github](https://github.com/RLHF-V/RLAIF-V) | - |
| ![Star](https://img.shields.io/github/stars/opendatalab/HA-DPO?style=social) <br> [**Beyond Hallucinations: Enhancing LVLMs through Hallucination-Aware Direct Preference Optimization**](https://arxiv.org/abs/2311.16839) <br> | arXiv | 2023-11 | [Github](https://github.com/opendatalab/HA-DPO) | [Page](https://opendatalab.github.io/HA-DPO/) |
| ![Star](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF?style=social) <br> [**Aligning Large Multimodal Models with Factually Augmented RLHF**](https://arxiv.org/abs/2309.14525) <br> | arXiv | 2023-09 | [Github](https://github.com/llava-rlhf/LLaVA-RLHF) |  [Page](https://llava-rlhf.github.io/) | 
| ![Star](https://img.shields.io/github/stars/RLHF-V/RLHF-V?style=social) <br> [**RLHF-V: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback**](https://arxiv.org/abs/2309.14525) <br> | arXiv | 2023-09 | [Github](https://github.com/RLHF-V/RLHF-V) |  [Page](https://rlhf-v.github.io/) |
| ![Star](https://img.shields.io/github/stars/hendryx-scale/mhal-detect?style=social) <br> [**Detecting and Preventing Hallucinations in Large Vision Language Models**](https://arxiv.org/abs/2308.06394) <br> | arXiv | 2023-08 | [Github](https://github.com/hendryx-scale/mhal-detect) | - |
### Enhancing Comprehensive Capabilities
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/Kwai-YuanQi/MM-RLHF?style=social) <br> [**MM-RLHF: The Next Step Forward in Multimodal LLM Alignment**](https://arxiv.org/abs/2502.10391) <br> | arXiv | 2025-02 | [Github](https://github.com/Kwai-YuanQi/MM-RLHF) | [Page](https://mm-rlhf.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/QwenLM/Qwen2.5-VL?style=social) <br> [**Qwen2.5-VL Technical Report**](https://arxiv.org/abs/2502.13923) <br> | arXiv | 2025-02 | [Github](https://github.com/QwenLM/Qwen2.5-VL) | [Page](https://qwenlm.github.io/zh/blog/qwen2.5-vl/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/PhoenixZ810/OmniAlign-V?style=social) <br> [**OmniAlign-V: Towards Enhanced Alignment of MLLMs with Human Preference**](https://arxiv.org/abs/2502.18411) <br> | arXiv | 2025-02 | [Github](https://github.com/PhoenixZ810/OmniAlign-V) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/pds-dpo/pds-dpo?style=social) <br> [**Multimodal Preference Data Synthetic Alignment with Reward Model**](https://arxiv.org/abs/2412.17417) <br> | arXiv | 2024-12 | [Github](https://github.com/pds-dpo/pds-dpo) | [Page](https://pds-dpo.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenGVLab/InternVL?style=social) <br> [**Enhancing the Reasoning Ability of Multimodal Large Language Models via Mixed Preference Optimization**](https://arxiv.org/abs/2411.10442) <br> | arXiv | 2024-11 | [Github](https://github.com/OpenGVLab/InternVL/tree/main) | [Page](https://internvl.github.io/blog/2024-12-20-InternVL-2.5-MPO/) |
|[**vVLM: Exploring Visual Reasoning in VLMs against Language Priors**](https://openreview.net/forum?id=lCqNxBGPp5) <br> | openreview | 2024-10 | - | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-NeXT?style=social) <br> [**LLaVA-Critic: Learning to Evaluate Multimodal Models**](https://arxiv.org/abs/2410.02712) <br> | arXiv | 2024-10 | [Github](https://github.com/LLaVA-VL/LLaVA-NeXT) | [Page](https://llava-vl.github.io/blog/2024-10-03-llava-critic/) |
|[**CLIP-DPO: Vision-Language Models as a Source of Preference for Fixing Hallucinations in LVLMs**](https://arxiv.org/abs/2408.10433) <br> | arXiv | 2024-08 | - | - |
|[**Enhancing Visual-Language Modality Alignment in Large Vision Language Models via Self-Improvement**](https://arxiv.org/abs/2405.15973) <br> | arXiv | 2024-05 | - | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/vlf-silkie/VLFeedback?style=social) <br> [**Silkie: Preference Distillation for Large Visual Language Models**](https://arxiv.org/abs/2312.10665) <br> | arXiv | 2023-12 | [Github](https://github.com/vlf-silkie/VLFeedback) | [Page](https://vlf-silkie.github.io/) |
### Multi-modal O1 Development
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/TideDra/lmm-r1?style=social) <br> [**LMM-R1**](https://github.com/TideDra/lmm-r1) <br> | github | 2025-02 | [Github](https://github.com/TideDra/lmm-r1) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Wang-Xiaodong1899/Open-R1-Video?style=social) <br> [**Open-R1-Video**](https://github.com/Wang-Xiaodong1899/Open-R1-Video) <br> | github | 2025-02 | [Github](https://github.com/Wang-Xiaodong1899/Open-R1-Video) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/om-ai-lab/VLM-R1?style=social) <br> [**VLM-R1: A stable and generalizable R1-style Large Vision-Language Model**](https://github.com/om-ai-lab/VLM-R1) <br> | github | 2025-02 | [Github](https://github.com/om-ai-lab/VLM-R1) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Deep-Agent/R1-V?style=social) <br> [**R1-V: Reinforcing Super Generalization Ability in Vision Language Models with Less Than $3**](https://github.com/Deep-Agent/R1-V) <br> | github | 2025-02 | [Github](https://github.com/Deep-Agent/R1-V) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/hiyouga/EasyR1?style=social) <br> [**EasyR1: An Efficient, Scalable, Multi-Modality RL Training Framework**](https://github.com/hiyouga/EasyR1) <br> | github | 2025-02 | [Github](https://github.com/hiyouga/EasyR1) | - |
## Multi-Image, Video, and Audio
### Multi-Image
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/Liuziyu77/MIA-DPO?style=social) <br> [**MIA-DPO: Multi-Image Augmented Direct Preference Optimization For Large Vision-Language Models**](https://arxiv.org/abs/2410.17637) <br> | arXiv | 2024-10 | [Github](https://github.com/Liuziyu77/MIA-DPO) | [Page](https://liuziyu77.github.io/MIA-DPO/) |
### ICL
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/APiaoG/SymDPO?style=social) <br> [**SymDPO: Boosting In-Context Learning of Large Multimodal Models with Symbol Demonstration Direct Preference Optimization**](https://arxiv.org/abs/2411.11909) <br> | arXiv | 2024-11 | [Github](https://github.com/APiaoG/SymDPO) | - |
### Video
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/Kwai-YuanQi/MM-RLHF?style=social) <br> [**MM-RLHF: The Next Step Forward in Multimodal LLM Alignment**](https://arxiv.org/abs/2502.10391) <br> | arXiv | 2025-02 | [Github](https://github.com/Kwai-YuanQi/MM-RLHF) | [Page](https://mm-rlhf.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/farewellthree/PPLLaVA?style=social) <br> [**PPLLaVA: Varied Video Sequence Understanding With Prompt Guidance**](https://arxiv.org/abs/2411.02327) <br> | arXiv | 2024-11 | [Github](https://github.com/farewellthree/PPLLaVA) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-NeXT?style=social) <br> [**LLaVA-NeXT-Interleave: Tackling Multi-image, Video, and 3D in Large Multimodal Models**](https://arxiv.org/abs/2407.07895) <br> | arXiv | 2024-07 | [Github](https://github.com/LLaVA-VL/LLaVA-NeXT) | [Page](https://llava-vl.github.io/blog/2024-06-16-llava-next-interleave/) |
### Audio-Visual
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
|[**Enhancing Multimodal LLM for Detailed and Accurate Video Captioning using Multi-Round Preference Optimization**](https://arxiv.org/abs/2410.06682) <br> | arXiv | 2024-10 | - | [Page](https://video-salmonn-2.github.io/) |
### Audio-Text
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
|[**SQuBa: Speech Mamba Language Model with Querying-Attention for Efficient Summarization**](https://openreview.net/forum?id=zOMa82W1HV) <br> | openreview | 2024-10 | - | - |
## Extended Multimodal Applications
### Medicine
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
|[**3D-CT-GPT++: Enhancing 3D Radiology Report Generation with Direct Preference Optimization and Large Vision-Language Models**](https://openreview.net/forum?id=LzycEbgLoi) <br> | openreview | 2024-10 | - | - |
### Mathematics
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/ZrrSkywalker/MAVIS?style=social) <br> [**MAVIS: Mathematical Visual Instruction Tuning with an Automatic Data Engine**](https://arxiv.org/abs/2407.08739) <br> | arXiv | 2024-07 | [Github](https://github.com/ZrrSkywalker/MAVIS) | [Page](https://mathverse-cuhk.github.io/) |
### Embodied Intelligence
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
|[**HomieBot: an Adaptive System for Embodied Mobile Manipulation in Open Environments**](https://openreview.net/forum?id=NQTrARs2pz&referrer=%5Bthe%20profile%20of%20Tianci%20Tang%5D(%2Fprofile%3Fid%3D~Tianci_Tang1)) <br> | openreview | 2024-10 | - | - |
|[**InteractiveCOT: Aligning Dynamic Chain-of-Thought Planning for Embodied Decision-Making**](https://openreview.net/forum?id=Y4iaDU4yMi) <br> | openreview | 2024-10 | - | - |
### Safety
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/Kwai-YuanQi/MM-RLHF?style=social) <br> [**MM-RLHF: The Next Step Forward in Multimodal LLM Alignment**](https://arxiv.org/abs/2502.10391) <br> | arXiv | 2025-02 | [Github](https://github.com/Kwai-YuanQi/MM-RLHF) | [Page](https://mm-rlhf.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Amirabbas-Afzali/Aligning-Visual-Contrastive-learning-models-via-Preference-Optimization?style=social) <br> [**Aligning Visual Contrastive learning models via Preference Optimization**](https://arxiv.org/abs/2411.08923) <br> | arXiv | 2024-11 | [Github](https://github.com/Amirabbas-Afzali/Aligning-Visual-Contrastive-learning-models-via-Preference-Optimization) | - |
|[**AdPO: Enhancing the Adversarial Robustness of Large Vision-Language Models with Preference Optimization**](https://openreview.net/forum?id=nbngu7H3ko) <br> | openreview | 2024-10 | - | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/ys-zong/VLGuard?style=social) <br> [**Safety Fine-Tuning at (Almost) No Cost: A Baseline for Vision Large Language Models**](https://arxiv.org/abs/2402.02207) <br> | arXiv | 2024-02 | [Github](https://github.com/ys-zong/VLGuard) | [Page](https://ys-zong.github.io/VLGuard/) |
### Agent 
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/RL4VLM/RL4VLM?style=social) <br> [**Fine-Tuning Large Vision-Language Models as Decision-Making Agents via Reinforcement Learning**](https://arxiv.org/abs/2405.10292) <br> | arXiv | 2024-05 | [Github](https://github.com/RL4VLM/RL4VLM) | [Page](https://rl4vlm.github.io/) |
# Dataset Construction
## Using External Knowledge
### Human Annotation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/Kwai-YuanQi/MM-RLHF?style=social) <br> [**MM-RLHF: The Next Step Forward in Multimodal LLM Alignment**](https://arxiv.org/abs/2502.10391) <br> | arXiv | 2025-02 | [Github](https://github.com/Kwai-YuanQi/MM-RLHF) | [Page](https://mm-rlhf.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/meta-llama/llama-models?style=social) <br> [**Llama 3.1: An In-Depth Analysis of the Next Generation Large Language Model**](https://arxiv.org/abs/2407.21783) <br> | arXiv | 2024-07 | [Github](https://github.com/meta-llama/llama-models) | [Page](https://ai.meta.com/blog/meta-llama-3-1/) |
| ![Star](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF?style=social) <br> [**Aligning Large Multimodal Models with Factually Augmented RLHF**](https://arxiv.org/abs/2309.14525) <br> | arXiv | 2023-09 | [Github](https://github.com/llava-rlhf/LLaVA-RLHF) |  [Page](https://llava-rlhf.github.io/) | 
| ![Star](https://img.shields.io/github/stars/RLHF-V/RLHF-V?style=social) <br> [**RLHF-V: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback**](https://arxiv.org/abs/2309.14525) <br> | arXiv | 2023-09 | [Github](https://github.com/RLHF-V/RLHF-V) |  [Page](https://rlhf-v.github.io/) |
| ![Star](https://img.shields.io/github/stars/hendryx-scale/mhal-detect?style=social) <br> [**Detecting and Preventing Hallucinations in Large Vision Language Models**](https://arxiv.org/abs/2308.06394) <br> | arXiv | 2023-08 | [Github](https://github.com/hendryx-scale/mhal-detect) | - |
### Close-Source LLM/MLLM
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/PhoenixZ810/OmniAlign-V?style=social) <br> [**OmniAlign-V: Towards Enhanced Alignment of MLLMs with Human Preference**](https://arxiv.org/abs/2502.18411) <br> | arXiv | 2025-02 | [Github](https://github.com/PhoenixZ810/OmniAlign-V) | - |
| [**Mitigating Hallucination in Multimodal Large Language Model via Hallucination-targeted Direct Preference Optimization**](https://arxiv.org/abs/2411.10436) <br> | arXiv | 2024-11 | - | - |
|[**HomieBot: an Adaptive System for Embodied Mobile Manipulation in Open Environments**](https://openreview.net/forum?id=NQTrARs2pz&referrer=%5Bthe%20profile%20of%20Tianci%20Tang%5D(%2Fprofile%3Fid%3D~Tianci_Tang1)) <br> | openreview | 2024-10 | - | - |
|[**Enhancing Multimodal LLM for Detailed and Accurate Video Captioning using Multi-Round Preference Optimization**](https://arxiv.org/abs/2410.06682) <br> | arXiv | 2024-10 | - | [Page](https://video-salmonn-2.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/ByungKwanLee/Phantom?style=social) <br> [**Phantom of Latent for Large Language and Vision Models**](https://arxiv.org/abs/2409.14713) <br> | arXiv | 2024-09 | [Github](https://github.com/ByungKwanLee/Phantom) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/ZrrSkywalker/MAVIS?style=social) <br> [**MAVIS: Mathematical Visual Instruction Tuning with an Automatic Data Engine**](https://arxiv.org/abs/2407.08739) <br> | arXiv | 2024-07 | [Github](https://github.com/ZrrSkywalker/MAVIS) | [Page](https://mathverse-cuhk.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/ys-zong/VLGuard?style=social) <br> [**Safety Fine-Tuning at (Almost) No Cost: A Baseline for Vision Large Language Models**](https://arxiv.org/abs/2402.02207) <br> | arXiv | 2024-02 | [Github](https://github.com/ys-zong/VLGuard) | [Page](https://ys-zong.github.io/VLGuard/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/vlf-silkie/VLFeedback?style=social) <br> [**Silkie: Preference Distillation for Large Visual Language Models**](https://arxiv.org/abs/2312.10665) <br> | arXiv | 2023-12 | [Github](https://github.com/vlf-silkie/VLFeedback) | [Page](https://vlf-silkie.github.io/) |
| ![Star](https://img.shields.io/github/stars/opendatalab/HA-DPO?style=social) <br> [**Beyond Hallucinations: Enhancing LVLMs through Hallucination-Aware Direct Preference Optimization**](https://arxiv.org/abs/2311.16839) <br> | arXiv | 2023-11 | [Github](https://github.com/opendatalab/HA-DPO) | [Page](https://opendatalab.github.io/HA-DPO/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/FuxiaoLiu/LRV-Instruction?style=social) <br> [**Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning**](https://arxiv.org/abs/2306.14565) <br> | arXiv | 2023-06 | [Github](https://github.com/FuxiaoLiu/LRV-Instruction) | [Page](https://fuxiaoliu.github.io/LRV/) |
### Open-Source LLM/MLLM
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-NeXT?style=social) <br> [**LLaVA-Critic: Learning to Evaluate Multimodal Models**](https://arxiv.org/abs/2410.02712) <br> | arXiv | 2024-10 | [Github](https://github.com/LLaVA-VL/LLaVA-NeXT) | [Page](https://llava-vl.github.io/blog/2024-10-03-llava-critic/) |
|[**InteractiveCOT: Aligning Dynamic Chain-of-Thought Planning for Embodied Decision-Making**](https://openreview.net/forum?id=Y4iaDU4yMi) <br> | openreview | 2024-10 | - | - |
|[**CLIP-DPO: Vision-Language Models as a Source of Preference for Fixing Hallucinations in LVLMs**](https://arxiv.org/abs/2408.10433) <br> | arXiv | 2024-08 | - | - |
## Self-Annotation
### Single Text Modality
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/APiaoG/SymDPO?style=social) <br> [**SymDPO: Boosting In-Context Learning of Large Multimodal Models with Symbol Demonstration Direct Preference Optimization**](https://arxiv.org/abs/2411.11909) <br> | arXiv | 2024-11 | [Github](https://github.com/APiaoG/SymDPO) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenGVLab/InternVL?style=social) <br> [**Enhancing the Reasoning Ability of Multimodal Large Language Models via Mixed Preference Optimization**](https://arxiv.org/abs/2411.10442) <br> | arXiv | 2024-11 | [Github](https://github.com/OpenGVLab/InternVL/tree/main) | [Page](https://internvl.github.io/blog/2024-12-20-InternVL-2.5-MPO/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Liuziyu77/MIA-DPO?style=social) <br> [**MIA-DPO: Multi-Image Augmented Direct Preference Optimization For Large Vision-Language Models**](https://arxiv.org/abs/2410.17637) <br> | arXiv | 2024-10 | [Github](https://github.com/Liuziyu77/MIA-DPO) | [Page](https://liuziyu77.github.io/MIA-DPO/) |
|[**SQuBa: Speech Mamba Language Model with Querying-Attention for Efficient Summarization**](https://openreview.net/forum?id=zOMa82W1HV) <br> | openreview | 2024-10 | - | - |
|[**Enhancing Visual-Language Modality Alignment in Large Vision Language Models via Self-Improvement**](https://arxiv.org/abs/2405.15973) <br> | arXiv | 2024-05 | - | - |
### Single Image Modality
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
|[**vVLM: Exploring Visual Reasoning in VLMs against Language Priors**](https://openreview.net/forum?id=lCqNxBGPp5) <br> | openreview | 2024-10 | - | - |
### Image-Text Mixed Modality
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
|[**AdPO: Enhancing the Adversarial Robustness of Large Vision-Language Models with Preference Optimization**](https://openreview.net/forum?id=nbngu7H3ko) <br> | openreview | 2024-10 | - | - |
# Evaluation Benchmark
## General Knowledge
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/yfzhang114/MME-RealWorld) <br> [**MME-RealWorld: Could Your Multimodal LLM Challenge High-Resolution Real-World Scenarios that are Difficult for Humans?**](https://arxiv.org/abs/2408.13257) <br> | arXiv | 2024-08 | [Github](https://github.com/yfzhang114/MME-RealWorld) | [Page](https://mme-realworld.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/MMStar-Benchmark/MMStar) <br> [**Are We on the Right Way for Evaluating Large Vision-Language Models?**](https://arxiv.org/abs/2403.20330) <br> | NeurIPS | 2024-03 | [Github](https://github.com/MMStar-Benchmark/MMStar) | [Page](https://mmstar-benchmark.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/open-compass/VLMEvalKit) <br> [**MMBench: Is Your Multi-modal Model an All-around Player?**](https://arxiv.org/abs/2307.06281) <br> | NeurIPS | 2023-07 | [Github](https://github.com/open-compass/VLMEvalKit) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenGVLab/MMT-Bench?style=social) <br> [**MMT-Bench: A Comprehensive Multimodal Benchmark for Evaluating Large Vision-Language Models Towards Multitask AGI**](https://arxiv.org/abs/2404.16006) <br> | arXiv | 2024-04 | [Github](https://github.com/OpenGVLab/MMT-Bench) | [Page](https://mmt-bench.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/zeyofu/BLINK_Benchmark) <br> [**BLINK: Multimodal Large Language Models Can See but Not Perceive**](https://arxiv.org/abs/2404.12390) <br> | ECCV | 2024-04 | [Github](https://github.com/zeyofu/BLINK_Benchmark) | [Page](https://zeyofu.github.io/blink/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/lupantech/MathVista) <br> [**MathVista: Evaluating Mathematical Reasoning of Foundation Models in Visual Contexts**](https://arxiv.org/abs/2310.02255) <br> | ICLR | 2023-10 | [Github](https://github.com/lupantech/MathVista) | [Page](https://mathvista.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/SilongYong/SQA3D) <br> [**SQA3D: Situated Question Answering in 3D Scenes**](https://openreview.net/forum?id=example) <br> | ICLR | 2022-10 | [Github](https://github.com/SilongYong/SQA3D) | [Page](https://sqa3d.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/MMMU-Benchmark/MMMU) <br> [**MMMU: A Massive Multi-Discipline Multimodal Understanding and Reasoning Benchmark for Expert AGI**](https://arxiv.org/abs/2311.16502) <br> | CVPR | 2024-11 | [Github](https://github.com/MMMU-Benchmark/MMMU) | [Page](https://mmmu-benchmark.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenGVLab/Ask-Anything) <br> [**MVBench: A Comprehensive Multi-Modal Video Understanding Benchmark**](https://openaccess.thecvf.com/content/CVPR2024/papers/example) <br> | CVPR | 2023-11 | [Github](https://github.com/OpenGVLab/Ask-Anything) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/TIGER-AI-Lab/Mantis?style=social) <br> [**MANTIS: Interleaved Multi-Image Instruction Tuning**](https://arxiv.org/abs/2405.01483) <br> | arXiv | 2024-05 | [Github](https://github.com/TIGER-AI-Lab/Mantis/) | [Page](https://tiger-ai-lab.github.io/Mantis/) |
## Hallucination
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/LisaAnne/Hallucination?style=social) <br> [**Object Hallucination in Image Captioning**](https://arxiv.org/abs/1809.02156) <br> | arXiv | 2018-09 | [Github](https://github.com/LisaAnne/Hallucination) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/patrick-tssn/VideoHallucer) <br> [**VideoHallucer: Evaluating Intrinsic and Extrinsic Hallucinations in Large Video-Language Models**](https://arxiv.org/abs/2406.16338) <br> | arXiv | 2024-06 | [Github](https://github.com/patrick-tssn/VideoHallucer) | [Page](https://videohallucer.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/haoyiq114/VALOR) <br> [**VALOR-Eval: Holistic Coverage and Faithfulness Evaluation of Large Vision-Language Models**](https://arxiv.org/abs/2404.13874) <br> | ACL Findings | 2024-04 | [Github](https://github.com/haoyiq114/VALOR) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/RUCAIBox/POPE) <br> [**Evaluating Object Hallucination in Large Vision-Language Models**](https://aclanthology.org/D23-1073/) <br> | EMNLP | 2023-05 | [Github](https://github.com/RUCAIBox/POPE) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/junyangwang0410/HaELM?style=social) <br> [**Evaluation and Analysis of Hallucination in Large Vision-Language Models**](https://arxiv.org/abs/2308.15126) <br> | arXiv | 2023-08 | [Github](https://github.com/junyangwang0410/HaELM) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/assafbk/mocha_code) <br> [**MOCHA: Multi-Objective Reinforcement Mitigating Caption Hallucinations**](https://arxiv.org/abs/2312.03631) <br> | arXiv | 2023-12 | [Github](https://github.com/assafbk/mocha_code) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/FuxiaoLiu/LRV-Instruction) <br> [**Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning**](https://openreview.net/forum?id=example) <br> | ICLR | 2023-06 | [Github](https://github.com/FuxiaoLiu/LRV-Instruction) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/junyangwang0410/AMBER) <br> [**An LLM-Free Multi-Dimensional Benchmark for MLLMs Hallucination Evaluation**](https://arxiv.org/abs/2311.07397) <br> | arXiv | 2023-11 | [Github](https://github.com/junyangwang0410/AMBER) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/umd-huang-lab/Mementos) <br> [**Mementos: A Comprehensive Benchmark for Multimodal Large Language Model Reasoning over Image Sequences**](https://arxiv.org/abs/2401.10529) <br> | arXiv | 2024-01 | [Github](https://github.com/umd-huang-lab/Mementos) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF)<br> [**Aligning Large Multimodal Models with Factually Augmented RLHF**](https://arxiv.org/abs/2309.14525) <br> | arXiv | 2023-09-25 |  [Github](https://github.com/llava-rlhf/LLaVA-RLHF)  | [Page](https://llava-rlhf.github.io/) |
|  [**VLIND-Bench: Measuring Language Priors in Large Vision-Language Models**](https://arxiv.org/abs/2406.08702) | arXiv | 2024-06 | - | - |
| ![Star](https://img.shields.io/github/stars/hendryx-scale/mhal-detect?style=social) <br> [**Detecting and Preventing Hallucinations in Large Vision Language Models**](https://arxiv.org/abs/2308.06394) <br> | arXiv | 2023-08 | [Github](https://github.com/hendryx-scale/mhal-detect) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/tianyi-lab/HallusionBench?style=social) <br> [**HallusionBench: An Advanced Diagnostic Suite for Entangled Language Hallucination and Visual Illusion in Large Vision-Language Models**](https://arxiv.org/abs/2310.14566) <br> | arXiv | 2023-10 | [Github](https://github.com/tianyi-lab/HallusionBench) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/wenhuang2000/VHTest) <br> [**Visual Hallucinations of Multi-Modal Large Language Models**](https://arxiv.org/abs/2402.14683) <br> | arXiv | 2024-02 | [Github](https://github.com/wenhuang2000/VHTest) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/RLHF-V/RLAIF-V?style=social) <br> [**RLAIF-V: Open-Source AI Feedback Leads to Super GPT-4V Trustworthiness**](https://arxiv.org/abs/2405.17220) <br> | arXiv | 2024-05 | [Github](https://github.com/RLHF-V/RLAIF-V) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenKG-ORG/EasyDetect) <br> [**Unified Hallucination Detection for Multimodal Large Language Models**](https://arxiv.org/abs/2402.03190) <br> | ACL | 2024-02 | [Github](https://github.com/OpenKG-ORG/EasyDetect) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/jiazhen-code/IntrinsicHallu) <br> [**PHD: A Prompted Visual Hallucination Evaluation Dataset**](https://arxiv.org/abs/2403.11116) <br> | arXiv | 2024-05 | [Github](https://github.com/jiazhen-code/IntrinsicHallu) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/MILVLG/activitynet-qa) <br> [**ActivityNet-QA: A Dataset for Understanding Complex Web Videos via Question Answering**](https://arxiv.org/abs/1906.02467) <br> | AAAI | 2019-06 | [Github](https://github.com/MILVLG/activitynet-qa) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/mrwu-mac/R-Bench) <br> [**Evaluating and Analyzing Relationship Hallucinations in LVLMs**](https://arxiv.org/abs/2406.16449) <br> | ICML | 2024-06 | [Github](https://github.com/mrwu-mac/R-Bench) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/mraihan-gmu/mhumaneval-benchmark?style=social) <br> [**mHumanEval -- A Multilingual Benchmark to Evaluate Large Language Models for Code Generation**](https://arxiv.org/abs/2410.15037) <br> | arXiv | 2024-10 | [Github](https://github.com/mraihan-gmu/mhumaneval-benchmark) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/gzcch/Bingo) <br> [**Holistic Analysis of Hallucination in GPT-4V(ision): Bias and Interference Challenges**](https://arxiv.org/abs/2311.03287) <br> | arXiv | 2023-11 | [Github](https://github.com/gzcch/Bingo) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/HQHBench/HQHBench) <br> [**Evaluating the Quality of Hallucination Benchmarks for Large Vision-Language Models**](https://arxiv.org/abs/2406.17115) <br> | arXiv | 2024-06 | [Github](https://github.com/HQHBench/HQHBench) | - |
## Safety
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/Kwai-YuanQi/MM-RLHF?style=social) <br> [**MM-RLHF: The Next Step Forward in Multimodal LLM Alignment**](https://arxiv.org/abs/2502.10391) <br> | arXiv | 2025-02 | [Github](https://github.com/Kwai-YuanQi/MM-RLHF) | [Page](https://mm-rlhf.github.io/) |
| [**Efficiently Adversarial Examples Generation for Visual-Language Models under Targeted Transfer Scenarios Using Diffusion Models**](https://arxiv.org/abs/2404.10335) | arXiv | 2024-04 | - | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/kiaia/RedTeamVLM?style=social) <br> [**Red Teaming Visual Language Models**](https://arxiv.org/abs/2401.12915) <br> | arXiv | 2024-01 | [Github](https://github.com/kiaia/RedTeamVLM) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/ys-zong/VLGuard?style=social) <br> [**Safety Fine-Tuning at (Almost) No Cost: A Baseline for Vision Large Language Models**](https://arxiv.org/abs/2402.02207) <br> | arXiv | 2024-02 | [Github](https://github.com/ys-zong/VLGuard) | [Page](https://ys-zong.github.io/VLGuard/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/thu-ml/MMTrustEval) <br> [**MultiTrust: A Comprehensive Benchmark Towards Trustworthy Multimodal Large Language Models**](https://arxiv.org/abs/2406.07057) <br> | arXiv | 2024-06 | [Github](https://github.com/thu-ml/MMTrustEval) | [Page](https://multi-trust.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/UCSC-VLAA/vllm-safety-benchmark) <br> [**How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for Vision LLMs**](https://arxiv.org/abs/2311.16101) <br> | arXiv | 2023-11 | [Github](https://github.com/UCSC-VLAA/vllm-safety-benchmark) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/xirui-li/MOSSBench) <br> [**MossBench: Is Your Multimodal Language Model Oversensitive to Safe Queries?**](https://arxiv.org/abs/2406.17806) <br> | arXiv | 2024-06 | [Github](https://github.com/xirui-li/MOSSBench) | [Page](https://turningpoint-ai.github.io/MOSSBench/) |
## Conversation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/Q-Future/Q-Bench) <br> [**Q-Bench: A Benchmark for General-Purpose Foundation Models on Low-Level Vision**](https://arxiv.org/abs/2309.14181) <br> | ICLR | 2023-09 | [Github](https://github.com/Q-Future/Q-Bench) | [Page](https://q-future.github.io/Q-Bench/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/haotian-liu/LLaVA?style=social) <br> [**Improved Baselines with Visual Instruction Tuning**](https://arxiv.org/abs/2310.03744) <br> | arXiv | 2023-10 | [Github](https://github.com/haotian-liu/LLaVA) | [Page](https://llava-vl.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/LiveBench/LiveBench?style=social) <br> [**LiveBench: A Challenging, Contamination-Free LLM Benchmark**](https://arxiv.org/abs/2406.19314) <br> | arXiv | 2024-06 | [Github](https://github.com/LiveBench/LiveBench) | [Page](https://livebench.ai/#/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/reka-ai/reka-vibe-eval?style=social) <br> [**Vibe-Eval: A hard evaluation suite for measuring progress of multimodal language models**](https://arxiv.org/abs/2405.02287) <br> | arXiv | 2024-05 | [Github](https://github.com/reka-ai/reka-vibe-eval) | [Page](https://www.reka.ai/news/vibe-eval) |
## Reward Model
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/Kwai-YuanQi/MM-RLHF?style=social) <br> [**MM-RLHF: The Next Step Forward in Multimodal LLM Alignment**](https://arxiv.org/abs/2502.10391) <br> | arXiv | 2025-02 | [Github](https://github.com/Kwai-YuanQi/MM-RLHF) | [Page](https://mm-rlhf.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/for-ai/m-rewardbench?style=social) <br> [**M-RewardBench: Evaluating Reward Models in Multilingual Settings**](https://arxiv.org/abs/2410.15522) <br> | arXiv | 2024-10 | [Github](https://github.com/for-ai/m-rewardbench) | [Page](https://m-rewardbench.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/vl-rewardbench/VL-RewardBench?style=social) <br> [**VLRewardBench: A Challenging Benchmark for Vision-Language Generative Reward Models**](https://arxiv.org/abs/2411.17451) <br> | arXiv | 2024-11 | [Github](https://github.com/vl-rewardbench/VL-RewardBench) | [Page](https://vl-rewardbench.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/allenai/reward-bench?style=social) <br> [**RewardBench: Evaluating Reward Models for Language Modeling**](https://arxiv.org/abs/2403.13787) <br> | arXiv | 2024-03 | [Github](https://github.com/allenai/reward-bench) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/MJ-Bench/MJ-Bench?style=social) <br> [**MJ-Bench: Is Your Multimodal Reward Model Really a Good Judge for Text-to-Image Generation?**](https://arxiv.org/abs/2407.04842) <br> | arXiv | 2024-07 | [Github](https://github.com/MJ-Bench/MJ-Bench) | [Page](https://mj-bench.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Dongping-Chen/MLLM-Judge?style=social) <br> [**MLLM-as-a-Judge: Assessing Multimodal LLM-as-a-Judge with Vision-Language Benchmark**](https://arxiv.org/abs/2402.04788) <br> | arXiv | 2024-02 | [Github](https://github.com/Dongping-Chen/MLLM-Judge) | [Page](https://mllm-judge.github.io/) |
### Alignment
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/PhoenixZ810/OmniAlign-V?style=social) <br> [**OmniAlign-V: Towards Enhanced Alignment of MLLMs with Human Preference**](https://arxiv.org/abs/2502.18411) <br> | arXiv | 2025-02 | [Github](https://github.com/PhoenixZ810/OmniAlign-V) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/lmarena/arena-hard-auto?style=social) <br> [**From Crowdsourced Data to High-Quality Benchmarks: Arena-Hard and BenchBuilder Pipeline**](https://arxiv.org/abs/2406.11939) <br> | arXiv | 2024-06 | [Github](https://github.com/lmarena/arena-hard-auto) | [Page](https://lmsys.org/blog/2024-05-17-category-hard/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/tatsu-lab/alpaca_eval?style=social) <br> [**Length-Controlled AlpacaEval: A Simple Way to Debias Automatic Evaluators**](https://arxiv.org/abs/2404.04475) <br> | arXiv | 2024-04 | [Github](https://github.com/tatsu-lab/alpaca_eval) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/AlignBench?style=social) <br> [**AlignBench: Benchmarking Chinese Alignment of Large Language Models**](https://arxiv.org/abs/2311.18743) <br> | arXiv | 2023-11 | [Github](https://github.com/THUDM/AlignBench) | - |
