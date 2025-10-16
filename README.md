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
        - [Cascade Encoding Strategy](#Cascade-Encoding-Strategy)
        - [Dual-Branch Hybrid Encoding](#Dual-Branch-Hybrid-Encoding)
- [Decoding](#Decoding)
    - [Continuous Representation](#Continuous-Representation-1)
        - [External Generation](#External-Generation)
        - [Internal Generation](#Internal-Generation)
    - [Discrete Representation](#Discrete-Representation-1)
    - [Hybrid Representation](#Hybrid-Representation-1)
- [Training Dataset](#Training-Dataset)
- [Benchmark](#Benchmark)

# Modeling
## External Expert Integration Modeling
## Modular Joint Modeling
### Prompt-Mediated
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
### Representation-Mediated
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
## End-to-End Unified Modeling
### Autoregressive
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
### Diffusion
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
### Hybrid
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
# Encoding
## Continuous Representation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
## Discrete Representation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
## Hybrid Representation
### Cascade Encoding Strategy
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
### Dual-Branch Hybrid Encoding
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
# Decoding
## Continuous Representation
### External Generation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
### Internal Generation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
## Discrete Representation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
## Hybrid Representation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
# Training Dataset
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|

# Benchmark
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
