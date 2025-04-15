# MME-Survey: A Comprehensive Survey on Evaluation of Multimodal LLMs
 
---

<font size=5><center><b> Table of Contents </b> </center></font>
- [Foundational Capability](#foundational-capability)
  - [Comprehensive Evaluation](#comprehensive-evaluation)
  - [OCR](#ocr)
  - [Chart and Documentation](#chart-and-documentation)
  - [Mathematical](#mathematical)
  - [Multidisciplinary](#multidisciplinary)
  - [Multilingual](#multilingual)
  - [Instruction Following](#instruction-following)
  - [Multi-Round QA](#multi-round-qa)
  - [Multi-Image](#multi-image)
  - [Interleaved Data](#interleaved-data)
  - [High Resolution](#high-resolution)
  - [Visual Grounding](#visual-grounding)
  - [Fine-Grained Perception](#fine-grained-perception)
  - [Video Understanding](#video-understanding)
- [Model Self-Analysis](#model-self-analysis)
  - [Hallucination](#hallucination)
  - [Bias](#bias)
  - [Safety](#safety)
  - [Causation](#causation)
- [Extended Applications](#extended-applications)
  - [Medical Image](#medical-image)
  - [Sentiment Analysis](#sentiment-analysis)
  - [Remote Sensing](#remote-sensing)
  - [Agent](#agent)
  - [Code Generation](#code-generation)
  - [GUI](#gui)
  - [Transfer Capability](#transfer-capability)
  - [Knowledge Editing](#knowledge-editing)
  - [Embodied AI](#embodied-ai)
  - [Autonomous Driving](#autonomous-driving)
---

## Foundational Capability

### Comprehensive Evaluation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/MME-Benchmarks/MME-Unify) <br> [**MME-Unify: A Comprehensive Benchmark for Unified Multimodal Understanding and Generation Models**](https://arxiv.org/abs/2502.10391) <br> | arXiv | 2025-02-14 | [Github](https://github.com/MME-Benchmarks/MME-Unify) | [Page](https://mme-unify.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/yfzhang114/MME-RealWorld) <br> [**MME-RealWorld: Could Your Multimodal LLM Challenge High-Resolution Real-World Scenarios that are Difficult for Humans?**](https://arxiv.org/abs/2408.13257) <br> | arXiv | 2024-8-23 | [Github](https://github.com/yfzhang114/MME-RealWorld) | [Page](https://mme-realworld.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/WildVision-AI/WildVision-Bench) <br> [**WildVision: Evaluating Vision-Language Models in the Wild with Human Preferences**](https://arxiv.org/abs/2406.11069) <br> | arXiv | 2024-6-16 | [Github](https://github.com/WildVision-AI/WildVision-Bench) | [Page](https://huggingface.co/spaces/WildVision/vision-arena) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/MMStar-Benchmark/MMStar) <br> [**Are We on the Right Way for Evaluating Large Vision-Language Models?**](https://arxiv.org/abs/2403.20330) <br> | NeurIPS | 2024-03-29 | [Github](https://github.com/MMStar-Benchmark/MMStar) | [Page](https://mmstar-benchmark.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/zeyofu/BLINK_Benchmark) <br> [**BLINK: Multimodal Large Language Models Can See but Not Perceive**](https://arxiv.org/abs/2404.12390) <br> | ECCV | 2024-04-18 | [Github](https://github.com/zeyofu/BLINK_Benchmark) | [Page](https://zeyofu.github.io/blink/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenGVLab/MMT-Bench) <br> [**MMT-Bench: A Comprehensive Multimodal Benchmark for Evaluating Large Vision-Language Models Towards Multitask AGI**](https://arxiv.org/abs/2404.16006) <br> | ICML | 2024-04-24 | [Github](https://github.com/OpenGVLab/MMT-Bench) | [Page](https://mmt-bench.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/AILab-CVC/SEED-Bench) <br> [**SEED-Bench-2: Benchmarking Multimodal Large Language Models**](https://arxiv.org/abs/2311.17092) <br> | NeurIPS | 2023-11-28 | [Github](https://github.com/AILab-CVC/SEED-Bench) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/InfiMM/InfiMM-Eval-Tool) <br> [**InfiMM-Eval: Complex Open-Ended Reasoning Evaluation For Multi-Modal Large Language Models**](https://arxiv.org/abs/2311.11567) <br> | arXiv | 2023-11-20 | [Github](https://github.com/WildVision-AI/WildVision-Bench) | [Page](https://infimm.github.io/InfiMM-Eval/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OFA-Sys/TouchStone) <br> [**TouchStone: Evaluating Vision-Language Models by Language Models**](https://arxiv.org/abs/2308.16890) <br> | arXiv | 2023-08-31 | [Github](https://github.com/OFA-Sys/TouchStone) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/mlfoundations/VisIT-Bench) <br> [**VisIT-Bench: A Benchmark for Vision-Language Instruction Following Inspired by Real-World Use**](https://arxiv.org/abs/2308.06595) <br> | NeurIPS | 2023-08-12 | [Github](https://github.com/mlfoundations/VisIT-Bench/) | [Page](https://visit-bench.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/yuweihao/MM-Vet) <br> [**MM-Vet: Evaluating Large Multimodal Models for Integrated Capabilities**](https://arxiv.org/abs/2308.02490) <br> | ICML | 2023-08-04 | [Github](https://github.com/yuweihao/MM-Vet) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/AILab-CVC/SEED-Bench) <br> [**SEED-Bench: Benchmarking Multimodal LLMs with Generative Comprehension**](https://arxiv.org/abs/2307.16125) <br> | NeurIPS | 2023-07-30 | [Github](https://github.com/AILab-CVC/SEED-Bench) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/open-compass/VLMEvalKit) <br> [**MMBench: Is Your Multi-modal Model an All-around Player?**](https://arxiv.org/abs/2307.06281) <br> | NeurIPS | 2023-07-12 | [Github](https://github.com/open-compass/VLMEvalKit) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/BradyFU/Awesome-Multimodal-Large-Language-Models) <br> [**MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models**](https://arxiv.org/abs/2306.13394) <br> | arXiv | 2023-6-23 | [Github](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenGVLab/LAMM) <br> [**LAMM: Language-Assisted Multi-Modal Instruction-Tuning Dataset, Framework, and Benchmark**](https://arxiv.org/abs/2306.06687) <br> | NeurIPS | 2023-06-11 | [Github](https://github.com/OpenGVLab/LAMM) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenGVLab/Multi-Modality-Arena) <br> [**LVLM-eHub: A Comprehensive Evaluation Benchmark for Large Vision-Language Models**](https://arxiv.org/abs/2306.09265) <br> | arXiv | 2023-06-15 | [Github](https://github.com/OpenGVLab/Multi-Modality-Arena) | - |
| [**Making the V in VQA Matter: Elevating the Role of Image Understanding in Visual Question Answering**](https://arxiv.org/abs/1802.08218)| CVPR | 2018-2-22 | - | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/salesforce/LAVIS) <br> [**Making the V in VQA Matter: Elevating the Role of Image Understanding in Visual Question Answering**](https://arxiv.org/abs/1612.00837) <br> | arXiv | 2016-12-02 | [Github](https://github.com/salesforce/LAVIS) | [Page](https://visualqa.org/) |

### OCR
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/tianyu-z/VCR) <br> [**VCR: Visual Caption Restoration**](https://arxiv.org/abs/2406.06462) <br> | arXiv | 2024-06-10 | [Github](https://github.com/tianyu-z/VCR) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/AILab-CVC/SEED-Bench) <br> [**SEED-Bench-2: Benchmarking Multimodal Large Language Models**](https://arxiv.org/abs/2311.17092) <br> | NeurIPS | 2023-11-28 | [Github](https://github.com/AILab-CVC/SEED-Bench) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Yuliang-Liu/MultimodalOCR) <br> [**OCRBench: On the Hidden Mystery of OCR in Large Multimodal Models**](https://arxiv.org/abs/2305.07895) <br> | arXiv | 2023-5-13 | [Github](https://github.com/Yuliang-Liu/MultimodalOCR) | [Page](https://github.com/Yuliang-Liu/MultimodalOCR) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/X-LANCE/WebSRC) <br> [**WebSRC: A Dataset for Web-Based Structural Reading Comprehension**](https://arxiv.org/abs/2101.09465) <br> | CVPR | 2023-01-23 | [Github](https://github.com/X-LANCE/WebSRC) | [Page](https://x-lance.github.io/WebSRC/) |
| [**OCR-VQA: Visual Question Answering by Reading Text in Images**](https://arxiv.org/abs/1904.08920)| ICDAR | 2019-9-20 | - | [Page](https://ocr-vqa.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/TextVQA) <br> [**Towards VQA Models That Can Read**](https://arxiv.org/abs/1904.08920) <br> | CVPR | 2019-04-18 | [Github](https://github.com/facebookresearch/TextVQA) | [Page](https://textvqa.org/) |


### Chart and Documentation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/NimrodShabtay/LiveXiv) <br>[**LiveXiv -- A Multi-Modal Live Benchmark Based on Arxiv Papers Content**](https://arxiv.org/abs/2410.10783)<br> | arXiv | 2024-10-14 | [Github](https://github.com/NimrodShabtay/LiveXiv) | [Page](https://huggingface.co/datasets/LiveXiv/LiveXiv) |
| [**DocVQA: A Dataset for VQA on Document Images**](https://arxiv.org/abs/2007.00398) | WACV | 2020-07-01 | - | [Page](https://docvqa.org/) |
| [**InfographicVQA**](https://arxiv.org/abs/2104.12756) | WACV | 2021-04-26 | - | [Page](https://docvqa.org/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/mayubo2333/MMLongBench-Doc) <br>[**MMLongbench-Doc: Benchmarking Long-Context Document Understanding with Visualizations**](https://arxiv.org/abs/2407.01523)<br> | NeurIPS | 2024-07-01 | [Github](https://github.com/mayubo2333/MMLongBench-Doc) | [Page](https://mayubo2333.github.io/MMLongBench-Doc/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/princeton-nlp/CharXiv) <br>[**Charxiv: Charting Gaps in Realistic Chart Understanding in Multimodal LLMs**](https://arxiv.org/abs/2406.18521)<br> | NeurIPS | 2024-06-26 | [Github](https://github.com/princeton-nlp/CharXiv) | [Page](https://charxiv.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/UniModal4Reasoning/DocGenome) <br>[**DocGenome: An Open Large-Scale Scientific Document Benchmark for Training and Testing Multi-Modal Large Language Models**](https://arxiv.org/abs/2406.11633)<br> | arXiv | 2024-06-17 | [Github](https://github.com/UniModal4Reasoning/DocGenome) | [Page](https://unimodal4reasoning.github.io/DocGenome_page/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/allenai/dqa-net) <br>[**A Diagram is Worth a Dozen Images**](https://link.springer.com/chapter/10.1007/978-3-319-46448-0_16)<br> | ECCV | 2016-10-08 | [Github](https://github.com/allenai/dqa-net) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/zhaowc-ustc/tabpedia) <br>[**TabPedia: Towards Comprehensive Visual Table Understanding with Concept Synergy**](https://arxiv.org/abs/2406.01326)<br> | arXiv | 2024-06-03 | [Github](https://github.com/zhaowc-ustc/tabpedia) | [Page](https://huggingface.co/datasets/ByteDance/ComTQA) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/vis-nlp/ChartQA) <br>[**ChartQA: A Benchmark for Question Answering about Charts with Visual and Logical Reasoning**](https://arxiv.org/abs/2203.10244)<br> | arXiv | 2022-03-19 | [Github](https://github.com/vis-nlp/ChartQA) | [Page](https://huggingface.co/datasets/lmms-lab/ChartQA) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/nttmdlab-nlp/VisualMRC) <br>[**VisualMRC: Machine Reading Comprehension on Document Images**](https://ojs.aaai.org/index.php/AAAI/article/view/16468)<br> | AAAI | 2021-01-27 | [Github](https://github.com/nttmdlab-nlp/VisualMRC) | - |
| [**Leaf-QA: Locate, Encode, Attend for Figure Question Answering**](https://arxiv.org/abs/1907.12861) | WACV | 2019-7-30 | - | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/vmichals/FigureQA-baseline) <br>[**FigureQA: An Annotated Figure Dataset for Visual Reasoning**](https://arxiv.org/abs/1710.07300) <br>| ICLR | 2017-10-19 | [Github](https://github.com/vmichals/FigureQA-baseline) | - |

### Mathematical
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/AceCHQ/MMIQ) <br> [**MM-IQ: Benchmarking Human-Like Abstraction and Reasoning in Multimodal Models**](https://arxiv.org/abs/2502.00698) <br> | arXiv | 2025-02-02 | [Github](https://github.com/AceCHQ/MMIQ) | [Page](https://acechq.github.io/MMIQ-benchmark) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/We-Math/We-Math) <br> [**We-Math: Does Your Large Multimodal Model Achieve Human-like Mathematical Reasoning?**](https://arxiv.org/abs/2407.01284) <br> | arXiv | 2024-07-01 | [Github](https://github.com/We-Math/We-Math) | [Page](https://we-math.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/ZrrSkywalker/MathVerse) <br> [**MathVerse: Does Your Multimodal LLM Truly See the Diagrams in Visual Math Problems?**](https://arxiv.org/abs/2403.14624) <br> | ECCV | 2024-05-21 | [Github](https://github.com/ZrrSkywalker/MathVerse) | [Page](https://mathverse-cuhk.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/mathvision-cuhk/MathVision) <br> [**Measuring Multimodal Mathematical Reasoning with Math-Vision Dataset**](https://arxiv.org/abs/2402.14804) <br> | arXiv | 2024-02-22 | [Github](https://github.com/mathvision-cuhk/MathVision) | [Page](https://mathvision-cuhk.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenBMB/OlympiadBench) <br> [**OlympiadBench: A Challenging Benchmark for Promoting AGI with Olympiad-Level Bilingual Multimodal Scientific Problems**](https://arxiv.org/abs/2402.14008) <br> | ACL | 2024-02-21 | [Github](https://github.com/OpenBMB/OlympiadBench) | [Page](https://huggingface.co/datasets/Hothan/OlympiadBench) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/lupantech/MathVista) <br> [**MathVista: Evaluating Mathematical Reasoning of Foundation Models in Visual Contexts**](https://arxiv.org/abs/2310.02255) <br> | ICLR | 2023-10-03 | [Github](https://github.com/lupantech/MathVista) | [Page](https://mathvista.github.io/) |


### Multidisciplinary
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/open-compass/Creation-MMBench) <br> [**Creation-MMBench: Assessing Context-Aware Creative Intelligence in MLLM**](https://arxiv.org/pdf/2503.14478) <br> | arXiv | 2025-03-18 | [Github](https://github.com/open-compass/Creation-MMBench) | [Page](https://open-compass.github.io/Creation-MMBench/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/MMMU-Benchmark/MMMU) <br> [**MMMU: A Massive Multi-Discipline Multimodal Understanding and Reasoning Benchmark for Expert AGI**](https://arxiv.org/abs/2311.16502) <br> | CVPR | 2024-11-27 | [Github](https://github.com/MMMU-Benchmark/MMMU) | [Page](https://mmmu-benchmark.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/MMMU-Benchmark/MMMU) <br> [**MMMU-Pro: A More Robust Multi-Discipline Multimodal Understanding Benchmark**](https://arxiv.org/abs/2409.02813) <br> | arXiv | 2024-09-04 | [Github](https://github.com/MMMU-Benchmark/MMMU)  | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/flageval-baai/CMMU) <br> [**CMMU: A Benchmark for Chinese Multi-Modal Multi-Type Question Understanding and Reasoning**](https://arxiv.org/abs/2401.14011) <br> | arXiv | 2024-01-25 | [Github](https://github.com/flageval-baai/CMMU) | [Page](https://huggingface.co/datasets/BAAI/CMMU) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/CMMMU-Benchmark/CMMMU) <br> [**CMMMU: A Chinese Massive Multi-Discipline Multimodal Understanding Benchmark**](https://arxiv.org/abs/2401.11944) <br> | arXiv | 2024-01-22 | [Github](https://github.com/CMMMU-Benchmark/CMMMU) | [Page](https://cmmmu-benchmark.github.io/) |
|![GitHub Repo stars](https://img.shields.io/github/stars/lupantech/ScienceQA) <br> [**Learn to Explain: Multimodal Reasoning via Thought Chains for Science Question Answering**](https://arxiv.org/abs/2209.09513) <br> | NeurIPS | 2022-9-20 | [Github](https://github.com/lupantech/ScienceQA) | [Page](https://scienceqa.github.io/) |


### Multilingual
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/mbzuai-oryx/ALM-Bench) <br> [**All Languages Matter: Evaluating LMMs on Culturally Diverse 100 Languages**](https://arxiv.org/abs/2411.16508) <br> | arXiv | 2024-11-25 | [Github](https://github.com/mbzuai-oryx/ALM-Bench) | [Page](https://mbzuai-oryx.github.io/ALM-Bench/) |  
| ![GitHub Repo stars](https://img.shields.io/github/stars/flageval-baai/CMMU) <br> [**CMMU: A Benchmark for Chinese Multi-Modal Multi-Type Question Understanding and Reasoning**](https://arxiv.org/abs/2401.14011) <br> | arXiv | 2024-01-25 | [Github](https://github.com/flageval-baai/CMMU) | [Page](https://huggingface.co/datasets/BAAI/CMMU) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/CMMMU-Benchmark/CMMMU) <br> [**CMMMU: A Chinese Massive Multi-Discipline Multimodal Understanding Benchmark**](https://arxiv.org/abs/2401.11944) <br> | arXiv | 2024-01-22 | [Github](https://github.com/CMMMU-Benchmark/CMMMU) | [Page](https://cmmmu-benchmark.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/WangYuxuan93/CVLUE) <br> [**CVLUE: A New Benchmark Dataset for Chinese Vision-Language Understanding Evaluation**](https://arxiv.org/abs/2407.01081) <br> | arXiv | 2024-07-01 | [Github](https://github.com/WangYuxuan93/CVLUE) |- |
| ![GitHub Repo stars](https://img.shields.io/github/stars/wuyuhang05/AlignMMBench) <br> [**AlignMMBench: Evaluating Chinese Multimodal Alignment in Large Vision-Language Models**](https://arxiv.org/abs/2406.09295) <br> | arXiv | 2024-06-13 | [Github](https://github.com/wuyuhang05/AlignMMBench) | [Page](https://alignmmbench.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Hiba-MeiRuan/Urdu-VQA-Dataset-) <br> [**Dataset and Benchmark for Urdu Natural Scenes Text Detection, Recognition and Visual Question Answering**](https://arxiv.org/abs/2405.12533) <br> | arXiv | 2024-05-21 | [Github](https://github.com/Hiba-MeiRuan/Urdu-VQA-Dataset-) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/FadilaW/Swahili-STR-Dataset) <br> [**The First Swahili Language Scene Text Detection and Recognition Dataset**](https://arxiv.org/abs/2405.11437) <br> | ICDAR | 2024-05-19 | [Github](https://github.com/FadilaW/Swahili-STR-Dataset) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/bytedance/MTVQA) <br> [**MTVQA: Benchmarking Multilingual Text-Centric Visual Question Answering**](https://arxiv.org/abs/2405.11985) <br> | arXiv | 2024-05-20 | [Github](https://github.com/bytedance/MTVQA) | [Page](https://bytedance.github.io/MTVQA/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/qhnhynmm/ViOCRVQA-Dataset) <br> [**VIOCRVQA: Novel Benchmark Dataset and Vision Reader for Visual Question Answering by Understanding Vietnamese Text in Images**](https://arxiv.org/abs/2404.18397) <br> | arXiv | 2024-04-29 | [Github](https://github.com/qhnhynmm/ViOCRVQA-Dataset) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/DAMO-NLP-SG/M3Exam) <br> [**M3Exam: A Multilingual, Multimodal, Multilevel Benchmark for Examining Large Language Models**](https://arxiv.org/abs/2306.05179) <br> | NeurIPS | 2023-06-08 | [Github](https://github.com/DAMO-NLP-SG/M3Exam) | - |


### Instruction Following
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/apple/ml-mia-bench) <br> [**MIA-Bench: Towards Better Instruction Following Evaluation of Multimodal LLMs**](https://arxiv.org/abs/2407.01509) <br> | arXiv | 2024-07-01 | [Github](https://github.com/apple/ml-mia-bench) | - |

### Multi-Round QA
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/Liuziyu77/MMDU) <br> [**MMDU: A Multi-Turn Multi-Image Dialog Understanding Benchmark and Instruction-Tuning Dataset for LVLMs**](https://arxiv.org/abs/2406.11833) <br> | NeurIPS | 2024-06-17 | [Github](https://github.com/Liuziyu77/MMDU) | [Page](https://liuziyu77.github.io/MMDU/) |
|  [**ConvBench: A Multi-Turn Conversation Evaluation Benchmark with Hierarchical Capability for Large Vision-Language Models**](https://arxiv.org/abs/2403.20194) | arXiv | 2024-05-29 | - | - |

### Multi-Image
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenGVLab/MMIU) <br> [**MMIU: Multimodal Multi-image Understanding for Evaluating Large Vision-Language Models**](https://arxiv.org/abs/2408.02718) <br> | arXiv | 2024-08-05 | [Github](https://github.com/OpenGVLab/MMIU) | [Page](https://mmiu-bench.github.io) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Liuziyu77/MMDU) <br> [**MMDU: A Multi-Turn Multi-Image Dialog Understanding Benchmark and Instruction-Tuning Dataset for LVLMs**](https://arxiv.org/abs/2406.11833) <br> | NeurIPS | 2024-06-17 | [Github](https://github.com/Liuziyu77/MMDU) | [Page](https://liuziyu77.github.io/MMDU/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/lil-lab/nlvr) <br> [**A Corpus for Reasoning about Natural Language Grounded in Photographs**](https://arxiv.org/abs/1811.00491) <br> | ACL | 2018-11-01 | [Github](https://github.com/lil-lab/nlvr) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/HYPJUDY/Sparkles) <br> [**Sparkles: Unlocking Chats Across Multiple Images for Multi-Modal Instruction-Following Models**](https://arxiv.org/abs/2308.16463) <br> | arXiv | 2023-08-23 | [Github](https://github.com/HYPJUDY/Sparkles) | [Page](https://www.youtube.com/watch?v=GyBUqfHbp2w) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/umd-huang-lab/Mementos) <br> [**Mementos: A Comprehensive Benchmark for Multimodal Large Language Model Reasoning over Image Sequences**](https://arxiv.org/abs/2401.10529) <br> | arXiv | 2024-01-19 | [Github](https://github.com/umd-huang-lab/Mementos) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/ys-zong/MIRB) <br> [**Benchmarking Multi-Image Understanding in Vision and Language Models: Perception, Knowledge, Reasoning, and Multi-Hop Reasoning**](https://arxiv.org/abs/2406.12742) <br> | arXiv | 2024-06-18 | [Github](https://github.com/ys-zong/MIRB) | [Page](https://huggingface.co/datasets/VLLMs/MIRB) |
|  [**REMI: A Dataset for Reasoning with Multiple Images**](https://arxiv.org/abs/2406.09175) | arXiv | 2024-06-13 | - | [Page](https://huggingface.co/datasets/mehrankazemi/ReMI) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/muirbench/MuirBench) <br> [**MUIRBench: A Comprehensive Benchmark for Robust Multi-Image Understanding**](https://arxiv.org/abs/2406.09411) <br> | arXiv | 2024-06-13 | [Github](https://github.com/muirbench/MuirBench) | [Page](https://muirbench.github.io/) |


### Interleaved Data
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/MMMU-Benchmark/MMMU) <br> [**MMMU: A Massive Multi-Discipline Multimodal Understanding and Reasoning Benchmark for Expert AGI**](https://arxiv.org/abs/2311.16502) <br> | CVPR | 2024-11-27 | [Github](https://github.com/MMMU-Benchmark/MMMU) | [Page](https://mmmu-benchmark.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/HYPJUDY/Sparkles) <br> [**Sparkles: Unlocking Chats Across Multiple Images for Multi-Modal Instruction-Following Models**](https://arxiv.org/abs/2308.16463) <br> | arXiv | 2023-08-23 | [Github](https://github.com/HYPJUDY/Sparkles) | [Page](https://www.youtube.com/watch?v=GyBUqfHbp2w) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/zhourax/VEGA) <br> [**Vega: Learning Interleaved Image-Text Comprehension in Vision-Language Large Models**](https://arxiv.org/abs/2406.10228) <br> | arXiv | 2024-06-14 | [Github](https://github.com/zhourax/VEGA) | [Page](https://zhourax.github.io/VEGA/) |

### High Resolution
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/yfzhang114/MME-RealWorld) <br> [**MME-RealWorld: Could Your Multimodal LLM Challenge High-Resolution Real-World Scenarios that are Difficult for Humans?**](https://arxiv.org/abs/2408.13257) <br> | arXiv | 2024-8-23 | [Github](https://github.com/yfzhang114/MME-RealWorld) | [Page](https://mme-realworld.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/penghao-wu/vstar) <br> [**V?: Guided Visual Search as a Core Mechanism in Multimodal LLMs**](https://arxiv.org/abs/2312.14135) <br> | CVPR | 2023-12-21 | [Github](https://github.com/penghao-wu/vstar) | [Page](https://vstar-seal.github.io/) |

### Visual Grounding
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**ReferItGame: Referring to Objects in Photographs of Natural Scenes**](https://aclanthology.org/D14-1073/)| EMNLP | 2014-10-25 | - | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/JierunChen/Ref-L4) <br> [**Revisiting Referring Expression Comprehension Evaluation in the Era of Large Multimodal Models**](https://arxiv.org/abs/2406.16866) <br> | arXiv | 2024-06-24 | [Github](https://github.com/JierunChen/Ref-L4) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/mjhucla/Google_Refexp_toolbox) <br> [**Generation and Comprehension of Unambiguous Object Descriptions**](https://openaccess.thecvf.com/content_cvpr_2016/html/Mao_Generation_and_Comprehension_CVPR_2016_paper.html) <br> | CVPR | 2016-06-26 | [Github](https://github.com/mjhucla/Google_Refexp_toolbox) | - |

### Fine-Grained Perception
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/Baiqi-Li/NaturalBench) <br> [**NaturalBench: Evaluating Vision-Language Models on Natural Adversarial Samples**](https://arxiv.org/pdf/2410.14669) <br> | NeurIPS | 2024-10-18 | [Github](https://github.com/Baiqi-Li/NaturalBench) | [Page](https://linzhiqiu.github.io/papers/naturalbench/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/gregor-ge/FOCI-Benchmark) <br> [**African or European Swallow? Benchmarking Large Vision-Language Models for Fine-Grained Object Classification**](https://arxiv.org/abs/2406.14496) <br> | arXiv | 2024-06-20 | [Github](https://github.com/gregor-ge/FOCI-Benchmark) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/tsb0601/MMVP) <br> [**Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs**](https://arxiv.org/abs/2401.06209) <br> | CVPR | 2024-06-11 | [Github](https://github.com/tsb0601/MMVP) | [Page](https://tsb0601.github.io/mmvp_blog/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Q-Future/Q-Bench) <br> [**Q-Bench: A Benchmark for General-Purpose Foundation Models on Low-Level Vision**](https://arxiv.org/abs/2309.14181) <br> | ICLR | 2023-09-25 | [Github](https://github.com/Q-Future/Q-Bench) | [Page](https://q-future.github.io/Q-Bench/) |

### Video Understanding
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/zhishuifeiqian/VCR-Bench) <br> [**VCR-Bench: A Comprehensive Evaluation Framework for Video Chain-of-Thought Reasoning**](https://arxiv.org/abs/2504.07956) <br> | arXiv | 2025-04-10 | [Github](https://github.com/zhishuifeiqian/VCR-Bench) | [Page](https://vlm-reasoning.github.io/VCR-Bench/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/MIRA-SJTU/STI-Bench) <br> [**STI-Bench: Are MLLMs Ready for Precise Spatial-Temporal World Understanding?**](https://arxiv.org/abs/2503.23765) <br> | arXiv | 2025-04-09 | [Github](https://github.com/MIRA-SJTU/STI-Bench) | [Page](https://mira-sjtu.github.io/STI-Bench.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/V-STaR-Bench/V-STaR) <br> [**V-STaR: Benchmarking Video-LLMs on Video Spatio-Temporal Reasoning**](https://arxiv.org/abs/2503.11495) <br> | arXiv | 2025-03-14 | [Github](https://github.com/V-STaR-Bench/V-STaR) | [Page](https://v-star-bench.github.io) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/PolyU-ChenLab/ETBench) <br> [**E.T. Bench: Towards Open-Ended Event-Level Video-Language Understanding**](https://arxiv.org/abs/2409.18111) <br> | NeurIPS | 2024-09-26 | [Github](https://github.com/PolyU-ChenLab/ETBench) | [Page](https://polyu-chenlab.github.io/etbench/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/BradyFU/Video-MME)<br> [**Video-MME: The First-Ever Comprehensive Evaluation Benchmark of Multi-Modal LLMs in Video Analysis**](https://arxiv.org/abs/2405.21075) <br> | arXiv | 2024-05-31 | [Github](https://github.com/BradyFU/Video-MME) | [Page](https://video-mme.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenGVLab/Ask-Anything) <br> [**MVBench: A Comprehensive Multi-Modal Video Understanding Benchmark**](https://openaccess.thecvf.com/content/CVPR2024/papers/example) <br> | CVPR | 2023-11-28 | [Github](https://github.com/OpenGVLab/Ask-Anything) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/JUNJIE99/MLVU) <br> [**MLVU: A Comprehensive Benchmark for Multi-Task Long Video Understanding**](https://arxiv.org/abs/2406.04264) <br> | arXiv | 2024-06-06 | [Github](https://github.com/JUNJIE99/MLVU) | [Page](https://huggingface.co/datasets/MLVU/MLVU_Test) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/THUDM/LVBench) <br> [**LVBench: An Extreme Long Video Understanding Benchmark**](https://arxiv.org/abs/2406.08035) <br> | arXiv | 2024-06-12 | [Github](https://github.com/THUDM/LVBench) | [Page](https://lvbench.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/open-compass/VLMEvalKit) <br> [**MMBench-Video: A Long-Form Multi-Shot Benchmark for Holistic Video Understanding**](https://arxiv.org/abs/2406.14515) <br> | arXiv | 2024-06-20 | [Github](https://github.com/open-compass/VLMEvalKit) | -|
| ![GitHub Repo stars](https://img.shields.io/github/stars/RUCAIBox/Event-Bench) <br> [**Towards Event-Oriented Long Video Understanding**](https://arxiv.org/abs/2406.14129) <br> | arXiv | 2024-06-20 | [Github](https://github.com/RUCAIBox/Event-Bench) | [Page](https://huggingface.co/datasets/RUCAIBox/Event-Bench) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/joez17/VideoNIAH) <br> [**Needle in a Video Haystack: A Scalable Synthetic Framework for Benchmarking Video MLLMs**](https://arxiv.org/abs/2406.09367) <br> | arXiv | 2024-06-13 | [Github](https://github.com/joez17/VideoNIAH) | [Page](https://videoniah.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/egoschema/EgoSchema) <br> [**EgoSchema: A Diagnostic Benchmark for Very Long-Form Video Language Understanding**](https://proceedings.neurips.cc/paper/2024/hash/example) <br> | NeurIPS | 2023-08-17 | [Github](https://github.com/egoschema/EgoSchema) | [Page](https://egoschema.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/llyx97/TempCompass) <br> [**TempCompass: Do Video LLMs Really Understand Videos?**](https://arxiv.org/abs/2403.00476) <br> | arXiv | 2024-05-01 | [Github](https://github.com/llyx97/TempCompass) | [Page](https://llyx97.github.io/tempcompass/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/xudejing/video-question-answering) <br> [**Video Question Answering via Gradually Refined Attention over Appearance and Motion**](https://dl.acm.org/doi/10.1145/3123266.3123427) <br> | ACM MM | 2017-10-23 | [Github](https://github.com/xudejing/video-question-answering) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/YunseokJANG/tgif-qa) <br> [**TGIF-QA: Toward Spatio-Temporal Reasoning in Visual Question Answering**](https://openaccess.thecvf.com/content_cvpr_2017/html/Jang_TGIF-QA_Toward_Spatio-Temporal_CVPR_2017_paper.html) <br> | CVPR | 2017-07-22 | [Github](https://github.com/YunseokJANG/tgif-qa) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/MILVLG/activitynet-qa) <br> [**ActivityNet-QA: A Dataset for Understanding Complex Web Videos via Question Answering**](https://arxiv.org/abs/1906.02467) <br> | AAAI | 2019-06-06 | [Github](https://github.com/MILVLG/activitynet-qa) | - |


## Model Self-Analysis

### Hallucination
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/HQHBench/HQHBench) <br> [**Evaluating the Quality of Hallucination Benchmarks for Large Vision-Language Models**](https://arxiv.org/abs/2406.17115) <br> | arXiv | 2024-06-24 | [Github](https://github.com/HQHBench/HQHBench) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/mrwu-mac/R-Bench) <br> [**Evaluating and Analyzing Relationship Hallucinations in LVLMs**](https://arxiv.org/abs/2406.16449) <br> | ICML | 2024-06-24 | [Github](https://github.com/mrwu-mac/R-Bench) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/patrick-tssn/VideoHallucer) <br> [**VideoHallucer: Evaluating Intrinsic and Extrinsic Hallucinations in Large Video-Language Models**](https://arxiv.org/abs/2406.16338) <br> | arXiv | 2024-06-24 | [Github](https://github.com/patrick-tssn/VideoHallucer) | [Page](https://videohallucer.github.io/) |
|  [**VLIND-Bench: Measuring Language Priors in Large Vision-Language Models**](https://arxiv.org/abs/2406.08702) | arXiv | 2024-06-13 | - | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/jiazhen-code/IntrinsicHallu) <br> [**PHD: A Prompted Visual Hallucination Evaluation Dataset**](https://arxiv.org/abs/2403.11116) <br> | arXiv | 2024-05-17 | [Github](https://github.com/jiazhen-code/IntrinsicHallu) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/haoyiq114/VALOR) <br> [**VALOR-Eval: Holistic Coverage and Faithfulness Evaluation of Large Vision-Language Models**](https://arxiv.org/abs/2404.13874) <br> | ACL Findings | 2024-04-22 | [Github](https://github.com/haoyiq114/VALOR) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/wenhuang2000/VHTest) <br> [**Visual Hallucinations of Multi-Modal Large Language Models**](https://arxiv.org/abs/2402.14683) <br> | arXiv | 2024-02-22 | [Github](https://github.com/wenhuang2000/VHTest) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenKG-ORG/EasyDetect) <br> [**Unified Hallucination Detection for Multimodal Large Language Models**](https://arxiv.org/abs/2402.03190) <br> | ACL | 2024-02-05 | [Github](https://github.com/OpenKG-ORG/EasyDetect) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/assafbk/mocha_code) <br> [**MOCHA: Multi-Objective Reinforcement Mitigating Caption Hallucinations**](https://arxiv.org/abs/2312.03631) <br> | arXiv | 2023-12-03 | [Github](https://github.com/assafbk/mocha_code) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/junyangwang0410/AMBER) <br> [**An LLM-Free Multi-Dimensional Benchmark for MLLMs Hallucination Evaluation**](https://arxiv.org/abs/2311.07397) <br> | arXiv | 2023-11-13 | [Github](https://github.com/junyangwang0410/AMBER) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/gzcch/Bingo) <br> [**Holistic Analysis of Hallucination in GPT-4V(ision): Bias and Interference Challenges**](https://arxiv.org/abs/2311.03287) <br> | arXiv | 2023-11-06 | [Github](https://github.com/gzcch/Bingo) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF)<br> [**Aligning Large Multimodal Models with Factually Augmented RLHF**](https://arxiv.org/abs/2309.14525) <br> | arXiv | 2023-09-25 |  [Github](https://github.com/llava-rlhf/LLaVA-RLHF)  | [Page](https://llava-rlhf.github.io/) |
|  [**Evaluation and Analysis of Hallucination in Large Vision-Language Models**](https://arxiv.org/abs/2308.15126) | EMNLP | 2023-08-29 | - | - |
| [**Detecting and Preventing Hallucinations in Large Vision-Language Models**](https://arxiv.org/abs/2308.06394) | AAAI | 2023-08-11 | - | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/FuxiaoLiu/LRV-Instruction) <br> [**Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning**](https://openreview.net/forum?id=example) <br> | ICLR | 2023-06-26 | [Github](https://github.com/FuxiaoLiu/LRV-Instruction) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/RUCAIBox/POPE) <br> [**Evaluating Object Hallucination in Large Vision-Language Models**](https://aclanthology.org/D23-1073/) <br> | EMNLP | 2023-05-17 | [Github](https://github.com/RUCAIBox/POPE) | - |


### Bias
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/Xiangkui-Cao/VLBiasBench) <br> [**VLBiasBench: A Comprehensive Benchmark for Evaluating Bias in Large Vision-Language Models**](https://arxiv.org/abs/2406.14194) <br> | arXiv | 2024-06-20 | [Github](https://github.com/Xiangkui-Cao/VLBiasBench) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/gzcch/Bingo) <br> [**Holistic Analysis of Hallucination in GPT-4V(ision): Bias and Interference Challenges**](https://arxiv.org/abs/2311.03287) <br> | arXiv | 2023-11-06 | [Github](https://github.com/gzcch/Bingo) | [Page]() |
| [**MM-SPUBench: Towards Better Understanding of Spurious Biases in Multimodal LLMs**](https://arxiv.org/abs/2406.17126)| arXiv | 2024-06-24 | - | [Page](https://huggingface.co/datasets/mmbench/MM-SpuBench) |

### Safety
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/xirui-li/MOSSBench) <br> [**MossBench: Is Your Multimodal Language Model Oversensitive to Safe Queries?**](https://arxiv.org/abs/2406.17806) <br> | arXiv | 2024-06-22 | [Github](https://github.com/xirui-li/MOSSBench) | [Page](https://turningpoint-ai.github.io/MOSSBench/) |
| [**Efficiently Adversarial Examples Generation for Visual-Language Models under Targeted Transfer Scenarios Using Diffusion Models**](https://arxiv.org/abs/2404.10335) | arXiv | 2024-04-16 | - | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/yunqing-me/AttackVLM) <br> [**On Evaluating Adversarial Robustness of Large Vision-Language Models**](https://proceedings.neurips.cc/paper/2024/hash/example) <br> | NeurIPS | 2024-05-26 | [Github](https://github.com/yunqing-me/AttackVLM) | [Page](https://yunqing-me.github.io/AttackVLM/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/thu-ml/MMTrustEval) <br> [**Benchmarking Trustworthiness of Multimodal Large Language Models: A Comprehensive Study**](https://arxiv.org/abs/2406.07057) <br> | arXiv | 2024-06-11 | [Github](https://github.com/thu-ml/MMTrustEval) | [Page](https://multi-trust.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/UCSC-VLAA/vllm-safety-benchmark) <br> [**How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for Vision LLMs**](https://arxiv.org/abs/2311.16101) <br> | arXiv | 2023-11-28 | [Github](https://github.com/UCSC-VLAA/vllm-safety-benchmark) | - |


### Causation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
|![GitHub Repo stars](https://img.shields.io/github/stars/OpenCausaLab/CELLO) <br> [**Cello: Causal Evaluation of Large Vision-Language Models**](https://arxiv.org/abs/2406.19131) <br> | arXiv | 2024-06-27 | [Github](https://github.com/OpenCausaLab/CELLO) | - |

## Extended Applications

### Medical Image
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/uni-medical/GMAI-MMBench)<br> [**GMAI-MMbench: A Comprehensive Multimodal Evaluation Benchmark Towards General Medical AI**](https://arxiv.org/abs/2408.03361) <br> | arXiv | 2024-08-06 | [Github](https://github.com/uni-medical/GMAI-MMBench) | [Page](https://huggingface.co/datasets/OpenGVLab/GMAI-MMBench) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenGVLab/Multi-Modality-Arena) <br> [**OmniMedVQA: A New Large-Scale Comprehensive Evaluation Benchmark for Medical LVLM**](https://openaccess.thecvf.com/content/CVPR2024/papers/example) <br> | CVPR | 2024-02-14 | [Github](https://github.com/OpenGVLab/Multi-Modality-Arena) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/xiaoman-zhang/PMC-VQA) <br> [**PMC-VQA: Visual Instruction Tuning for Medical Visual Question Answering**](https://arxiv.org/abs/2305.10415) <br> | arXiv | 2023-05-17 | [Github](https://github.com/xiaoman-zhang/PMC-VQA) | [Page](https://paperswithcode.com/paper/pmc-vqa-visual-instruction-tuning-for-medical) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/chaoyi-wu/RadFM) <br> [**Towards Generalist Foundation Model for Radiology by Leveraging Web-scale 2D&3D Medical Data**](https://arxiv.org/abs/2308.02463) <br> | arXiv | 2023-08-04 | [Github](https://github.com/chaoyi-wu/RadFM) | [Page](https://chaoyi-wu.github.io/RadFM/) |
| [**PathVQA: 30000+ Questions for Medical Visual Question Answering**](https://arxiv.org/abs/2003.10286)| arXiv | 2020-05-07 | - | - |
| [**SLAKE: A Semantically-Labeled Knowledge-Enhanced Dataset for Medical Visual Question Answering**](https://arxiv.org/abs/2102.09542) | ISBI | 2021-04-13 | - | [Page](https://www.med-vqa.com/slake/) |
| [**A Dataset of Clinically Generated Visual Questions and Answers about Radiology Images**](https://www.nature.com/articles/sdata2018162) | Scientific data | 2018-02-51 |- | - |


### Sentiment Analysis
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/yan9qu/EmoLLM) <br> [**EMoLLM: Multimodal Emotional Understanding Meets Large Language Models**](https://arxiv.org/abs/2406.16442) <br> | arXiv | 2024-06-24 | [Github](https://github.com/yan9qu/EmoLLM) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/lx709/VRSBench) <br> [**VRSBench: A Versatile Vision-Language Benchmark Dataset for Remote Sensing Image Understanding**](https://arxiv.org/abs/2406.12384) <br> | arXiv | 2024-06-18 | [Github](https://github.com/lx709/VRSBench) | - |

### Remote Sensing
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/yfzhang114/MME-RealWorld) <br> [**MME-RealWorld: Could Your Multimodal LLM Challenge High-Resolution Real-World Scenarios that are Difficult for Humans?**](https://arxiv.org/abs/2408.13257) <br> | arXiv | 2024-8-23 | [Github](https://github.com/yfzhang114/MME-RealWorld) | [Page](https://mme-realworld.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/JackYFL/EmoLA) <br> [**Facial Affective Behavior Analysis with Instruction Tuning**](https://arxiv.org/abs/2404.05052) <br> | arXiv | 2024-04-07 | [Github](https://github.com/JackYFL/EmoLA) | [Page](https://johnx69.github.io/FABA/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Lsan2401/RMSIN) <br> [**Rotated Multi-Scale Interaction Network for Referring Remote Sensing Image Segmentation**](https://openaccess.thecvf.com/content/CVPR2024/papers/example) <br> | CVPR | 2023-12-19 | [Github](https://github.com/Lsan2401/RMSIN) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/Lavender105/RSGPT) <br> [**RSGPT: A Remote Sensing Vision Language Model and Benchmark**](https://arxiv.org/abs/2307.15266) <br> | arXiv | 2023-07-28 | [Github](https://github.com/Lavender105/RSGPT) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/ZhanYang-nwpu/RSVG-pytorch) <br> [**RSVG: Exploring Data and Models for Visual Grounding on Remote Sensing Data**](https://arxiv.org/abs/2210.12634) <br> | IEEE TGRS | 2022-10-23 | [Github](https://github.com/ZhanYang-nwpu/RSVG-pytorch) | - |
| [**Visual Grounding in Remote Sensing Images**](https://dl.acm.org/doi/10.1145/3503161.3548316) | ACM MM | 2022-10-10 | - | [Page](https://sunyuxi.github.io/publication/GeoVG) |
|  [**Open-Ended Remote Sensing Visual Question Answering with Transformers**](https://www.tandfonline.com/doi/full/10.1080/01431161.2022.2145583) | Int. J. Remote Sens. | 2022-08-10 |- | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/spectralpublic/RSIVQA) <br> [**Mutual Attention Inception Network for Remote Sensing Visual Question Answering**](https://ieeexplore.ieee.org/document/9444570) <br> | IEEE TGRS | 2021-05-20 | [Github](https://github.com/spectralpublic/RSIVQA) | - |
|  [**RSVQA: Visual Question Answering for Remote Sensing Data**](https://ieeexplore.ieee.org/document/example) | IEEE TGRS | 2020-03-16 | - | [Page](https://rsvqa.sylvainlobry.com/) |

### Agent
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/X-PLUG/MobileAgent) <br> [**Mobile-Agent: Autonomous Multi-Modal Mobile Device Agent with Visual Perception**](https://arxiv.org/abs/2401.16158) <br> | arXiv | 2024-01-29 | [Github](https://github.com/X-PLUG/MobileAgent) |- |
| ![GitHub Repo stars](https://img.shields.io/github/stars/AILab-CVC/GPT4Tools) <br> [**GPT4Tools: Teaching Large Language Model to Use Tools via Self-Instruction**](https://proceedings.neurips.cc/paper/2024/hash/example) <br> | NeurIPS | 2023-05-30 | [Github](https://github.com/AILab-CVC/GPT4Tools) | [Page](https://gpt4tools.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/mnotgod96/AppAgent) <br> [**AppAgent: Multimodal Agents as Smartphone Users**](https://arxiv.org/abs/2312.13771) <br> | arXiv | 2023-12-21 | [Github](https://github.com/mnotgod96/AppAgent) | [Page](https://appagent-official.github.io/) |


### Code Generation
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/MBZUAI-LLM/web2code) <br> [**Web2Code: A Large-Scale Webpage-to-Code Dataset and Evaluation Framework for Multimodal LLMs**](https://arxiv.org/abs/2406.20098) <br> | arXiv | 2024-06-28 | [Github](https://github.com/MBZUAI-LLM/web2code) | [Page](https://mbzuai-llm.github.io/webpage2code/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/ChartMimic/ChartMimic) <br> [**ChartMimic: Evaluating LLM’s Cross-Modal Reasoning Capability via Chart-to-Code Generation**](https://arxiv.org/abs/2406.09961) <br> | arXiv | 2024-06-14 | [Github](https://github.com/ChartMimic/ChartMimic) | [Page](https://chartmimic.github.io/) |

### GUI
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/kyegomez/ScreenAI) <br> [**ScreenAI: A Vision-Language Model for UI and Infographics Understanding**](https://arxiv.org/abs/2402.04615) <br> | IJCAI | 2024-02-07 | [Github](https://github.com/kyegomez/ScreenAI) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/google-research-datasets/screen_qa) <br> [**ScreenQA: Large-Scale Question-Answer Pairs Over Mobile App Screenshots**](https://arxiv.org/abs/2209.08199) <br> | arXiv | 2022-09-16 | [Github](https://github.com/google-research-datasets/screen_qa) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/google-research-datasets/rico_semantics) <br> [**Towards Better Semantic Understanding of Mobile Interfaces**](https://arxiv.org/abs/2210.02663) <br> | arXiv | 2022-10-06 | [Github](https://github.com/google-research-datasets/rico_semantics) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/google-research/google-research) <br> [**Screen2Words: Automatic Mobile UI Summarization with Multimodal Learning**](https://dl.acm.org/doi/10.1145/3472749.3474798) <br> | UIST | 2021-08-07 | [Github](https://github.com/google-research/google-research/tree/master/screen2words) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/google-research-datasets/widget-caption) <br> [**Widget Captioning: Generating Natural Language Description for Mobile User Interface Elements**](https://arxiv.org/abs/2010.04295) <br> | arXiv | 2020-10-08 | [Github](https://github.com/google-research-datasets/widget-caption) | - |
| [**Resolving Referring Expressions in Images with Labeled Elements**](https://ieeexplore.ieee.org/document/example)| SLT | 2018-10-24 | - | - |

### Transfer Capability
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/sail-sg/MMCBench) <br> [**Benchmarking Large Multimodal Models Against Common Corruptions**](https://arxiv.org/abs/2401.11943) <br> | arXiv | 2024-01-22 | [Github](https://github.com/sail-sg/MMCBench) | - |
|![GitHub Repo stars](https://img.shields.io/github/stars/AIFEG/BenchLMM) <br> [**BenchLMM: Benchmarking Cross-Style Visual Capability of Large Multimodal Models**](https://arxiv.org/abs/2312.02896) <br> | ECCV | 2023-12-05 | [Github](https://github.com/AIFEG/BenchLMM) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/UCSC-VLAA/vllm-safety-benchmark) <br> [**How Many Unicorns Are in This Image? A Safety Evaluation Benchmark for Vision LLMs**](https://arxiv.org/abs/2311.16101) <br> | arXiv | 2023-11-27 | [Github](https://github.com/UCSC-VLAA/vllm-safety-benchmark) | - |


### Knowledge Editing
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/VLKEB/VLKEB) <br> [**VLKEB: A Large Vision-Language Model Knowledge Editing Benchmark**](https://arxiv.org/abs/2403.07350) <br> | NeurIPS | 2024-03-12 | [Github](https://github.com/VLKEB/VLKEB) | [Page]() |
| ![GitHub Repo stars](https://img.shields.io/github/stars/zjunlp/EasyEdit) <br> [**Can We Edit Multimodal Large Language Models?**](https://aclanthology.org/D23-1078/) <br> | EMNLP | 2023-10-12 | [Github](https://github.com/zjunlp/EasyEdit) | - |

### Embodied AI
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**RH20T-P: A Primitive-Level Robotic Dataset Towards Composable Generalization Agents**](https://arxiv.org/abs/2403.19622) | arXiv | 2024-03-28 | - | [Page](https://sites.google.com/view/rh20t-primitive/main) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenRobotLab/EmbodiedScan) <br> [**EmbodiedScan: A Holistic Multi-Modal 3D Perception Suite Towards Embodied AI**](https://arxiv.org/abs/2312.16170) <br> | CVPR | 2023-12-26 | [Github](https://github.com/OpenRobotLab/EmbodiedScan) | [Page](https://tai-wang.github.io/embodiedscan/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/SilongYong/SQA3D) <br> [**SQA3D: Situated Question Answering in 3D Scenes**](https://openreview.net/forum?id=example) <br> | ICLR | 2022-10-14 | [Github](https://github.com/SilongYong/SQA3D) | [Page](https://sqa3d.github.io/) |
| [**Episodic Memory Question Answering**](https://openaccess.thecvf.com/content/CVPR2022/papers/example) | CVPR | 2022-05-03 | - | [Page](https://samyak-268.github.io/emqa) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/facebookresearch/EmbodiedQA) <br> [**Embodied Question Answering**](https://arxiv.org/abs/1711.11543) <br> | CVPR | 2017-11-30 | [Github](https://github.com/facebookresearch/EmbodiedQA) | [Page](https://embodiedqa.org/) |
|  [**The EPIC-Kitchens Dataset: Collection, Challenges and Baselines**](https://arxiv.org/abs/2005.00343) | IEEE TPAMI | 2020-04-29 | - | [Page](https://epic-kitchens.github.io/) |
| [**EGO4D: Around the World in 3,000 Hours of Egocentric Video**](https://arxiv.org/abs/2110.07058) | CVPR | 2021-10-13 | - | [Page](https://ego4d-data.org/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/aburns4/MoTIF) <br> [**A Dataset for Interactive Vision-Language Navigation with Unknown Command Feasibility**](https://arxiv.org/abs/2202.02312) <br> | ECCV | 2022-02-04 | [Github](https://github.com/aburns4/MoTIF) | - |

### Autonomous Driving
|  Title  |   Venue  |   Date   |   Code   |   Page   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| ![GitHub Repo stars](https://img.shields.io/github/stars/yfzhang114/MME-RealWorld) <br> [**MME-RealWorld: Could Your Multimodal LLM Challenge High-Resolution Real-World Scenarios that are Difficult for Humans?**](https://arxiv.org/abs/2408.13257) <br> | arXiv | 2024-8-23 | [Github](https://github.com/yfzhang114/MME-RealWorld) | [Page](https://mme-realworld.github.io/) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/4DVLab/IDKB) <br> [**Can LVLMs Obtain a Driver’s License? A Benchmark Towards Reliable AGI for Autonomous Driving**](https://arxiv.org/abs/2409.02914) <br> | arXiv | 2024-09-02 | [Github](https://github.com/4DVLab/IDKB) | [Page](https://4dvlab.github.io/project_page/idkb.html) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/qiantianwen/NuScenes-QA) <br> [**NuScenes-QA: A Multi-Modal Visual Question Answering Benchmark for Autonomous Driving Scenario**](https://aaai.org/Conferences/AAAI24/) <br> | AAAI | 2023-05-24 | [Github](https://github.com/qiantianwen/NuScenes-QA) | - |
| [**Rank2Tell: A Multimodal Driving Dataset for Joint Importance Ranking and Reasoning**](https://arxiv.org/abs/2309.06597) | WACV | 2023-09-12 | - | [Page](https://usa.honda-ri.com/rank2tell) |
| ![GitHub Repo stars](https://img.shields.io/github/stars/fudan-zvg/Reason2Drive) <br> [**Reason2Drive: Towards Interpretable and Chain-Based Reasoning for Autonomous Driving**](https://arxiv.org/abs/2312.03661) <br> | ECCV Benchmark | 2023-12-21 | [Github](https://github.com/fudan-zvg/Reason2Drive) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/wayveai/LingoQA) <br> [**LingoQA: Video Question Answering for Autonomous Driving**](https://arxiv.org/abs/2312.14115) <br> | arXiv | 2023-12-15 | [Github](https://github.com/wayveai/LingoQA/) | - |
| ![GitHub Repo stars](https://img.shields.io/github/stars/OpenDriveLab/DriveLM) <br> [**DriveLM: Driving with Graph Visual Question Answering**](https://arxiv.org/abs/2312.14150) <br> | ECCV | 2023-12-21 | [Github](https://github.com/OpenDriveLab/DriveLM) | |
| ![GitHub Repo stars](https://img.shields.io/github/stars/wudongming97/Prompt4Driving) <br> [**Language Prompt for Autonomous Driving**](https://arxiv.org/abs/2309.04379) <br> | arXiv | 2023-09-08 | [Github](https://github.com/wudongming97/Prompt4Driving) | - |
| [**DRAMA: Joint Risk Localization and Captioning in Driving**](https://arxiv.org/abs/2209.10767) | WACV | 2022-09-22 | - | [Page](https://usa.honda-ri.com/drama) |
| [**Grounding Human-to-Vehicle Advice for Self-Driving Vehicles**](https://arxiv.org/abs/1911.06978) | CVPR | 2019-09-16 | - | [Page](https://usa.honda-ri.com/HAD) |
| [**Talk2Car: Taking Control of Your Self-Driving Car**](https://arxiv.org/abs/1909.10838) | arXiv | 2019-09-24 | - | [Page](https://macchina-ai.cs.kuleuven.be/) |
