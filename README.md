# MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models

<img src="./images/dataset.png" width="96%" height="96%">

> Multimodal Large Language Model (MLLM) relies on the powerful LLM to perform multimodal tasks, showing amazing emergent abilities in recent studies, such as writing poems based on an image. However, it is difficult for these case studies to fully reflect the performance of MLLM, lacking a comprehensive evaluation. In this paper, we fill in this blank, presenting the first MLLM Evaluation benchmark MME. It measures both perception and cognition abilities on a total of 14 subtasks. In order to avoid data leakage that may arise from direct use of public datasets for evaluation, the annotations of instruction-answer pairs are all manually designed. The concise instruction design allows us to fairly compare MLLMs, instead of struggling in prompt engineering. Besides, with such an instruction, we can also easily carry out quantitative statistics. A total of 16 advanced MLLMs are comprehensively evaluated on our MME, which not only suggests that existing MLLMs still have a large room for improvement, but also reveals the potential directions for the subsequent model optimization.




## Our MLLM works

🔥🔥🔥 **A Survey on Multimodal Large Language Models**  
**[Project Page](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)** | **[Paper](https://arxiv.org/pdf/2306.13549.pdf)**

A curated list of Multimodal Large Language Models (MLLMs), including datasets, multimodal instruction tuning, multimodal in-context learning, multimodal chain-of-thought, llm-aided visual reasoning, foundation models, and others. This list will be updated in real time. :sparkles:

Welcome to join our WeChat group of MLLM communication! 

Please add WeChat ID (xjtupanda) to join the group. :star2:

---

🔥🔥🔥 **MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models**  
**[Project Page [Leaderboards]](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation)** | **[Paper](https://arxiv.org/pdf/2306.13394.pdf)**

Leaderboards of **16** advanced MLLMs, including [**BLIP-2**](https://arxiv.org/pdf/2301.12597.pdf), [**InstructBLIP**](https://arxiv.org/pdf/2305.06500.pdf), [**LLaVA**](https://arxiv.org/pdf/2304.08485.pdf), [**MiniGPT-4**](https://arxiv.org/pdf/2304.10592.pdf), [**mPLUG-Owl**](https://arxiv.org/pdf/2304.14178.pdf), [**LLaMA-Adapter V2**](https://arxiv.org/pdf/2304.15010.pdf), [**ImageBind_LLM**](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main), [**Otter**](https://arxiv.org/pdf/2305.03726.pdf), [**VisualGLM-6B**](https://github.com/THUDM/VisualGLM-6B), [**Multimodal-GPT**](https://arxiv.org/pdf/2305.04790.pdf), [**PandaGPT**](https://arxiv.org/pdf/2305.16355.pdf), [**VPGTrans**](https://arxiv.org/pdf/2305.01278.pdf), [**LaVIN**](https://arxiv.org/pdf/2305.15023.pdf), [**Lynx**](https://arxiv.org/pdf/2307.02469.pdf), [**Octopus**](https://5e517712ad3e493895.gradio.live/), and [**LRV-Instruction**](https://arxiv.org/pdf/2306.14565.pdf).

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
**[2023-08]** 
1. [08-08] Thanks to [**Fuxiao Liu**](https://github.com/FuxiaoLiu), we add [**LRV-Instruction**](https://github.com/FuxiaoLiu/LRV-Instruction) to our leaderboards. 🔥🔥

**[2023-07]** 
1. [07-28] Thanks to [**Yingzi Ma**](https://gray311.github.io/), his work [**Octopus**](https://5e517712ad3e493895.gradio.live/) has been updated to our leaderboards. 🔥🔥
2. [07-15] Thanks to [**Jiani Zheng**](https://github.com/Garlicisnotmyfavor), our leaderboards welcome a new member [**Lynx**](https://github.com/bytedance/lynx-llm). 🔥🔥
3. [07-12] Thanks to [**Ao Zhang**](https://github.com/waxnkw), his work [**VPGTrans**](https://github.com/VPGTrans/VPGTrans) has been added in our leaderboards. 🔥🔥
4. [07-09] Thanks to [**Bo Li**](https://github.com/Luodian), we have updated the evaluation of his work [**Otter**](https://github.com/Luodian/Otter). It uses the latest model [**OTTER-Image-MPT7B**](https://huggingface.co/luodian/OTTER-Image-MPT7B) that incoporates OpenFlamingv2 and enhances instruction following ability. 🔥🔥

**[2023-06]** 
1. [06-30] Thanks to [**Renrui Zhang**](https://github.com/ZrrSkywalker), we have updated the evaluation of his two works, i.e., [**LLaMA-Adapter V2**](https://github.com/OpenGVLab/LLaMA-Adapter) and [**ImageBind_LLM**](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM). The former is re-evaluated after changing the model [**weights**](https://github.com/OpenGVLab/LLaMA-Adapter/releases/download/v.2.0.0/7fa55208379faf2dd862565284101b0e4a2a72114d6490a95e432cf9d9b6c813_BIAS-7B.pth), and the latter is a newly added MLLM. 🔥🔥
2. [06-30] Thanks to [**Gen Luo**](https://github.com/luogen1996), we have added the evaluation of his work [**LaVIN**](https://github.com/luogen1996/LaVIN). 🔥🔥
3. [06-30] The results of other models have also been updated, retrieving the answer from the beginning of the generated responses instead of the whole responses. [**An automated evaluation script**](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/blob/Evaluation/tools/eval_tool.zip) for the calculation of scores has been released!

---

# Evaluation Results
The top 5 on the perception and cognition leaderboards:

<img src="./images/evaluation.png" width="80%" height="80%">


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
|  🏅️   |       **[Lynx](https://arxiv.org/pdf/2307.02469.pdf)**       |    **[vicuna-7b](https://github.com/bytedance/lynx-llm)**    | **1373.23** |
|  🥈   |      **[BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)**      | **[blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)** | **1293.84** |
|  🥉   |      **[Otter](https://arxiv.org/pdf/2305.03726.pdf)**       |  **[OTTER-Image-MPT7B](https://github.com/Luodian/Otter)**   | **1292.26** |
|  4   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   1212.82   |
|  5   |      [Octopus](https://5e517712ad3e493895.gradio.live/)      |                            MPT7B                             |   1095.76   |
|  6   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) |   972.67    |
|  7   |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   967.34    |
|  8   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   963.60    |
|  9   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   895.96    |
|  10  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) |   866.57    |
|  11  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)     |   790.45    |
|  12  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   775.77    |
|  13  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   705.31    |
|  14  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   654.72    |
|  15  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   642.59    |
|  16  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   502.82    |

### Existence

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |      **[Otter](https://arxiv.org/pdf/2305.03726.pdf)**       |  **[OTTER-Image-MPT7B](https://github.com/Luodian/Otter)**   | **195.00** |
|  🏅️   |       **[Lynx](https://arxiv.org/pdf/2307.02469.pdf)**       |    **[vicuna-7b](https://github.com/bytedance/lynx-llm)**    | **195.00** |
|  🥈   |   **[InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)**   | **[blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip)** | **185.00** |
|  🥈   |      **[LaVIN](https://arxiv.org/pdf/2305.15023.pdf)**       |     **[LAVIN-13B](https://github.com/luogen1996/LaVIN)**     | **185.00** |
|  🥉   |    **[Octopus](https://5e517712ad3e493895.gradio.live/)**    |                          **MPT7B**                           | **180.00** |
|  4   |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   160.00   |
|  5   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   128.33   |
|  6   |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   120.00   |
|  6   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) |   120.00   |
|  7   |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) |   115.00   |
|  7   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   115.00   |
|  8   |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   85.00    |
|  9   |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   70.00    |
|  9   |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)     |   70.00    |
|  10  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   61.67    |
|  11  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   50.00    |

### Count

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |       **[Lynx](https://arxiv.org/pdf/2307.02469.pdf)**       |    **[vicuna-7b](https://github.com/bytedance/lynx-llm)**    | **151.67** |
|  🥈   |   **[InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)**   | **[blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip)** | **143.33** |
|  🥉   |      **[BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)**      | **[blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)** | **135.00** |
|  4   |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) |   123.33   |
|  5   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   88.33    |
|  5   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   88.33    |
|  5   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   88.33    |
|  6   |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)     |   85.00    |
|  7   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   60.00    |
|  8   |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   55.00    |
|  9   |      [Octopus](https://5e517712ad3e493895.gradio.live/)      |                            MPT7B                             |   53.33    |
|  10  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   50.00    |
|  10  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) |   50.00    |
|  10  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   50.00    |
|  10  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   50.00    |
|  10  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   50.00    |

### Position

| Rank |                            Model                             |                           Version                            |   Score   |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :-------: |
|  🏅️   |       **[Lynx](https://arxiv.org/pdf/2307.02469.pdf)**       |    **[vicuna-7b](https://github.com/bytedance/lynx-llm)**    | **90.00** |
|  🥈   |      **[Otter](https://arxiv.org/pdf/2305.03726.pdf)**       |  **[OTTER-Image-MPT7B](https://github.com/Luodian/Otter)**   | **86.67** |
|  🥉   |    **[MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)**     | **[minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4)** | **81.67** |
|  4   |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   73.33   |
|  5   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   68.33   |
|  6   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   66.67   |
|  7   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   63.33   |
|  7   |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)     |   63.33   |
|  8   |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   58.33   |
|  9   |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   50.00   |
|  9   |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   50.00   |
|  9   |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   50.00   |
|  10  |      [Octopus](https://5e517712ad3e493895.gradio.live/)      |                            MPT7B                             |   48.33   |
|  11  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) |   48.33   |
|  11  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   48.33   |
|  12  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   46.67   |

### Color

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |       **[Lynx](https://arxiv.org/pdf/2307.02469.pdf)**       |    **[vicuna-7b](https://github.com/bytedance/lynx-llm)**    | **170.00** |
|  🥈   |   **[InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)**   | **[blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip)** | **153.33** |
|  🥉   |      **[BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)**      | **[blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)** | **148.33** |
|  4   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   113.33   |
|  5   |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) |   110.00   |
|  6   |      [Octopus](https://5e517712ad3e493895.gradio.live/)      |                            MPT7B                             |   103.33   |
|  7   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   96.67    |
|  8   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) |   75.00    |
|  8   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   75.00    |
|  9   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   73.33    |
|  9   |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)     |   73.33    |
|  10  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   68.33    |
|  11  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   55.00    |
|  11  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   55.00    |
|  11  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   55.00    |
|  12  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   50.00    |

### Poster

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |      **[BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)**      | **[blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)** | **141.84** |
|  🥈   |      **[Otter](https://arxiv.org/pdf/2305.03726.pdf)**       |  **[OTTER-Image-MPT7B](https://github.com/Luodian/Otter)**   | **138.78** |
|  🥉   |    **[Octopus](https://5e517712ad3e493895.gradio.live/)**    |                          **MPT7B**                           | **138.10** |
|  4   |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   136.05   |
|  5   |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [vicuna-7b](https://github.com/bytedance/lynx-llm)      |   124.83   |
|  6   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   123.81   |
|  7   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) |   99.66    |
|  8   |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)     |   84.01    |
|  9   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   79.59    |
|  10  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   76.53    |
|  11  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   71.43    |
|  12  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   65.99    |
|  13  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   64.97    |
|  14  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   57.82    |
|  15  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) |   55.78    |
|  16  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   50.00    |

### Celebrity

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |      **[Otter](https://arxiv.org/pdf/2305.03726.pdf)**       |  **[OTTER-Image-MPT7B](https://github.com/Luodian/Otter)**   | **172.65** |
|  🥈   |    **[Octopus](https://5e517712ad3e493895.gradio.live/)**    |                          **MPT7B**                           | **129.41** |
|  🥉   |       **[Lynx](https://arxiv.org/pdf/2307.02469.pdf)**       |    **[vicuna-7b](https://github.com/bytedance/lynx-llm)**    | **118.24** |
|  4   |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   105.59   |
|  5   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   101.18   |
|  6   |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   100.29   |
|  7   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) |   86.18    |
|  8   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   76.47    |
|  9   |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   73.82    |
|  10  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   72.35    |
|  11  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) |   65.29    |
|  12  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   57.06    |
|  13  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)     |   53.53    |
|  14  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   53.24    |
|  15  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   48.82    |
|  16  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   47.35    |

### Scene

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |       **[Lynx](https://arxiv.org/pdf/2307.02469.pdf)**       |    **[vicuna-7b](https://github.com/bytedance/lynx-llm)**    | **164.50** |
|  🥈   |      **[Otter](https://arxiv.org/pdf/2305.03726.pdf)**       |  **[OTTER-Image-MPT7B](https://github.com/Luodian/Otter)**   | **158.75** |
|  🥉   |    [**Octopus](https://5e517712ad3e493895.gradio.live/)**    |                          **MPT7B**                           | **157.25** |
|  4   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   153.00   |
|  5   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) |   148.50   |
|  6   |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   146.25   |
|  7   |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   145.25   |
|  8   |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)     |   141.75   |
|  9   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   136.75   |
|  10  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   135.50   |
|  11  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   122.00   |
|  12  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   118.00   |
|  13  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   113.25   |
|  14  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) |   95.75    |
|  15  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   68.00    |
|  16  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   50.00    |

### Landmark

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |       **[Lynx](https://arxiv.org/pdf/2307.02469.pdf)**       |    **[vicuna-7b](https://github.com/bytedance/lynx-llm)**    | **162.00** |
|  🥈   |    **[mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)**     | **[mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b)** | **159.25** |
|  🥉   | **[LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)** | **[LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal)** | **150.25** |
|  4   |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   138.00   |
|  5   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   137.25   |
|  6   |      [Octopus](https://5e517712ad3e493895.gradio.live/)      |                            MPT7B                             |   126.00   |
|  7   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   104.35   |
|  8   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   93.50    |
|  9   |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   83.75    |
|  10  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   79.75    |
|  11  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   69.75    |
|  11  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   69.75    |
|  12  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) |   69.00    |
|  13  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)     |   64.75    |
|  14  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   62.00    |
|  15  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   50.00    |

### Artwork

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |      **[BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)**      | **[blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)** | **136.50** |
|  🥈   |   **[InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)**   | **[blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip)** | **134.25** |
|  🥉   |      **[Otter](https://arxiv.org/pdf/2305.03726.pdf)**       |  **[OTTER-Image-MPT7B](https://github.com/Luodian/Otter)**   | **129.00** |
|  4   |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [vicuna-7b](https://github.com/bytedance/lynx-llm)      |   119.50   |
|  5   |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   96.25    |
|  6   |      [Octopus](https://5e517712ad3e493895.gradio.live/)      |                            MPT7B                             |   95.00    |
|  7   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   87.25    |
|  8   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   77.50    |
|  9   |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)     |   77.25    |
|  10  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   75.25    |
|  11  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   70.75    |
|  12  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) |   69.75    |
|  13  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   59.50    |
|  14  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) |   55.75    |
|  15  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   51.25    |
|  16  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   49.00    |

### OCR

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)** | **[LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal)** | **125.00** |
|  🥈   |      **[BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)**      | **[blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)** | **110.00** |
|  🥉   |      [**LaVIN](https://arxiv.org/pdf/2305.15023.pdf)**       |     **[LAVIN-13B](https://github.com/luogen1996/LaVIN)**     | **107.50** |
|  4   |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) |   95.00    |
|  5   |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   82.50    |
|  6   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   80.00    |
|  7   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   80.00    |
|  8   |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)     |   77.50    |
|  8   |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [vicuna-7b](https://github.com/bytedance/lynx-llm)      |   77.50    |
|  9   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   72.50    |
|  9   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   72.50    |
|  10  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   65.00    |
|  10  |      [Octopus](https://5e517712ad3e493895.gradio.live/)      |                            MPT7B                             |   65.00    |
|  11  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   50.00    |
|  11  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   50.00    |
|  12  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   42.50    |

## Cognition

Sum of the scores of all cognition subtasks, including commonsense reasoning, numerical calculation, text translation, and code reasoning. The full score of each subtask is 200, and that of all cognition is 800.

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |    **[Octopus](https://5e517712ad3e493895.gradio.live/)**    |                          **MPT7B**                           | **312.50** |
|  🥈   |      **[Otter](https://arxiv.org/pdf/2305.03726.pdf)**       |  **[OTTER-Image-MPT7B](https://github.com/Luodian/Otter)**   | **306.43** |
|  🥉   | **[LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)**  |  **[LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)**  | **296.43** |
|  4   |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) |   292.14   |
|  5   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   291.79   |
|  6   |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   290.00   |
|  7   |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   276.07   |
|  8   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   249.64   |
|  9   |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)     |   249.29   |
|  10  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) |   248.93   |
|  11  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   228.57   |
|  12  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   226.79   |
|  13  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [vicuna-7b](https://github.com/bytedance/lynx-llm)      |   215.71   |
|  14  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   214.64   |
|  15  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   213.57   |
|  16  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   181.79   |

### Commonsense Reasoning

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |   **[InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)**   | **[blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip)** | **129.29** |
|  🥈   |       **[Lynx](https://arxiv.org/pdf/2307.02469.pdf)**       |    **[vicuna-7b](https://github.com/bytedance/lynx-llm)**    | **110.71** |
|  🥉   |      **[BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)**      | **[blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)** | **110.00** |
|  4   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   106.43   |
|  5   |      [Octopus](https://5e517712ad3e493895.gradio.live/)      |                            MPT7B                             |   100.00   |
|  6   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   87.14    |
|  7   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) |   81.43    |
|  8   |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   78.57    |
|  9   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   76.43    |
|  10  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   73.57    |
|  11  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) |   72.14    |
|  12  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)     |   64.29    |
|  13  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   57.14    |
|  14  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   49.29    |
|  15  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   48.57    |
|  16  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   39.29    |

### Numerical Calculation

| Rank |                            Model                             |                           Version                            |   Score   |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :-------: |
|  🏅️   |      **[Otter](https://arxiv.org/pdf/2305.03726.pdf)**       |  **[OTTER-Image-MPT7B](https://github.com/Luodian/Otter)**   | **72.50** |
|  🥈   |      **[LaVIN](https://arxiv.org/pdf/2305.15023.pdf)**       |     **[LAVIN-13B](https://github.com/luogen1996/LaVIN)**     | **65.00** |
|  🥉   | **[LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)** | **[LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal)** | **62.50** |
|  🥉   |  **[Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)**  | **[Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT)** | **62.50** |
|  4   |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   60.00   |
|  5   |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) |   55.00   |
|  5   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   55.00   |
|  5   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   55.00   |
|  6   |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   50.00   |
|  6   |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   50.00   |
|  6   |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)     |   50.00   |
|  7   |      [Octopus](https://5e517712ad3e493895.gradio.live/)      |                            MPT7B                             |   47.50   |
|  8   |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   45.00   |
|  9   |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   40.00   |
|  9   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   40.00   |
|  10  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [vicuna-7b](https://github.com/bytedance/lynx-llm)      |   17.50   |

### Text Translation

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |    **[Octopus](https://5e517712ad3e493895.gradio.live/)**    |                          **MPT7B**                           | **102.50** |
|  🥈   |    **[mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)**     | **[mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b)** | **80.00**  |
|  🥉   |     **[VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)**     |   **[vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)**   | **77.50**  |
|  🥉   | **[LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)**  |  **[LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)**  | **77.50**  |
|  4   |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   65.00    |
|  4   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   65.00    |
|  5   |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   60.00    |
|  6   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   57.50    |
|  6   |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   57.50    |
|  6   |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   57.50    |
|  7   |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       | [minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4) |   55.00    |
|  8   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   50.00    |
|  8   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) |   50.00    |
|  8   |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   50.00    |
|  9   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   47.50    |
|  10  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [vicuna-7b](https://github.com/bytedance/lynx-llm)      |   42.50    |

### Code Reasoning

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |    **[MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)**     | **[minigpt4-aligned-with-vicuna13b](https://github.com/Vision-CAIR/MiniGPT-4)** | **110.00** |
|  🥈   | **[LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)**  |  **[LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)**  | **87.50**  |
|  🥉   |      **[BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)**      | **[blip2-pretrain-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2)** | **75.00**  |
|  4   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   70.00    |
|  5   |      [Octopus](https://5e517712ad3e493895.gradio.live/)      |                            MPT7B                             |   62.50    |
|  6   | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [imagebind_LLM-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   60.00    |
|  7   |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [mplug-owl-llama-7b](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   57.50    |
|  7   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [blip2-instruct-flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   57.50    |
|  7   |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |     [vl-vicuna-7b](https://github.com/VPGTrans/VPGTrans)     |   57.50    |
|  8   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMAv2-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal) |   55.00    |
|  8   |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   55.00    |
|  9   |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |     [LLaVA-7B-v0](https://github.com/haotian-liu/LLaVA)      |   50.00    |
|  9   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   50.00    |
|  10  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   47.50    |
|  10  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       | [pandagpt-7b-max-len-512](https://github.com/yxuansu/PandaGPT) |   47.50    |
|  11  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [vicuna-7b](https://github.com/bytedance/lynx-llm)      |   45.00    |
