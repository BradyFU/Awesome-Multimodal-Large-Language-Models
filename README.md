# MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models

<img src="./images/dataset.png" width="96%" height="96%">

> Multimodal Large Language Model (MLLM) relies on the powerful LLM to perform multimodal tasks, showing amazing emergent abilities in recent studies, such as writing poems based on an image. However, it is difficult for these case studies to fully reflect the performance of MLLM, lacking a comprehensive evaluation. In this paper, we fill in this blank, presenting the first MLLM Evaluation benchmark MME. It measures both perception and cognition abilities on a total of 14 subtasks. In order to avoid data leakage that may arise from direct use of public datasets for evaluation, the annotations of instruction-answer pairs are all manually designed. The concise instruction design allows us to fairly compare MLLMs, instead of struggling in prompt engineering. Besides, with such an instruction, we can also easily carry out quantitative statistics. A total of 23 advanced MLLMs are comprehensively evaluated on our MME, which not only suggests that existing MLLMs still have a large room for improvement, but also reveals the potential directions for the subsequent model optimization.




## Our MLLM works

🔥🔥🔥 **A Survey on Multimodal Large Language Models**  
**[Project Page](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)** | **[Paper](https://arxiv.org/pdf/2306.13549.pdf)**

A curated list of Multimodal Large Language Models (MLLMs), including datasets, multimodal instruction tuning, multimodal in-context learning, multimodal chain-of-thought, llm-aided visual reasoning, foundation models, and others. This list will be updated in real time. :sparkles:

Welcome to join our WeChat group of MLLM communication! 

Please add WeChat ID (xjtupanda) to join the group. :star2:

---

🔥🔥🔥 **MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models**  
**[Project Page [Leaderboards]](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation)** | **[Paper](https://arxiv.org/pdf/2306.13394.pdf)**

Leaderboards of **23** advanced MLLMs, including [**BLIP-2**](https://arxiv.org/pdf/2301.12597.pdf), [**InstructBLIP**](https://arxiv.org/pdf/2305.06500.pdf), [**LLaVA**](https://arxiv.org/pdf/2304.08485.pdf), [**MiniGPT-4**](https://arxiv.org/pdf/2304.10592.pdf), [**mPLUG-Owl**](https://arxiv.org/pdf/2304.14178.pdf), [**LLaMA-Adapter V2**](https://arxiv.org/pdf/2304.15010.pdf), [**ImageBind_LLM**](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main), [**Otter**](https://arxiv.org/pdf/2305.03726.pdf), [**VisualGLM-6B**](https://github.com/THUDM/VisualGLM-6B), [**Multimodal-GPT**](https://arxiv.org/pdf/2305.04790.pdf), [**PandaGPT**](https://arxiv.org/pdf/2305.16355.pdf), [**VPGTrans**](https://arxiv.org/pdf/2305.01278.pdf), [**LaVIN**](https://arxiv.org/pdf/2305.15023.pdf), [**Lynx**](https://arxiv.org/pdf/2307.02469.pdf), [**Octopus**](https://17b56cb5aa22eb65bf.gradio.live/), [**LRV-Instruction**](https://arxiv.org/pdf/2306.14565.pdf), [**Cheetor**](https://arxiv.org/pdf/2308.04152.pdf), [**MMICL**](https://github.com/HaozheZhao/MIC), [**GIT2**](https://arxiv.org/pdf/2205.14100.pdf), [**BLIVA**](https://arxiv.org/pdf/2308.09936.pdf), [**Skywork-MM**](https://github.com/will-singularity/Skywork-MM/tree/main), [**Qwen-VL-Chat**](https://arxiv.org/pdf/2308.12966.pdf), and [**InternLM-XComposer-VL**](https://arxiv.org/pdf/2309.15112.pdf).

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

🔥🔥🔥 **Hallucination Correction for MLLMs** 🚀🚀🚀  
**[Code](https://github.com/BradyFU/Hallucination-Correction-for-MLLMs)** | **[Online Demo](https://3f42ced93bd85313af.gradio.live)** | **[Paper [Coming Soon]](https://github.com/BradyFU/Hallucination-Correction-for-MLLMs)**

This is the first work to correct hallucination in multimodal large language models. The code and online demo have been released, and the paper will be coming soon!

<p align="center">
<img src="./images/example.jpeg" width="96%" height="96%">
</p>


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

**[2023-09]** 

1. [09-27] Thanks to [**Xiaoyi Dong**](https://github.com/LightDXY), [**InternLM-XComposer-VL**](https://github.com/InternLM/InternLM-XComposer) joins our leaderboards. 🔥🔥
2. [09-05] Thanks to [**Jinze Bai**](https://github.com/jinze1994), our leaderboards usher in [**Qwen-VL-Chat**](https://github.com/QwenLM/Qwen-VL). 🔥🔥
3. [09-01] Thanks to [**Skywork Multi-Modal Group**](https://github.com/will-singularity), [**Skywork-MM**](https://github.com/will-singularity/Skywork-MM/tree/main) takes part in our leaderboards. 🔥🔥

**[2023-08]** 

1. [08-28] Thanks to [**UCSD MLPC**](https://github.com/mlpc-ucsd), we welcome [**BLIVA**](https://github.com/mlpc-ucsd/BLIVA) to join our leaderboards. 🔥🔥
2. [08-28] Thanks to [**Jianfeng Wang**](https://scholar.google.com.hk/citations?user=vJWEw_8AAAAJ&hl=zh-CN&oi=sra), [**GIT2**](https://github.com/microsoft/GenerativeImage2Text) is added to our leaderboards. 🔥🔥
3. [08-28] Thanks to [**Yike Yuan**](https://github.com/yyk-wew) and [**Songyang Zhang**](https://github.com/tonysy), the results of [**MiniGPT4**](https://arxiv.org/pdf/2304.10592.pdf) have been revised. 🔥🔥
4. [08-21] Thanks to [**Haozhe Zhao**](https://github.com/HaozheZhao), [**MMICL**](https://github.com/HaozheZhao/MIC) joins our leaderboards (The results are renewed on 09-17 by upgrading the checkpoint.). 🔥🔥
5. [08-13] Thanks to [**Zhejiang University DCD Lab**](https://github.com/DCDmllm), our leaderboards incorporate a new member [**Cheetor**](https://github.com/DCDmllm/Cheetah). 🔥🔥
6. [08-08] Thanks to [**Fuxiao Liu**](https://github.com/FuxiaoLiu), we add [**LRV-Instruction**](https://github.com/FuxiaoLiu/LRV-Instruction) to our leaderboards. 🔥🔥

**[2023-07]** 

1. [07-28] Thanks to [**Yingzi Ma**](https://gray311.github.io/), his work [**Octopus**](https://17b56cb5aa22eb65bf.gradio.live/) has been updated to our leaderboards.
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

<img src="./images/evaluation-0926.png" width="80%" height="80%">


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

| Rank | Model                                                        | Version                                                      | Score   |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------- |
| 🏅️    | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 1528.45 |
| 🥈    | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 1487.58 |
| 🥉    | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 1419.08 |
| 4    | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 1381.73 |
| 5    | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 1373.23 |
| 6    | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 1337.73 |
| 7    | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 1332.05 |
| 8    | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 1299.96 |
| 9    | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 1299.78 |
| 10   | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 1293.84 |
| 11   | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 1292.26 |
| 12   | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 1212.82 |
| 13   | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 1095.76 |
| 14   | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 972.67  |
| 15   | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 967.34  |
| 16   | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 963.60  |
| 17   | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 790.45  |
| 18   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 775.77  |
| 19   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 705.31  |
| 20   | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 654.72  |
| 21   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 642.59  |
| 22   | [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)            | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) | 581.67  |
| 23   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 502.82  |

### Existence

| Rank | Model                                                        | Version                                                      | Score  |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| 🏅️    | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 195.00 |
| 🥈    | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 195.00 |
| 🥉    | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 190.00 |
| 4    | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 190.00 |
| 5    | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 185.00 |
| 6    | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 185.00 |
| 7    | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 180.00 |
| 8    | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 180.00 |
| 9    | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 180.00 |
| 10   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 180.00 |
| 11   | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 170.00 |
| 12   | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 165.00 |
| 13   | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 160.00 |
| 14   | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 158.33 |
| 15   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 128.33 |
| 16   | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 120.00 |
| 17   | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 120.00 |
| 18   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 85.00  |
| 19   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 70.00  |
| 20   | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 70.00  |
| 21   | [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)            | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) | 68.33  |
| 22   | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 61.67  |
| 23   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 50.00  |

### Count

| Rank | Model                                                        | Version                                                      | Score  |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| 🏅️    | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 160.00 |
| 🥈    | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 158.33 |
| 🥉    | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 151.67 |
| 4    | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 151.67 |
| 5    | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 150.00 |
| 6    | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 143.33 |
| 7    | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 138.33 |
| 8    | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 135.00 |
| 9    | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 118.33 |
| 10   | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 111.67 |
| 11   | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 96.67  |
| 12   | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 88.33  |
| 13   | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 88.33  |
| 14   | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 85.00  |
| 15   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 60.00  |
| 16   | [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)            | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) | 55.00  |
| 17   | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 55.00  |
| 18   | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 53.33  |
| 19   | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 50.00  |
| 20   | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 50.00  |
| 21   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 50.00  |
| 22   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 50.00  |
| 23   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 50.00  |

### Position

| Rank | Model                                                        | Version                                                      | Score  |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| 🏅️    | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 128.33 |
| 🥈    | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 126.67 |
| 🥉    | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 96.67  |
| 4    | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 90.00  |
| 5    | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 86.67  |
| 6    | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 86.67  |
| 7    | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 81.67  |
| 8    | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 81.67  |
| 9    | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 80.00  |
| 10   | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 73.33  |
| 11   | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 66.67  |
| 12   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 63.33  |
| 13   | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 63.33  |
| 14   | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 63.33  |
| 15   | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 58.33  |
| 16   | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 50.00  |
| 17   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 50.00  |
| 18   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 50.00  |
| 19   | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 48.33  |
| 20   | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 48.33  |
| 21   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 48.33  |
| 22   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 46.67  |
| 23   |                                                              |                                                              | 43.33  |

### Color

| Rank | Model                                                        | Version                                                      | Score  |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| 🏅️    | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 180.00 |
| 🥈    | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 170.00 |
| 🥉    | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 170.00 |
| 4    | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 165.00 |
| 5    | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 165.00 |
| 6    | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 158.33 |
| 7    | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 156.67 |
| 8    | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 153.33 |
| 9    | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 148.33 |
| 10   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 145.00 |
| 11   | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 116.67 |
| 12   | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 113.33 |
| 13   | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 103.33 |
| 14   | [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)            | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) | 75.00  |
| 15   | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 75.00  |
| 16   | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 75.00  |
| 17   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 73.33  |
| 18   | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 73.33  |
| 19   | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 68.33  |
| 20   | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 55.00  |
| 21   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 55.00  |
| 22   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 55.00  |
| 23   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 50.00  |

### Poster

| Rank | Model                                                        | Version                                                      | Score  |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| 🏅️    | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 178.57 |
| 🥈    | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 175.85 |
| 🥉    | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 161.90 |
| 4    | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 155.10 |
| 5    | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 147.28 |
| 6    | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 146.26 |
| 7    | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 141.84 |
| 8    | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 139.04 |
| 9    | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 138.78 |
| 10   | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 138.10 |
| 11   | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 136.05 |
| 12   | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 124.83 |
| 13   | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 123.81 |
| 14   | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 112.59 |
| 15   | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 99.66  |
| 16   | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 84.01  |
| 17   | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 79.59  |
| 18   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 76.53  |
| 19   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 65.99  |
| 20   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 64.97  |
| 21   | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 57.82  |
| 22   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 50.00  |
| 23   | [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)            | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) | 41.84  |

### Celebrity

| Rank | Model                                                        | Version                                                      | Score  |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| 🏅️    | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 172.65 |
| 🥈    | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 164.12 |
| 🥉    | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 160.29 |
| 4    | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 150.29 |
| 5    | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 145.88 |
| 6    | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 141.76 |
| 7    | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 140.88 |
| 8    | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 129.41 |
| 9    | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 120.59 |
| 10   | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 118.24 |
| 11   | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 112.65 |
| 12   | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 105.59 |
| 13   | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 101.18 |
| 14   | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 100.29 |
| 15   | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 86.18  |
| 16   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 76.47  |
| 17   | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 73.82  |
| 18   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 57.06  |
| 19   | [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)            | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) | 54.41  |
| 20   | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 53.53  |
| 21   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 53.24  |
| 22   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 48.82  |
| 23   | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 47.35  |

### Scene

| Rank | Model                                                        | Version                                                      | Score  |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| 🏅️    | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 164.50 |
| 🥈    | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 159.75 |
| 🥉    | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 158.75 |
| 4    | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 158.50 |
| 5    | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 157.25 |
| 6    | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 156.00 |
| 7    | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 153.75 |
| 8    | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 153.00 |
| 9    | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 152.25 |
| 10   | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 151.50 |
| 11   | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 148.50 |
| 12   | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 147.98 |
| 13   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 146.25 |
| 14   | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 145.25 |
| 15   | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 141.75 |
| 16   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 138.89 |
| 17   | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 136.75 |
| 18   | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 135.50 |
| 19   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 118.00 |
| 20   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 113.25 |
| 21   | [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)            | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) | 71.75  |
| 22   | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 68.00  |
| 23   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 50.00  |

### Landmark

| Rank | Model                                                        | Version                                                      | Score  |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| 🏅️    | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 165.25 |
| 🥈    | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 164.00 |
| 🥉    | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 162.00 |
| 4    | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 160.53 |
| 5    | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 159.25 |
| 6    | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 150.25 |
| 7    | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 145.73 |
| 8    | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 140.50 |
| 9    | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 138.00 |
| 10   | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 137.25 |
| 11   | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 136.13 |
| 12   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 127.04 |
| 13   | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 126.00 |
| 14   | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 93.50  |
| 15   | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 89.50  |
| 16   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 83.75  |
| 17   | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 79.75  |
| 18   | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 69.75  |
| 19   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 69.75  |
| 20   | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 64.75  |
| 21   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 62.00  |
| 22   | [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)            | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) | 54.00  |
| 23   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 50.00  |

### Artwork

| Rank | Model                                                        | Version                                                      | Score  |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| 🏅️    | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 146.25 |
| 🥈    | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 136.50 |
| 🥉    | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 135.50 |
| 4    | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 134.25 |
| 5    | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 133.25 |
| 6    | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 129.00 |
| 7    | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 126.25 |
| 8    | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 125.50 |
| 9    | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 119.50 |
| 10   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 114.51 |
| 11   | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 113.50 |
| 12   | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 101.25 |
| 13   | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 96.25  |
| 14   | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 95.00  |
| 15   | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 87.25  |
| 16   | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 77.25  |
| 17   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 75.25  |
| 18   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 70.75  |
| 19   | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 69.75  |
| 20   | [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)            | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) | 60.50  |
| 21   | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 59.50  |
| 22   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 51.25  |
| 23   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 49.00  |

### OCR

| Rank | Model                                                        | Version                                                      | Score  |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| 🏅️    | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 162.50 |
| 🥈    | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 140.00 |
| 🥉    | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 125.00 |
| 4    | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 125.00 |
| 5    | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 110.00 |
| 6    | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 110.00 |
| 7    | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 107.50 |
| 8    | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 100.00 |
| 9    | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 100.00 |
| 10   | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 87.50  |
| 11   | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 82.50  |
| 12   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 80.00  |
| 13   | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 77.50  |
| 14   | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 77.50  |
| 15   | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 72.50  |
| 16   | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 72.50  |
| 17   | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 65.00  |
| 18   | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 65.00  |
| 19   | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 65.00  |
| 20   | [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)            | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) | 57.50  |
| 21   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 50.00  |
| 22   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 50.00  |
| 23   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 42.50  |

## Cognition

Sum of the scores of all cognition subtasks, including commonsense reasoning, numerical calculation, text translation, and code reasoning. The full score of each subtask is 200, and that of all cognition is 800.

| Rank | Model                                                        | Version                                                      | Score  |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| 🏅️    | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 428.93 |
| 🥈    | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 391.07 |
| 🥉    | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 360.71 |
| 4    | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 356.43 |
| 5    | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 331.43 |
| 6    | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 328.21 |
| 7    | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 321.07 |
| 8    | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 312.50 |
| 9    | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 306.43 |
| 10   | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 291.79 |
| 11   | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 290.00 |
| 12   | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 276.07 |
| 13   | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 261.79 |
| 14   | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 249.64 |
| 15   | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 249.29 |
| 16   | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 248.93 |
| 17   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 228.57 |
| 18   | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 226.79 |
| 19   | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 215.71 |
| 20   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 214.64 |
| 21   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 213.57 |
| 22   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 181.79 |
| 23   | [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)            | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) | 144.29 |

### Commonsense Reasoning

| Rank | Model                                                        | Version                                                      | Score  |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| 🏅️    | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 138.57 |
| 🥈    | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 136.43 |
| 🥉    | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 136.43 |
| 4    | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 130.71 |
| 5    | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 129.29 |
| 6    | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 126.43 |
| 7    | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 110.71 |
| 8    | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 110.00 |
| 9    | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 106.43 |
| 10   | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 100.71 |
| 11   | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 100.00 |
| 12   | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 99.29  |
| 13   | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 98.57  |
| 14   | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 87.14  |
| 15   | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 81.43  |
| 16   | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 78.57  |
| 17   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 73.57  |
| 18   | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 64.29  |
| 19   | [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)            | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) | 59.29  |
| 20   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 57.14  |
| 21   | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 49.29  |
| 22   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 48.57  |
| 23   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 39.29  |

### Numerical Calculation

| Rank | Model                                                        | Version                                                      | Score |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ----- |
| 🏅️    | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 95.00 |
| 🥈    | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 82.50 |
| 🥉    | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 77.50 |
| 4    | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 72.50 |
| 5    | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 70.00 |
| 6    | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 65.00 |
| 7    | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 62.50 |
| 8    | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 62.50 |
| 9    | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 60.00 |
| 10   | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 57.50 |
| 11   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 55.00 |
| 12   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 55.00 |
| 13   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 50.00 |
| 14   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 50.00 |
| 15   | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 50.00 |
| 16   | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 50.00 |
| 17   | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 47.50 |
| 18   | [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)            | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) | 45.00 |
| 19   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 45.00 |
| 20   | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 40.00 |
| 21   | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 40.00 |
| 22   | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 40.00 |
| 23   | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 17.50 |

### Text Translation

| Rank | Model                                                        | Version                                                      | Score  |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ |
| 🏅️    | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 147.50 |
| 🥈    | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 132.50 |
| 🥉    | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 112.50 |
| 4    | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 102.50 |
| 5    | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 85.00  |
| 6    | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 80.00  |
| 7    | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 80.00  |
| 8    | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 77.50  |
| 9    | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 77.50  |
| 10   | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 67.50  |
| 11   | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 65.00  |
| 12   | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 65.00  |
| 13   | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 60.00  |
| 14   | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 57.50  |
| 15   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 57.50  |
| 16   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 57.50  |
| 17   | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 57.50  |
| 18   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 50.00  |
| 19   | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 50.00  |
| 20   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 50.00  |
| 21   | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 47.50  |
| 22   | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 42.50  |
| 23   | [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)            | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) | 0.00   |

