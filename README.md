# MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models

<img src="./images/dataset.png" width="96%" height="96%">

> Multimodal Large Language Model (MLLM) relies on the powerful LLM to perform multimodal tasks, showing amazing emergent abilities in recent studies, such as writing poems based on an image. However, it is difficult for these case studies to fully reflect the performance of MLLM, lacking a comprehensive evaluation. In this paper, we fill in this blank, presenting the first MLLM Evaluation benchmark MME. It measures both perception and cognition abilities on a total of 14 subtasks. In order to avoid data leakage that may arise from direct use of public datasets for evaluation, the annotations of instruction-answer pairs are all manually designed. The concise instruction design allows us to fairly compare MLLMs, instead of struggling in prompt engineering. Besides, with such an instruction, we can also easily carry out quantitative statistics. A total of 24 advanced MLLMs are comprehensively evaluated on our MME, which not only suggests that existing MLLMs still have a large room for improvement, but also reveals the potential directions for the subsequent model optimization.




## Our MLLM works

🔥🔥🔥 **A Survey on Multimodal Large Language Models**  
**[Project Page](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)** | **[Paper](https://arxiv.org/pdf/2306.13549.pdf)**

A curated list of Multimodal Large Language Models (MLLMs), including datasets, multimodal instruction tuning, multimodal in-context learning, multimodal chain-of-thought, llm-aided visual reasoning, foundation models, and others. This list will be updated in real time. :sparkles:

Welcome to join our WeChat group of MLLM communication! 

Please add WeChat ID (xjtupanda) to join the group. :star2:

---

🔥🔥🔥 **MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models**  
**[Project Page [Leaderboards]](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation)** | **[Paper](https://arxiv.org/pdf/2306.13394.pdf)**

Leaderboards of **24** advanced MLLMs, including [**BLIP-2**](https://arxiv.org/pdf/2301.12597.pdf), [**InstructBLIP**](https://arxiv.org/pdf/2305.06500.pdf), [**LLaVA**](https://arxiv.org/pdf/2304.08485.pdf), [**MiniGPT-4**](https://arxiv.org/pdf/2304.10592.pdf), [**mPLUG-Owl**](https://arxiv.org/pdf/2304.14178.pdf), [**LLaMA-Adapter V2**](https://arxiv.org/pdf/2304.15010.pdf), [**ImageBind_LLM**](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main), [**Otter**](https://arxiv.org/pdf/2305.03726.pdf), [**VisualGLM-6B**](https://github.com/THUDM/VisualGLM-6B), [**Multimodal-GPT**](https://arxiv.org/pdf/2305.04790.pdf), [**PandaGPT**](https://arxiv.org/pdf/2305.16355.pdf), [**VPGTrans**](https://arxiv.org/pdf/2305.01278.pdf), [**LaVIN**](https://arxiv.org/pdf/2305.15023.pdf), [**Lynx**](https://arxiv.org/pdf/2307.02469.pdf), [**Octopus**](https://github.com/gray311/UnifiedMultimodalInstructionTuning), [**LRV-Instruction**](https://arxiv.org/pdf/2306.14565.pdf), [**Cheetor**](https://arxiv.org/pdf/2308.04152.pdf), [**MMICL**](https://github.com/HaozheZhao/MIC), [**GIT2**](https://arxiv.org/pdf/2205.14100.pdf), [**BLIVA**](https://arxiv.org/pdf/2308.09936.pdf), [**Skywork-MM**](https://github.com/will-singularity/Skywork-MM/tree/main), [**Qwen-VL-Chat**](https://arxiv.org/pdf/2308.12966.pdf), [**InternLM-XComposer-VL**](https://arxiv.org/pdf/2309.15112.pdf), and [**Lion**](https://github.com/mynameischaos/Lion).

If you want to add your model in our leaderboards, please feel free to email bradyfu24@gmail.com. We will update the leaderboards in time. :sparkles:

<details><summary>Download MME :star2::star2: </summary>


The benchmark dataset is collected by Xiamen University for academic research only. You can email guilinli@stu.xmu.edu.cn to obtain the dataset, according to the following requirement. 

**Requirement**: A real-name system is encouraged for better academic communication. Your email suffix needs to match your affiliation, such as xx@stu.xmu.edu.cn and Xiamen University. Otherwise, you need to explain why. Please include the information bellow when sending your application email.

```
Name: (tell us who you are.)
Affiliation: (the name/url of your university or company)
Job Title: (e.g., professor, PhD, and researcher)
Email: (your email address)
How to use: (only for non-commercial use)
```

</details>

---

🔥🔥🔥 **Woodpecker: Hallucination Correction for MLLMs** 🚀🚀🚀  

<p align="center">
    <img src="./images/woodpecker.png" width="70%" height="70%">
</p>

**[Source Code](https://github.com/BradyFU/Woodpecker)** | **[Online Demo [Paused due to insufficient GPUs]](https://42976740ac53ddbe7d.gradio.live)** | **[Paper [Coming Soon]](https://github.com/BradyFU/Woodpecker)**

This is the first work to correct hallucination in multimodal large language models. The code and online demo have been released, and the paper will be coming soon!

---

If you find our projects helpful to your research, please cite the following papers:

```
@article{yin2023survey,
  title={A Survey on Multimodal Large Language Models},
  author={Yin, Shukang and Fu, Chaoyou and Zhao, Sirui and Li, Ke and Sun, Xing and Xu, Tong and Chen, Enhong},
  journal={arXiv preprint arXiv:2306.13549},
  year={2023}
}

@article{fu2023mme,
  title={MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models},
  author={Fu, Chaoyou and Chen, Peixian and Shen, Yunhang and Qin, Yulei and Zhang, Mengdan and Lin, Xu and Qiu, Zhenyu and Lin, Wei and Yang, Jinrui and Zheng, Xiawu and Li, Ke and Sun, Xing and Ji, Rongrong},
  journal={arXiv preprint arXiv:2306.13394},
  year={2023}
}
```

---

# News 🚀
**[2023-10]** 

1. [10-13] Thanks to [**Yizhou Zhou**](https://github.com/scenarios), [**WeMM**](https://github.com/scenarios/WeMM) joins our leaderboards. 🔥🔥
2. [10-13] Thanks to [**Cui Junbo**](https://github.com/thunlp/Muffin), we add [**Muffin**](https://github.com/thunlp/Muffin) to our leaderboards. 🔥🔥
3. [10-13] Thanks to [**Jiaming Han**](https://scholar.google.com/citations?hl=en&user=vgcxKEcAAAAJ&view_op=list_works), the results of [**LLaMA-Adapter V2**](https://github.com/OpenGVLab/LLaMA-Adapter) have been updated. 🔥🔥
4. [10-04] Thanks to [**Haotian Liu**](https://hliu.cc/), the results of [**LLaVA**](https://github.com/haotian-liu/LLaVA) have been updated. 🔥🔥

**[2023-09]** 

1. [09-28] Thanks to [**Huasong Zhong**](https://github.com/mynameischaos), [**Lion**](https://github.com/mynameischaos/Lion) is added. 🔥🔥
2. [09-27] Thanks to [**Xiaoyi Dong**](https://github.com/LightDXY), [**InternLM-XComposer-VL**](https://github.com/InternLM/InternLM-XComposer) joins our leaderboards. 🔥🔥
3. [09-05] Thanks to [**Jinze Bai**](https://github.com/jinze1994), our leaderboards usher in [**Qwen-VL-Chat**](https://github.com/QwenLM/Qwen-VL). 🔥🔥
4. [09-01] Thanks to [**Skywork Multi-Modal Group**](https://github.com/will-singularity), [**Skywork-MM**](https://github.com/will-singularity/Skywork-MM/tree/main) takes part in our leaderboards. 🔥🔥

**[2023-08]** 

1. [08-28] Thanks to [**UCSD MLPC**](https://github.com/mlpc-ucsd), we welcome [**BLIVA**](https://github.com/mlpc-ucsd/BLIVA) to join our leaderboards. 
2. [08-28] Thanks to [**Jianfeng Wang**](https://scholar.google.com.hk/citations?user=vJWEw_8AAAAJ&hl=zh-CN&oi=sra), [**GIT2**](https://github.com/microsoft/GenerativeImage2Text) is added to our leaderboards. 
3. [08-28] Thanks to [**Yike Yuan**](https://github.com/yyk-wew) and [**Songyang Zhang**](https://github.com/tonysy), the results of [**MiniGPT4**](https://arxiv.org/pdf/2304.10592.pdf) have been revised. 
4. [08-21] Thanks to [**Haozhe Zhao**](https://github.com/HaozheZhao), [**MMICL**](https://github.com/HaozheZhao/MIC) joins our leaderboards (The results are renewed on 09-17 by upgrading the checkpoint.). 
5. [08-13] Thanks to [**Zhejiang University DCD Lab**](https://github.com/DCDmllm), our leaderboards incorporate a new member [**Cheetor**](https://github.com/DCDmllm/Cheetah). 
6. [08-08] Thanks to [**Fuxiao Liu**](https://github.com/FuxiaoLiu), we add [**LRV-Instruction**](https://github.com/FuxiaoLiu/LRV-Instruction) to our leaderboards. 

**[2023-07]** 

1. [07-28] Thanks to [**Yingzi Ma**](https://gray311.github.io/), his work [**Octopus**](https://github.com/gray311/UnifiedMultimodalInstructionTuning) has been updated to our leaderboards.
2. [07-15] Thanks to [**Jiani Zheng**](https://github.com/Garlicisnotmyfavor), our leaderboards welcome a new member [**Lynx**](https://github.com/bytedance/lynx-llm).
3. [07-12] Thanks to [**Ao Zhang**](https://github.com/waxnkw), his work [**VPGTrans**](https://github.com/VPGTrans/VPGTrans) has been added in our leaderboards.
4. [07-09] Thanks to [**Bo Li**](https://github.com/Luodian), we have updated the evaluation of his work [**Otter**](https://github.com/Luodian/Otter). It uses the latest model [**OTTER-Image-MPT7B**](https://huggingface.co/luodian/OTTER-Image-MPT7B) that incoporates OpenFlamingv2 and enhances instruction following ability.

**[2023-06]** 

1. [06-30] Thanks to [**Renrui Zhang**](https://github.com/ZrrSkywalker), we have updated the evaluation of his two works, i.e., [**LLaMA-Adapter V2**](https://github.com/OpenGVLab/LLaMA-Adapter) and [**ImageBind_LLM**](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM). The former is re-evaluated after changing the model [**weights**](https://github.com/OpenGVLab/LLaMA-Adapter/releases/download/v.2.0.0/7fa55208379faf2dd862565284101b0e4a2a72114d6490a95e432cf9d9b6c813_BIAS-7B.pth), and the latter is a newly added MLLM.
2. [06-30] Thanks to [**Gen Luo**](https://github.com/luogen1996), we have added the evaluation of his work [**LaVIN**](https://github.com/luogen1996/LaVIN).
3. [06-30] The results of other models have also been updated, retrieving the answer from the beginning of the generated responses instead of the whole responses. [**An automated evaluation script**](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/blob/Evaluation/tools/eval_tool.zip) for the calculation of scores has been released!

---

# Evaluation Results

The top 5 on the perception and cognition leaderboards:

<img src="./images/evaluation-1013.png" width="80%" height="80%">


# Evaluation Leaderboards

<img src="./images/xmind.png" width="96%" height="96%">

---

<font size=5><center><b> Table of Leaderboards </b> </center></font>

- [Perception](#perception)
  - [Existence](#existence) | [Count](#count) | [Position](#position) | [Color](#color) | [Poster](#poster) | [Celebrity](#celebrity) | [Scene](#scene) | [Landmark](#landmark) | [Artwork](#artwork) | [OCR](#ocr)
- [Cognition](#cognition)
  - [Commonsense Reasoning](#commonsense-reasoning) | [Numerical Calculation](#numerical-calculation) | [Text Translation](#text-translation) | [Code Reasoning](#code-reasoning)

---

## Perception

Sum of the scores of all perception subtasks, including existence, count, position, color, poster, celebrity, scene, landmark, artwork, and OCR. The full score of each subtask is 200, and that of all perception is 2000.

| Rank |                            Model                             |                           Version                            |    Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :---------: |
|  🏅️   |        **[WeMM](https://github.com/scenarios/WeMM)**         |     **[InternLM-7B](https://github.com/scenarios/WeMM)**     | **1551.63** |
|  🥈   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **1545.80** |
|  🥉   |      **[LLaVA](https://arxiv.org/pdf/2304.08485.pdf)**       |    **[Vicuna-13B](https://github.com/haotian-liu/LLaVA)**    | **1531.32** |
|  4   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   1528.45   |
|  5   |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   1487.58   |
|  6   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   1419.08   |
|  7   |          [MMICL](https://github.com/HaozheZhao/MIC)          |      [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)       |   1381.73   |
|  8   |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   1373.23   |
|  9   |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   1337.73   |
|  10  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   1332.05   |
|  11  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   1328.40   |
|  12  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   1299.96   |
|  13  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   1299.78   |
|  14  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   1293.84   |
|  15  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   1292.26   |
|  16  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   1281.02   |
|  17  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   1212.82   |
|  18  | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   1095.76   |
|  19  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   967.34    |
|  20  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   963.60    |
|  21  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     |   790.45    |
|  22  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   775.77    |
|  23  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   705.31    |
|  24  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   654.72    |
|  25  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) |   642.59    |
|  26  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) |   581.67    |

### Existence

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |      **[Otter](https://arxiv.org/pdf/2305.03726.pdf)**       |  **[OTTER-Image-MPT7B](https://github.com/Luodian/Otter)**   | **195.00** |
|  🏅️   |       **[Lynx](https://arxiv.org/pdf/2307.02469.pdf)**       |    **[Vicuna-7B](https://github.com/bytedance/lynx-llm)**    | **195.00** |
|  🏅️   |        **[WeMM](https://github.com/scenarios/WeMM)**         |     **[InternLM-7B](https://github.com/scenarios/WeMM)**     | **195.00** |
|  🏅️   |        **[Muffin](https://github.com/thunlp/Muffin)**        |      **[Vicuna-13B](https://github.com/thunlp/Muffin)**      | **195.00** |
|  🥈   |       **[GIT2](https://arxiv.org/pdf/2205.14100.pdf)**       | **[VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text)** | **190.00** |
|  🥈   | **[InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer)** | **[InternLM-7B](https://github.com/InternLM/InternLM-XComposer)** | **190.00** |
|  🥈   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **190.00** |
|  🥉   | **[LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)** | **[LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b)** | **185.00** |
|  🥉   |   **[InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)**   | **[Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip)** | **185.00** |
|  🥉   |      **[LLaVA](https://arxiv.org/pdf/2304.08485.pdf)**       |    **[Vicuna-13B](https://github.com/haotian-liu/LLaVA)**    | **185.00** |
|  🥉   |      **[LaVIN](https://arxiv.org/pdf/2305.15023.pdf)**       |     **[LAVIN-13B](https://github.com/luogen1996/LaVIN)**     | **185.00** |
|  4   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   180.00   |
|  4   |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   180.00   |
|  4   |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   180.00   |
|  4   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   180.00   |
|  5   |          [MMICL](https://github.com/HaozheZhao/MIC)          |      [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)       |   170.00   |
|  6   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   165.00   |
|  7   |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   160.00   |
|  8   |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   158.33   |
|  9   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   128.33   |
|  10  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   120.00   |
|  11  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   85.00    |
|  12  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) |   70.00    |
|  12  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     |   70.00    |
|  13  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) |   68.33    |
|  14  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   61.67    |

### Count

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |        **[Muffin](https://github.com/thunlp/Muffin)**        |      **[Vicuna-13B](https://github.com/thunlp/Muffin)**      | **163.33** |
|  🥈   |        **[MMICL](https://github.com/HaozheZhao/MIC)**        |    **[FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)**     | **160.00** |
|  🥉   | **[InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer)** | **[InternLM-7B](https://github.com/InternLM/InternLM-XComposer)** | **158.33** |
|  4   |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   155.00   |
|  4   |        [Lion](https://github.com/mynameischaos/Lion)         |     [InternLM-7B](https://github.com/mynameischaos/Lion)     |   155.00   |
|  5   |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   151.67   |
|  5   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   151.67   |
|  6   |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   150.00   |
|  7   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   143.33   |
|  8   |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   138.33   |
|  9   |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   135.00   |
|  10  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   133.33   |
|  11  |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   128.33   |
|  12  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   118.33   |
|  13  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   111.67   |
|  14  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   96.67    |
|  15  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   88.33    |
|  15  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   88.33    |
|  16  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     |   85.00    |
|  17  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   60.00    |
|  18  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) |   55.00    |
|  18  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   55.00    |
|  19  | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   53.33    |
|  20  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   50.00    |
|  20  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   50.00    |
|  20  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) |   50.00    |

### Position

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **153.33** |
|  🥈   |      **[LLaVA](https://arxiv.org/pdf/2304.08485.pdf)**       |    **[Vicuna-13B](https://github.com/haotian-liu/LLaVA)**    | **133.33** |
|  🥉   |    **[Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)**    |       **[Qwen-7B](https://github.com/QwenLM/Qwen-VL)**       | **128.33** |
|  4   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   126.67   |
|  5   |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   96.67    |
|  6   |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   90.00    |
|  7   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   86.67    |
|  7   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   86.67    |
|  8   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   85.80    |
|  9   |          [MMICL](https://github.com/HaozheZhao/MIC)          |      [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)       |   81.67    |
|  9   |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   81.67    |
|  10  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   80.00    |
|  11  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   73.33    |
|  12  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   66.67    |
|  12  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   66.67    |
|  13  | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   63.33    |
|  13  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   63.33    |
|  13  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     |   63.33    |
|  14  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   58.33    |
|  15  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   56.67    |
|  16  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   50.00    |
|  16  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) |   50.00    |
|  17  | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   48.33    |
|  17  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   48.33    |
|  18  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   46.67    |
|  19  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) |   43.33    |

### Color

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |      **[BLIVA](https://arxiv.org/pdf/2308.09936.pdf)**       |     **[FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)**      | **180.00** |
|  🏅️   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **180.00** |
|  🥈   |      **[LLaVA](https://arxiv.org/pdf/2304.08485.pdf)**       |    **[Vicuna-13B](https://github.com/haotian-liu/LLaVA)**    | **170.00** |
|  🥈   |       **[Lynx](https://arxiv.org/pdf/2307.02469.pdf)**       |    **[Vicuna-7B](https://github.com/bytedance/lynx-llm)**    | **170.00** |
|  🥈   |    **[Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)**    |       **[Qwen-7B](https://github.com/QwenLM/Qwen-VL)**       | **170.00** |
|  🥉   |        **[WeMM](https://github.com/scenarios/WeMM)**         |     **[InternLM-7B](https://github.com/scenarios/WeMM)**     | **168.33** |
|  4   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   165.00   |
|  4   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   165.00   |
|  4   |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   165.00   |
|  5   |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   158.33   |
|  6   |          [MMICL](https://github.com/HaozheZhao/MIC)          |      [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)       |   156.67   |
|  7   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   153.33   |
|  8   |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   148.33   |
|  9   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   145.00   |
|  10  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   118.33   |
|  11  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   116.67   |
|  12  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   113.33   |
|  13  | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   103.33   |
|  14  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) |   75.00    |
|  14  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   75.00    |
|  15  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   73.33    |
|  15  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     |   73.33    |
|  16  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   68.33    |
|  17  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   55.00    |
|  17  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   55.00    |
|  18  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) |   50.00    |

### Poster

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **181.63** |
|  🥈   |    **[Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)**    |       **[Qwen-7B](https://github.com/QwenLM/Qwen-VL)**       | **178.57** |
|  🥉   | **[Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main)** | **[Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main)** | **175.85** |
|  4   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   169.39   |
|  5   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   161.90   |
|  6   |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   160.54   |
|  7   |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   155.10   |
|  8   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   147.96   |
|  9   |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   147.28   |
|  10  |          [MMICL](https://github.com/HaozheZhao/MIC)          |      [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)       |   146.26   |
|  11  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   141.84   |
|  12  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   139.04   |
|  13  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   138.78   |
|  14  | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   138.10   |
|  15  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   137.76   |
|  16  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   136.05   |
|  17  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   124.83   |
|  18  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   123.81   |
|  19  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   112.59   |
|  20  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     |   84.01    |
|  21  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   79.59    |
|  22  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) |   76.53    |
|  23  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   65.99    |
|  24  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   64.97    |
|  25  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   57.82    |
|  26  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) |   41.84    |

### Celebrity

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |      **[Otter](https://arxiv.org/pdf/2305.03726.pdf)**       |  **[OTTER-Image-MPT7B](https://github.com/Luodian/Otter)**   | **172.65** |
|  🥈   |     **[Cheetor](https://arxiv.org/pdf/2308.04152.pdf)**      |     **[Vicuna-7B](https://github.com/DCDmllm/Cheetah)**      | **164.12** |
|  🥉   |        **[WeMM](https://github.com/scenarios/WeMM)**         |     **[InternLM-7B](https://github.com/scenarios/WeMM)**     | **163.82** |
|  4   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   160.29   |
|  5   |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   152.94   |
|  6   |        [Lion](https://github.com/mynameischaos/Lion)         |     [InternLM-7B](https://github.com/mynameischaos/Lion)     |   150.59   |
|  7   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   150.29   |
|  8   |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   145.88   |
|  9   |          [MMICL](https://github.com/HaozheZhao/MIC)          |      [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)       |   141.76   |
|  10  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   140.88   |
|  11  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   136.76   |
|  12  | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   129.41   |
|  13  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   120.59   |
|  14  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   118.24   |
|  15  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   112.65   |
|  16  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   105.59   |
|  17  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   101.18   |
|  18  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   100.29   |
|  19  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   81.76    |
|  20  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   76.47    |
|  21  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   73.82    |
|  22  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) |   57.06    |
|  23  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) |   54.41    |
|  24  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     |   53.53    |
|  25  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   53.24    |
|  26  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   47.35    |

### Scene

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |        **[WeMM](https://github.com/scenarios/WeMM)**         |     **[InternLM-7B](https://github.com/scenarios/WeMM)**     | **171.75** |
|  🥈   |       **[Lynx](https://arxiv.org/pdf/2307.02469.pdf)**       |    **[Vicuna-7B](https://github.com/bytedance/lynx-llm)**    | **164.50** |
|  🥉   |      **[LLaVA](https://arxiv.org/pdf/2304.08485.pdf)**       |    **[Vicuna-13B](https://github.com/haotian-liu/LLaVA)**    | **161.25** |
|  4   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   159.75   |
|  5   |        [Lion](https://github.com/mynameischaos/Lion)         |     [InternLM-7B](https://github.com/mynameischaos/Lion)     |   159.00   |
|  6   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   158.75   |
|  7   |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   158.50   |
|  8   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   157.25   |
|  9   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   156.25   |
|  10  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   156.00   |
|  11  |          [MMICL](https://github.com/HaozheZhao/MIC)          |      [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)       |   153.75   |
|  12  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   153.00   |
|  13  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   152.25   |
|  14  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   151.50   |
|  15  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   151.25   |
|  16  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   147.98   |
|  17  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   146.25   |
|  18  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   145.25   |
|  19  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     |   141.75   |
|  20  | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   138.89   |
|  21  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   136.75   |
|  22  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   135.50   |
|  23  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) |   118.00   |
|  24  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   113.25   |
|  25  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) |   71.75    |
|  26  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   68.00    |

### Landmark

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **173.00** |
|  🥈   |      **[LLaVA](https://arxiv.org/pdf/2304.08485.pdf)**       |    **[Vicuna-13B](https://github.com/haotian-liu/LLaVA)**    | **170.50** |
|  🥉   | **[LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)** | **[LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b)** | **167.84** |
|  4   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   165.25   |
|  5   |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   164.00   |
|  6   |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   162.00   |
|  7   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   160.53   |
|  8   |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   159.25   |
|  9   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   151.75   |
|  10  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   146.25   |
|  11  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   145.73   |
|  12  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   140.50   |
|  13  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   138.00   |
|  14  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   137.25   |
|  15  |          [MMICL](https://github.com/HaozheZhao/MIC)          |      [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)       |   136.13   |
|  16  | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   127.04   |
|  17  | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   126.00   |
|  18  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   93.50    |
|  19  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   89.50    |
|  20  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   83.75    |
|  21  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   79.75    |
|  22  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   69.75    |
|  22  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) |   69.75    |
|  23  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     |   64.75    |
|  24  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   62.00    |
|  25  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) |   54.00    |

### Artwork

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |        **[WeMM](https://github.com/scenarios/WeMM)**         |     **[InternLM-7B](https://github.com/scenarios/WeMM)**     | **155.75** |
|  🥈   |       **[GIT2](https://arxiv.org/pdf/2205.14100.pdf)**       | **[VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text)** | **146.25** |
|  🥉   |      **[BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)**      | **[Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)** | **136.50** |
|  4   |          [MMICL](https://github.com/HaozheZhao/MIC)          |      [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)       |   135.50   |
|  5   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   134.25   |
|  6   |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   133.25   |
|  7   |        [Lion](https://github.com/mynameischaos/Lion)         |     [InternLM-7B](https://github.com/mynameischaos/Lion)     |   130.75   |
|  8   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   129.00   |
|  9   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   126.25   |
|  10  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   125.50   |
|  11  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   123.75   |
|  12  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   119.50   |
|  13  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   117.75   |
|  14  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   116.50   |
|  15  | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   114.51   |
|  16  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   113.50   |
|  17  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   101.25   |
|  18  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   96.25    |
|  19  | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   95.00    |
|  20  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   87.25    |
|  21  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     |   77.25    |
|  22  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   75.25    |
|  23  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   70.75    |
|  24  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) |   60.50    |
|  25  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   59.50    |
|  26  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) |   51.25    |

### OCR

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main)** | **[Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main)** | **162.50** |
|  🏅️   |        **[WeMM](https://github.com/scenarios/WeMM)**         |     **[InternLM-7B](https://github.com/scenarios/WeMM)**     | **162.50** |
|  🥈   |    **[Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)**    |       **[Qwen-7B](https://github.com/QwenLM/Qwen-VL)**       | **140.00** |
|  🥉   |      **[LLaVA](https://arxiv.org/pdf/2304.08485.pdf)**       |    **[Vicuna-13B](https://github.com/haotian-liu/LLaVA)**    | **125.00** |
|  🥉   | **[InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer)** | **[InternLM-7B](https://github.com/InternLM/InternLM-XComposer)** | **125.00** |
|  4   |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   110.00   |
|  4   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   110.00   |
|  5   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   107.50   |
|  6   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   102.50   |
|  7   |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   100.00   |
|  7   |          [MMICL](https://github.com/HaozheZhao/MIC)          |      [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)       |   100.00   |
|  8   |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   87.50    |
|  9   |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   82.50    |
|  10  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   80.00    |
|  11  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     |   77.50    |
|  11  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   77.50    |
|  12  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   72.50    |
|  12  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   72.50    |
|  12  |        [Lion](https://github.com/mynameischaos/Lion)         |     [InternLM-7B](https://github.com/mynameischaos/Lion)     |   72.50    |
|  13  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   65.00    |
|  13  | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   65.00    |
|  13  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   65.00    |
|  14  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) |   57.50    |
|  14  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   57.50    |
|  15  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) |   50.00    |
|  16  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   42.50    |

## Cognition

Sum of the scores of all cognition subtasks, including commonsense reasoning, numerical calculation, text translation, and code reasoning. The full score of each subtask is 200, and that of all cognition is 800.

| Rank |                            Model                             |                           Version                            | Score  |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :----: |
|  🏅️   |        [Lion](https://github.com/mynameischaos/Lion)         |     [InternLM-7B](https://github.com/mynameischaos/Lion)     | 445.71 |
|  🥈   |          [MMICL](https://github.com/HaozheZhao/MIC)          |      [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)       | 428.93 |
|  🥉   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 391.07 |
|  4   |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         | 360.71 |
|  5   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) | 356.43 |
|  5   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 356.43 |
|  6   |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        | 331.43 |
|  7   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    | 328.21 |
|  8   |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        | 321.07 |
|  9   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | 312.50 |
|  10  |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       | 306.43 |
|  10  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     | 306.43 |
|  11  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      | 295.36 |
|  12  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 291.79 |
|  13  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 290.00 |
|  13  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        | 290.00 |
|  14  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 276.07 |
|  15  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 261.79 |
|  16  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       | 249.64 |
|  17  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     | 249.29 |
|  18  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) | 228.57 |
|  19  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 226.79 |
|  20  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      | 215.71 |
|  21  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 213.57 |
|  22  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     | 181.79 |
|  23  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) | 144.29 |

### Commonsense Reasoning

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer)** | **[InternLM-7B](https://github.com/InternLM/InternLM-XComposer)** | **138.57** |
|  🥈   |      **[BLIVA](https://arxiv.org/pdf/2308.09936.pdf)**       |     **[FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)**      | **136.43** |
|  🥈   |        **[MMICL](https://github.com/HaozheZhao/MIC)**        |    **[FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)**     | **136.43** |
|  🥉   |    **[Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)**    |       **[Qwen-7B](https://github.com/QwenLM/Qwen-VL)**       | **130.71** |
|  4   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   129.29   |
|  5   |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   127.86   |
|  6   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   126.43   |
|  7   |        [Lion](https://github.com/mynameischaos/Lion)         |     [InternLM-7B](https://github.com/mynameischaos/Lion)     |   125.71   |
|  8   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   111.43   |
|  9   |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   110.71   |
|  10  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   110.00   |
|  10  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   110.00   |
|  11  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   106.43   |
|  11  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   106.43   |
|  12  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   100.71   |
|  13  | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   100.00   |
|  14  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   99.29    |
|  15  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   98.57    |
|  16  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   87.14    |
|  17  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   78.57    |
|  18  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) |   73.57    |
|  19  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     |   64.29    |
|  20  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) |   59.29    |
|  21  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   49.29    |
|  22  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   48.57    |
|  23  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   39.29    |

### Numerical Calculation

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **105.00** |
|  🥈   | **[Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main)** | **[Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main)** | **95.00**  |
|  🥉   |        **[MMICL](https://github.com/HaozheZhao/MIC)**        |    **[FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)**     | **82.50**  |
|  4   |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   77.50    |
|  5   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   72.50    |
|  6   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   70.00    |
|  7   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   65.00    |
|  8   |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   62.50    |
|  8   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   62.50    |
|  9   |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   60.00    |
|  10  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   57.50    |
|  11  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   55.00    |
|  11  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   55.00    |
|  12  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) |   50.00    |
|  12  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     |   50.00    |
|  12  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   50.00    |
|  13  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   47.50    |
|  13  | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   47.50    |
|  14  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) |   45.00    |
|  14  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   45.00    |
|  14  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   45.00    |
|  15  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   42.50    |
|  16  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   40.00    |
|  16  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   40.00    |
|  16  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   40.00    |
|  17  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   17.50    |

### Text Translation

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |    **[Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)**    |       **[Qwen-7B](https://github.com/QwenLM/Qwen-VL)**       | **147.50** |
|  🏅️   |      **[Lion](https://github.com/mynameischaos/Lion)**       |   **[InternLM-7B](https://github.com/mynameischaos/Lion)**   | **147.50** |
|  🥈   |        **[MMICL](https://github.com/HaozheZhao/MIC)**        |    **[FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)**     | **132.50** |
|  🥉   | **[LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)** | **[LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b)** | **112.50** |
|  4   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   112.50   |
|  5   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   102.50   |
|  6   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   87.50    |
|  7   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   85.00    |
|  8   |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   80.00    |
|  8   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   80.00    |
|  9   |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   77.50    |
|  9   |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     |   77.50    |
|  9   |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   77.50    |
|  10  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   72.50    |
|  11  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   67.50    |
|  12  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   65.00    |
|  12  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   65.00    |
|  13  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   60.00    |
|  14  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   57.50    |
|  14  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) |   57.50    |
|  14  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   57.50    |
|  15  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   50.00    |
|  15  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   50.00    |
|  16  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   47.50    |
|  17  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   42.50    |
|  18  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) |    0.00    |

### Code Reasoning

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)** | **[LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b)** | **356.43** |
|  🥈   |     **[Cheetor](https://arxiv.org/pdf/2308.04152.pdf)**      |     **[Vicuna-7B](https://github.com/DCDmllm/Cheetah)**      | **321.07** |
|  🥉   | **[InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer)** | **[InternLM-7B](https://github.com/InternLM/InternLM-XComposer)** | **391.07** |
|  4   |          [MMICL](https://github.com/HaozheZhao/MIC)          |      [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)       |   428.93   |
|  5   |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Blip2-Pretrain-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   290.00   |
|  6   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   328.21   |
|  7   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   306.43   |
|  8   |        [Lion](https://github.com/mynameischaos/Lion)         |     [InternLM-7B](https://github.com/mynameischaos/Lion)     |   445.71   |
|  9   | [Octopus](https://github.com/gray311/UnifiedMultimodalInstructionTuning) | [MPT7B](https://github.com/gray311/UnifiedMultimodalInstructionTuning) |   312.50   |
|  10  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   290.00   |
|  11  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   213.57   |
|  12  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   331.43   |
|  13  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [Mplug-Owl-Llama-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   276.07   |
|  14  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [Blip2-Instruct-Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   291.79   |
|  15  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [Vl-Vicuna-7B](https://github.com/VPGTrans/VPGTrans)     |   249.29   |
|  16  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   226.79   |
|  17  | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) |   356.43   |
|  18  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   249.64   |
|  19  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   181.79   |
|  20  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [Pandagpt-7B-Max-Len-512](https://github.com/yxuansu/PandaGPT) |   228.57   |
|  21  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   295.36   |
|  22  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   215.71   |
|  23  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   261.79   |
|  24  |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   306.43   |
|  25  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   360.71   |
|  26  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [Minigpt4-Aligned-With-Vicuna13B](https://github.com/Vision-CAIR/MiniGPT-4) |   144.29   |