### Code Reasoning

| Rank | Model                                                        | Version                                                      | Score |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ----- |
| 🏅️    | [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)              | [vicuna-7b](https://github.com/DCDmllm/Cheetah)              | 87.50 |
| 🥈    | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) | 85.00 |
| 🥉    | [MMICL](https://github.com/HaozheZhao/MIC)                   | [FlanT5xxl](https://arxiv.org/pdf/2309.07915.pdf)            | 77.50 |
| 4    | [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)               | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) | 75.00 |
| 5    | [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)      | [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)       | 72.50 |
| 6    | [Otter](https://arxiv.org/pdf/2305.03726.pdf)                | [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)        | 70.00 |
| 7    | [Octopus](https://5e517712ad3e493895.gradio.live/)           | MPT7B                                                        | 62.50 |
| 8    | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) | 60.00 |
| 9    | [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)                | [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)              | 60.00 |
| 10   | [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)            | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) | 57.50 |
| 11   | [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)         | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) | 57.50 |
| 12   | [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)             | [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)         | 57.50 |
| 13   | [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)     | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) | 55.00 |
| 14   | [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)       | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) | 55.00 |
| 15   | [Skywork-MM](https://github.com/will-singularity/Skywork-MM/tree/main) | [Skywork-MM-13B](https://github.com/will-singularity/Skywork-MM/tree/main) | 55.00 |
| 16   | [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)                | [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)          | 50.00 |
| 17   | [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)                | [LAVIN-13B](https://github.com/luogen1996/LaVIN)             | 50.00 |
| 18   | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)        | 47.50 |
| 19   | [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)             | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) | 47.50 |
| 20   | [Lynx](https://arxiv.org/pdf/2307.02469.pdf)                 | [vicuna-7b](https://github.com/bytedance/lynx-llm)           | 45.00 |
| 21   | [GIT2](https://arxiv.org/pdf/2205.14100.pdf)                 | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) | 45.00 |
| 22   | [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)           | [Qwen-7B](https://github.com/QwenLM/Qwen-VL)                 | 42.50 |
| 23   | [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)            | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) | 40.00 |
