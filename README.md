# MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models

<img src="./images/dataset.png" width="96%" height="96%">

> Multimodal Large Language Model (MLLM) relies on the powerful LLM to perform multimodal tasks, showing amazing emergent abilities in recent studies, such as writing poems based on an image. However, it is difficult for these case studies to fully reflect the performance of MLLM, lacking a comprehensive evaluation. In this paper, we fill in this blank, presenting the first MLLM Evaluation benchmark MME. It measures both perception and cognition abilities on a total of 14 subtasks. In order to avoid data leakage that may arise from direct use of public datasets for evaluation, the annotations of instruction-answer pairs are all manually designed. The concise instruction design allows us to fairly compare MLLMs, instead of struggling in prompt engineering. Besides, with such an instruction, we can also easily carry out quantitative statistics. A total of 50+ advanced MLLMs are comprehensively evaluated on our MME, which not only suggests that existing MLLMs still have a large room for improvement, but also reveals the potential directions for the subsequent model optimization.




## Our MLLM works

🔥🔥🔥 **A Survey on Multimodal Large Language Models**  
**[Project Page](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)** | **[Paper](https://arxiv.org/pdf/2306.13549.pdf)**
<p align="center">
    <img src="./images/timeline.jpg" width="100%" height="100%">
</p>

<font size=7><div align='center' > :apple: \[[Read our new version](https://arxiv.org/pdf/2306.13549.pdf)\] (update on April 2, 2024) </div></font>  
<div align='center'> <b>Chinese version</b> will be updated soon! </div>  

<div align='center'> The first survey for Multimodal Large Language Models (MLLMs). :sparkles: </div>  
<div align='center'> Welcome to add WeChat ID (wmd_ustc) to join our MLLM communication group! :star2: </div>

---

🔥🔥🔥 **MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models**  
**[Project Page [This Page]](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation)** | **[Paper](https://arxiv.org/pdf/2306.13394.pdf)**

The first comprehensive evaluation benchmark for MLLMs. Now the leaderboards include **50+** advanced models, such as Qwen-VL-Max, Gemini Pro, and GPT-4V. :sparkles:

If you want to add your model in our leaderboards, please feel free to email bradyfu24@gmail.com. We will update the leaderboards in time. :sparkles:

<details><summary>Download MME :star2::star2: </summary>

The benchmark dataset is collected by Xiamen University for academic research only. You can email yongdongluo@stu.xmu.edu.cn to obtain the dataset, according to the following requirement. 

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

🔥🔥🔥 **Woodpecker: Hallucination Correction for Multimodal Large Language Models**  
**[Paper](https://arxiv.org/pdf/2310.16045.pdf)** | **[Source Code![Star](https://img.shields.io/github/stars/BradyFU/Woodpecker.svg?style=social&label=Star)](https://github.com/BradyFU/Woodpecker)**

The first work to correct hallucinations in MLLMs. :sparkles:

---

🔥🔥🔥 **A Challenger to GPT-4V? Early Explorations of Gemini in Visual Expertise**  
**[Paper](https://arxiv.org/pdf/2312.12436.pdf)**

The first technical report for <b>Gemini vs GPT-4V</b>. A total of <b>128 pages</b>. Completed within one week of the Gemini API opening. :star2:

---

<br> **📑 If you find our projects helpful to your research, please consider citing:** <br>
```
@article{yin2023survey,
  title={A Survey on Multimodal Large Language Models},
  author={Yin, Shukang and Fu, Chaoyou and Zhao, Sirui and Li, Ke and Sun, Xing and Xu, Tong and Chen, Enhong},
  journal={arXiv preprint arXiv:2306.13549},
  year={2023}
}

@article{fu2023mme,
  title={MME: A Comprehensive Evaluation Benchmark for Multimodal Large Language Models},
  author={Fu, Chaoyou and Chen, Peixian and Shen, Yunhang and Qin, Yulei and Zhang, Mengdan and Lin, Xu and Yang, Jinrui and Zheng, Xiawu and Li, Ke and Sun, Xing and Wu, Yunsheng and Ji, Rongrong},
  journal={arXiv preprint arXiv:2306.13394},
  year={2023}
}

@article{yin2023woodpecker,
  title={Woodpecker: Hallucination Correction for Multimodal Large Language Models},
  author={Yin, Shukang and Fu, Chaoyou and Zhao, Sirui and Xu, Tong and Wang, Hao and Sui, Dianbo and Shen, Yunhang and Li, Ke and Sun, Xing and Chen, Enhong},
  journal={arXiv preprint arXiv:2310.16045},
  year={2023}
}

@article{fu2023gemini,
  title={A Challenger to GPT-4V? Early Explorations of Gemini in Visual Expertise},
  author={Fu, Chaoyou and Zhang, Renrui and Wang, Zihan and Huang, Yubo and Zhang, Zhengye and Qiu, Longtian and Ye, Gaoxiang and Shen, Yunhang and Zhang, Mengdan and Chen, Peixian and Zhao, Sirui and Lin, Shaohui and Jiang, Deqiang and Yin, Di and Gao, Peng and Li, Ke and Li, Hongsheng and Sun, Xing},
  journal={arXiv preprint arXiv:2312.12436},
  year={2023}
}
```

---

# News 🚀

1. [04-10] Thanks to [**Wenqiao Zhang**](https://scholar.google.com.hk/citations?user=XBbuP9YAAAAJ&hl=zh-CN&oi=sra), [**HyperLLaVA**](https://arxiv.org/pdf/2403.13447.pdf) joins our leaderboards. 🔥🔥
2. [03-14] Thanks to [**Muyang He**](https://scholar.google.com.hk/citations?user=Q0Xn7i4AAAAJ&hl=zh-CN&oi=sra), [**Bunny-3B**](https://github.com/BAAI-DCAI/Bunny) takes part in MME. 🔥🔥
3. [02-23] Thanks to [**Jingyu Liu**](https://scholar.google.com/citations?hl=en&tzom=-480&user=RCxy7UQAAAAJ), [**ChatTruth-7B**](https://huggingface.co/mingdali/ChatTruth-7B) is added to MME. 🔥🔥
4. [02-07] Thanks to [**TsinghuaNLP**](https://github.com/OpenBMB), [**MiniCPM**](https://github.com/OpenBMB/MiniCPM/#minicpm-v) and [**OmniLMM**](https://github.com/OpenBMB/MiniCPM/#minicpm-v) are incorporated into our leaderboards. 🔥🔥
5. [02-05] Thanks to [**Haotian Liu**](https://hliu.cc/), [**LLaVA-1.6**](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) is added to MME. 🔥🔥
6. [02-05] Thanks to [**Bin Lin**](https://scholar.google.com.hk/citations?user=GCOVDKoAAAAJ&hl=zh-CN&oi=sra), [**MoE-LLaVA**](https://github.com/PKU-YuanGroup/MoE-LLaVA) joins MME. 🔥🔥
7. [02-05] Thanks to [**Weihan Wang**](https://scholar.google.com.hk/citations?user=UaxGkIwAAAAJ&hl=zh-CN&oi=ao) and [**Wenyi Hong**](https://scholar.google.com.hk/citations?user=JSEzrlwAAAAJ&hl=zh-CN&oi=ao), [**CogVLM**](https://arxiv.org/pdf/2311.03079.pdf) and [**CogAgent**](https://arxiv.org/pdf/2312.08914.pdf) take part in MME. 🔥🔥
8. [01-25] Thanks to [**Shijie Wang**](https://scholar.google.com.hk/citations?hl=zh-CN&user=DuAqyTwAAAAJ), we welcome a new member [**Qwen-VL-Max**](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start). 🔥🔥
9. [01-22] Thanks to [**Xiaoyi Dong**](https://scholar.google.com/citations?user=FscToE0AAAAJ&hl=en), [**InternLM-XComposer2-VL**](https://github.com/InternLM/InternLM-XComposer) joins our leaderboards. 🔥🔥

<details><summary> <b>2023</b> </summary>

**[2023-12]** 

1. [12-31] Thanks to [**Dian Li**](https://scholar.google.com/citations?hl=zh-CN&user=rF7HU94AAAAJ), [**PureMM**](https://github.com/Q-MM/PureMM) takes part in our leaderboards (update in 2024-01-14 and 2024-01-21). 
2. [12-31] Thanks to Yilin Ma and [**Min Xu**](http://faculty.dlut.edu.cn/minxu/zh_CN/index.htm), [**RBDash**](https://github.com/RBDash-Team/RBDash) is added in MME. 
3. [12-18] Thanks to [**Zihan Wang**](https://github.com/hanhanHANS), our leaderboards usher in [**Gemini Pro**](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf).
4. [12-18] Thanks to [**Jinze Bai**](https://github.com/jinze1994), a new model [**Qwen-VL-Plus**](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) is added in MME.
5. [12-18] Thanks to [**Junbum Cha**](https://scholar.google.com.hk/citations?user=Py2gKnAAAAAJ&hl=zh-CN&oi=ao), [**Honeybee**](https://arxiv.org/pdf/2312.06742.pdf) joins our leaderboards.
6. [12-12] Thanks to [**Yuliang Liu**](https://github.com/Yuliang-Liu), [**Monkey-Chat**](https://github.com/Yuliang-Liu/Monkey) takes part in MME. 
7. [12-12] Thanks to [**Junkun Yuan**](https://scholar.google.com.hk/citations?hl=zh-CN&user=j3iFVPsAAAAJ&view_op=list_works&sortby=pubdate), we welcome a new member [**AGILMM**](https://github.com/AIResearchEnthusiast/AGILMM). 
8. [12-01] Thanks to [**Cheng Wen**](https://scholar.google.com/citations?user=9MLB3s8AAAAJ&hl=zh-CN), [**BELLE-VL**](https://huggingface.co/BELLE-2/BELLE-VL) is added to our leaderboards. 
9. [12-01] Thanks to [**PCI Research**](https://www.pcitech.com/), [**TransCore-M**](https://github.com/PCIResearch/TransCore-M) joins MME. 


**[2023-11]** 

1. [11-24] Thanks to [**Xiaoyi Dong**](https://scholar.google.com/citations?user=FscToE0AAAAJ&hl=en), we add [**ShareGPT4V**](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) to our leaderboards. 
2. [11-24] Thanks to [**Muyang He**](https://scholar.google.com/citations?hl=en&user=Q0Xn7i4AAAAJ), [**DataOptim**](https://github.com/BAAI-DCAI/DataOptim) joins MME. 
3. [11-24] Thanks to [**Zifei Shan**](https://scholar.google.com/citations?user=DGIdpTwAAAAJ&hl=en&oi=ao), [**Kanva**](https://github.com/llp1992/Kanva) is added. 
4. [11-21] Thanks to [**Junke Wang**](https://scholar.google.com.hk/citations?user=qQuxuo0AAAAJ&hl=zh-CN&oi=ao), [**LVIS-INSTRUCT4V**](https://arxiv.org/pdf/2311.07574.pdf) is added to our MME.
5. [11-18] Thanks to [**Zhenbo Luo**](https://dblp.org/pid/152/8206.html), our leaderboards welcome a new member [**CVLM**](https://github.com/buptlihang/CVLM).
6. [11-10] Thanks to [**Qinghao Ye**](https://scholar.google.com.hk/citations?user=ZYOhaGwAAAAJ&hl=zh-CN&oi=ao), we get a new model [**mPLUG-Owl2**](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) in our leaderboards.
7. [11-10] Thanks to [**Zhibin Wang**](https://scholar.google.com/citations?hl=zh-CN&user=YHzKee8AAAAJ), [**InfMLLM**](https://github.com/mightyzau/InfMLLM) joins our leaderboards (update in 2023-12-12).

**[2023-10]** 

1. [10-29] Thanks to [**Jiaming Han**](https://scholar.google.com/citations?hl=en&user=vgcxKEcAAAAJ&view_op=list_works), [**SPHINX**](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) is added to our leaderboards. 
2. [10-23] Thanks to [**Zihan Wang**](https://github.com/hanhanHANS), he manually evaluate the performance of [**GPT-4V**](https://cdn.openai.com/papers/GPTV_System_Card.pdf) on our benchmark. Note that GPT-4V refuses to answer questions that involve individuals, resulting in a zero score in the Celebrity subtask. 
3. [10-13] Thanks to [**Yizhou Zhou**](https://scholar.google.com/citations?user=dHBNmSkAAAAJ&hl=en&oi=sra), [**WeMM**](https://github.com/scenarios/WeMM) joins our leaderboards (The results are renewed on 2023-11-10 by updating the model). 
4. [10-13] Thanks to [**Cui Junbo**](https://github.com/thunlp/Muffin), we add [**Muffin**](https://github.com/thunlp/Muffin) to our leaderboards. 
5. [10-13] Thanks to [**Jiaming Han**](https://scholar.google.com/citations?hl=en&user=vgcxKEcAAAAJ&view_op=list_works), the results of [**LLaMA-Adapter V2**](https://github.com/OpenGVLab/LLaMA-Adapter) have been updated. 
6. [10-04] Thanks to [**Haotian Liu**](https://hliu.cc/), the results of [**LLaVA**](https://github.com/haotian-liu/LLaVA) have been updated. 

**[2023-09]** 

1. [09-28] Thanks to [**Huasong Zhong**](https://github.com/mynameischaos), [**Lion**](https://github.com/mynameischaos/Lion) is added.
2. [09-27] Thanks to [**Xiaoyi Dong**](https://scholar.google.com/citations?user=FscToE0AAAAJ&hl=en), [**InternLM-XComposer-VL**](https://github.com/InternLM/InternLM-XComposer) joins our leaderboards.
3. [09-05] Thanks to [**Jinze Bai**](https://github.com/jinze1994), our leaderboards usher in [**Qwen-VL-Chat**](https://github.com/QwenLM/Qwen-VL).
4. [09-01] Thanks to [**Skywork Multi-Modal Group**](https://github.com/will-singularity), [**Skywork-MM**](https://github.com/will-singularity/Skywork-MM/tree/main) takes part in our leaderboards.

**[2023-08]** 

1. [08-28] Thanks to [**UCSD MLPC**](https://github.com/mlpc-ucsd), we welcome [**BLIVA**](https://github.com/mlpc-ucsd/BLIVA) to join our leaderboards. 
2. [08-28] Thanks to [**Jianfeng Wang**](https://scholar.google.com.hk/citations?user=vJWEw_8AAAAJ&hl=zh-CN&oi=sra), [**GIT2**](https://github.com/microsoft/GenerativeImage2Text) is added to our leaderboards. 
3. [08-28] Thanks to [**Yike Yuan**](https://github.com/yyk-wew) and [**Songyang Zhang**](https://github.com/tonysy), the results of [**MiniGPT4**](https://arxiv.org/pdf/2304.10592.pdf) have been revised. 
4. [08-21] Thanks to [**Haozhe Zhao**](https://github.com/HaozheZhao), [**MMICL**](https://github.com/HaozheZhao/MIC) joins our leaderboards (The results are renewed on 2023-09-17 by upgrading the checkpoint.). 
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

</details>

---

# Results of Available Models [[Unavailable Version](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation-PrivateModel)]

<img src="./images/evaluation_chart_public_0128.png" width="70%" height="70%">

# Leaderboards of Available Models [[Unavailable Version](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models/tree/Evaluation-PrivateModel)]

<img src="./images/xmind.png" width="96%" height="96%">

---

- [Perception](#perception)
  - [Existence](#existence) | [Count](#count) | [Position](#position) | [Color](#color) | [Poster](#poster) | [Celebrity](#celebrity) | [Scene](#scene) | [Landmark](#landmark) | [Artwork](#artwork) | [OCR](#ocr)
  
- [Cognition](#cognition)
  - [Commonsense Reasoning](#commonsense-reasoning) | [Numerical Calculation](#numerical-calculation) | [Text Translation](#text-translation) | [Code Reasoning](#code-reasoning)


---

## Perception

Sum of the scores of all perception subtasks, including existence, count, position, color, poster, celebrity, scene, landmark, artwork, and OCR. The full score of each subtask is 200, and that of all perception is 2000.

| Rank |                            Model                             |                           Version                            |    Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :---------: |
|  🏅️   | **[Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **[-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **1790.04** |
|  🥈   | **[ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B)** | **[Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)**  | **1735.88** |
|  🥉   | **[InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer)** | **[InternLM2-7B](https://github.com/InternLM/InternLM-XComposer)** | **1712.00** |
|  4   |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         |   1686.52   |
|  5   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   1681.25   |
|  6   |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      |   1673.75   |
|  7   |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     |   1672.35   |
|  8   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   1661.13   |
|  9   |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) |   1636.90   |
|  10  | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      |   1631.47   |
|  11  |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   1621.66   |
|  12  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) |   1618.70   |
|  13  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      |   1610.15   |
|  14  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      |   1595.34   |
|  15  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) |   1588.16   |
|  16  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      |   1575.61   |
|  17  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     |   1574.89   |
|  18  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    |   1567.99   |
|  19  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     |   1563.56   |
|  20  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) |   1560.15   |
|  21  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   1531.31   |
|  22  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   1528.44   |
|  23  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       |   1522.39   |
|  24  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   1497.79   |
|  25  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) |   1496.57   |
|  26  |       [Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)       |         [Phi-2](https://github.com/BAAI-DCAI/Bunny)          |   1488.80   |
|  27  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   1487.57   |
|  28  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   1452.01   |
|  29  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   1450.19   |
|  30  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   1443.19   |
|  31  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   1439.07   |
|  32  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   |   1431.34   |
|  33  | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    |   1409.43   |
|  34  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   1381.74   |
|  35  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   1373.24   |
|  36  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   1337.73   |
|  37  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   1332.05   |
|  38  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   1328.39   |
|  39  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   1299.97   |
|  40  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   1299.79   |
|  41  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   1293.84   |
|  42  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   1292.26   |
|  43  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   1281.02   |
|  44  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   1212.82   |
|  45  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   967.34    |
|  46  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   963.60    |
|  47  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   790.45    |
|  48  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   775.77    |
|  49  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   705.31    |
|  50  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   654.72    |
|  51  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   642.59    |
|  52  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |   581.66    |

### Existence

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |      **[Otter](https://arxiv.org/pdf/2305.03726.pdf)**       |  **[OTTER-Image-MPT7B](https://github.com/Luodian/Otter)**   | **195.00** |
|  🏅️   |       **[Lynx](https://arxiv.org/pdf/2307.02469.pdf)**       |    **[Vicuna-7B](https://github.com/bytedance/lynx-llm)**    | **195.00** |
|  🏅️   |        **[WeMM](https://github.com/scenarios/WeMM)**         |     **[InternLM-7B](https://github.com/scenarios/WeMM)**     | **195.00** |
|  🏅️   |        **[Muffin](https://github.com/thunlp/Muffin)**        |      **[Vicuna-13B](https://github.com/thunlp/Muffin)**      | **195.00** |
|  🏅️   | **[SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX)** | **[LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX)** | **195.00** |
|  🏅️   |     **[InfMLLM](https://github.com/infly-ai/INF-MLLM)**      |    **[Vicuna-13B](https://github.com/infly-ai/INF-MLLM)**    | **195.00** |
|  🏅️   | **[LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)**  |  **[Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)**   | **195.00** |
|  🏅️   |     **[RBDash](https://github.com/RBDash-Team/RBDash)**      |   **[Vicuna-13B](https://github.com/RBDash-Team/RBDash)**    | **195.00** |
|  🏅️   | **[InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer)** | **[InternLM2-7B](https://github.com/InternLM/InternLM-XComposer)** | **195.00** |
|  🏅️   |      **[CogVLM](https://arxiv.org/pdf/2311.03079.pdf)**      |       **[Vicuna-7B](https://github.com/THUDM/CogVLM)**       | **195.00** |
|  🏅️   | **[ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B)** | **[Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)**  | **195.00** |
|  🏅️   | **[MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR)** | **[MindSource-7B](https://github.com/luogen1996/LLaVA-HR)**  | **195.00** |
|  🏅️   | **[MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v)** | **[MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)** | **195.00** |
|  🥈   |       **[GIT2](https://arxiv.org/pdf/2205.14100.pdf)**       | **[VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text)** | **190.00** |
|  🥈   | **[InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer)** | **[InternLM-7B](https://github.com/InternLM/InternLM-XComposer)** | **190.00** |
|  🥈   | **[GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf)** | **[-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)**  | **190.00** |
|  🥈   |    **[ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)**    | **[Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V)** | **190.00** |
|  🥈   | **[DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)** |   **[Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)**   | **190.00** |
|  🥈   |   **[BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)**    |   **[Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)**    | **190.00** |
|  🥈   | **[TransCore-M](https://github.com/PCIResearch/TransCore-M)** | **[PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M)** | **190.00** |
|  🥈   | **[LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/)** |    **[Vicuna-34B](https://github.com/haotian-liu/LLaVA)**    | **190.00** |
|  🥈   | **[MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)** | **[MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)** | **190.00** |
|  🥈   | **[OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)** | **[Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v)** | **190.00** |
|  🥈   |    **[HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)**    |   **[Vicuna-13B](https://github.com/dcdmllm/hyperllava)**    | **190.00** |
|  🥉   |         **[PureMM](https://github.com/Q-MM/PureMM)**         |       **[Vicuna-13B](https://github.com/Q-MM/PureMM)**       | **188.33** |
|  4   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   185.00   |
|  4   |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   185.00   |
|  4   |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   185.00   |
|  4   |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   185.00   |
|  4   |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   185.00   |
|  4   |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       |   185.00   |
|  4   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   185.00   |
|  4   |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     |   185.00   |
|  4   |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   185.00   |
|  5   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   183.33   |
|  6   |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   180.00   |
|  6   |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   180.00   |
|  6   |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   |   180.00   |
|  6   |       [Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)       |         [Phi-2](https://github.com/BAAI-DCAI/Bunny)          |   180.00   |
|  7   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   175.00   |
|  7   | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) |   175.00   |
|  8   |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   170.00   |
|  9   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   165.00   |
|  10  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   160.00   |
|  11  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   158.33   |
|  12  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   128.33   |
|  13  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   120.00   |
|  14  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   85.00    |
|  15  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   70.00    |
|  15  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   70.00    |
|  16  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |   68.33    |
|  17  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   61.67    |

### Count

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |     **[CogAgent](https://arxiv.org/pdf/2312.08914.pdf)**     |       **[Vicuna-7B](https://github.com/THUDM/CogVLM)**       | **180.00** |
|  🥈   |     **[RBDash](https://github.com/RBDash-Team/RBDash)**      |   **[Vicuna-13B](https://github.com/RBDash-Team/RBDash)**    | **173.33** |
|  🥈   | **[InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)** |   **[LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)**   | **173.33** |
|  🥉   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   170.00   |
|  🥉   | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      |   170.00   |
|  🥉   | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    |   170.00   |
|  4   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   166.67   |
|  5   |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) |   165.00   |
|  5   |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     |   165.00   |
|  5   |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) |   165.00   |
|  5   |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   165.00   |
|  5   |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) |   165.00   |
|  6   |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   163.33   |
|  7   |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   160.00   |
|  7   | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    |   160.00   |
|  7   | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) |   160.00   |
|  7   |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     |   160.00   |
|  7   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) |   160.00   |
|  7   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    |   160.00   |
|  7   |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      |   160.00   |
|  8   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   158.33   |
|  8   |       [Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)       |         [Phi-2](https://github.com/BAAI-DCAI/Bunny)          |   158.33   |
|  10  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   155.00   |
|  10  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   155.00   |
|  10  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   |   155.00   |
|  11  | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   153.33   |
|  12  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   151.67   |
|  13  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   150.00   |
|  14  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      |   150.00   |
|  14  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       |   150.00   |
|  14  |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         |   150.00   |
|  15  |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      |   145.00   |
|  16  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   143.33   |
|  17  |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   140.00   |
|  18  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   138.33   |
|  19  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   135.00   |
|  20  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   133.33   |
|  20  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   133.33   |
|  21  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) |   131.67   |
|  22  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   130.00   |
|  23  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   118.33   |
|  24  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   111.67   |
|  25  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   96.67    |
|  26  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   88.33    |
|  26  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   88.33    |
|  27  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   85.00    |
|  28  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   60.00    |
|  29  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |   55.00    |
|  29  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   55.00    |
|  30  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   50.00    |
|  30  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   50.00    |
|  30  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   50.00    |

### Position

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **[-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **176.67** |
|  🥈   |     **[InfMLLM](https://github.com/infly-ai/INF-MLLM)**      |    **[Vicuna-13B](https://github.com/infly-ai/INF-MLLM)**    | **170.00** |
|  🥉   | **[InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer)** | **[InternLM2-7B](https://github.com/InternLM/InternLM-XComposer)** | **163.33** |
|  🥉   | **[InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)** |   **[LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)**   | **163.33** |
|  4   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   161.67   |
|  5   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    |   158.33   |
|  6   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   155.00   |
|  7   |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) |   153.33   |
|  7   | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) |   153.33   |
|  8   | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    |   146.67   |
|  9   |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      |   138.33   |
|  9   | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      |   138.33   |
|  10  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) |   136.67   |
|  11  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   135.00   |
|  12  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   133.33   |
|  13  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) |   131.67   |
|  14  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      |   130.00   |
|  15  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     |   128.33   |
|  15  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      |   128.33   |
|  15  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   128.33   |
|  15  |       [Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)       |         [Phi-2](https://github.com/BAAI-DCAI/Bunny)          |   128.33   |
|  16  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   126.67   |
|  16  |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   126.67   |
|  17  |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         |   123.33   |
|  18  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     |   121.67   |
|  19  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       |   118.33   |
|  19  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   |   118.33   |
|  20  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   103.33   |
|  21  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   96.67    |
|  22  | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    |   95.00    |
|  23  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   93.33    |
|  24  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   90.00    |
|  25  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) |   90.00    |
|  26  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   88.33    |
|  27  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   86.67    |
|  27  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   86.67    |
|  27  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   86.67    |
|  28  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   81.67    |
|  28  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   81.67    |
|  29  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   80.00    |
|  30  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   73.33    |
|  31  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   66.67    |
|  31  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   66.67    |
|  32  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   63.33    |
|  32  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   63.33    |
|  33  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   58.33    |
|  34  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   56.67    |
|  35  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   50.00    |
|  35  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   50.00    |
|  36  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   48.33    |
|  37  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   46.67    |
|  38  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |   43.33    |

### Color

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |     **[InfMLLM](https://github.com/infly-ai/INF-MLLM)**      |    **[Vicuna-13B](https://github.com/infly-ai/INF-MLLM)**    | **195.00** |
|  🏅️   | **[InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer)** | **[InternLM2-7B](https://github.com/InternLM/InternLM-XComposer)** | **195.00** |
|  🏅️   | **[LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/)** |    **[Vicuna-34B](https://github.com/haotian-liu/LLaVA)**    | **195.00** |
|  🏅️   | **[ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B)** | **[Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)**  | **195.00** |
|  🥈   |     **[RBDash](https://github.com/RBDash-Team/RBDash)**      |   **[Vicuna-13B](https://github.com/RBDash-Team/RBDash)**    | **190.00** |
|  🥈   | **[InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)** |   **[LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)**   | **190.00** |
|  🥈   |    **[MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)**     | **[Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)** | **190.00** |
|  🥉   |    **[ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)**    | **[Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V)** | **185.00** |
|  🥉   | **[TransCore-M](https://github.com/PCIResearch/TransCore-M)** | **[PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M)** | **185.00** |
|  🥉   |   **[Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)**    |     **[Qwen-7B](https://github.com/Yuliang-Liu/Monkey)**     | **185.00** |
|  4   |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   180.00   |
|  4   |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     |   180.00   |
|  4   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   180.00   |
|  4   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   180.00   |
|  4   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   180.00   |
|  4   |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) |   180.00   |
|  4   |       [Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)       |         [Phi-2](https://github.com/BAAI-DCAI/Bunny)          |   180.00   |
|  4   | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    |   180.00   |
|  4   |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      |   180.00   |
|  5   |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      |   175.00   |
|  6   |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   170.00   |
|  6   |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   170.00   |
|  6   |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   170.00   |
|  6   |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         |   170.00   |
|  7   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   168.33   |
|  8   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   165.00   |
|  8   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   165.00   |
|  8   |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   165.00   |
|  9   | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) |   163.33   |
|  10  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) |   160.00   |
|  10  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   160.00   |
|  10  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   160.00   |
|  11  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   158.33   |
|  11  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   158.33   |
|  12  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   156.67   |
|  13  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     |   155.00   |
|  14  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   153.33   |
|  15  | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    |   150.00   |
|  15  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   150.00   |
|  16  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   148.33   |
|  17  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   145.00   |
|  18  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   118.33   |
|  19  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   116.67   |
|  20  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   113.33   |
|  21  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |   75.00    |
|  21  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   75.00    |
|  22  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   73.33    |
|  22  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   73.33    |
|  23  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   68.33    |
|  24  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   55.00    |
|  24  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   55.00    |
|  25  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   50.00    |

### Poster

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf)** | **[-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)**  | **192.18** |
|  🥈   |         **[PureMM](https://github.com/Q-MM/PureMM)**         |       **[Vicuna-13B](https://github.com/Q-MM/PureMM)**       | **191.50** |
|  🥉   | **[Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **[-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **187.76** |
|  4   |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      |   183.33   |
|  5   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   181.63   |
|  6   |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       |   178.91   |
|  7   |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   178.57   |
|  8   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    |   174.15   |
|  9   |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) |   171.43   |
|  10  | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) |   171.09   |
|  11  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   170.07   |
|  12  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     |   169.73   |
|  13  | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      |   169.39   |
|  14  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) |   169.05   |
|  15  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   167.35   |
|  16  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      |   166.33   |
|  17  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      |   165.99   |
|  18  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   165.31   |
|  19  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) |   164.97   |
|  20  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      |   164.97   |
|  21  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) |   164.29   |
|  22  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     |   162.59   |
|  23  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   161.90   |
|  24  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     |   161.22   |
|  25  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   160.54   |
|  26  |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   160.54   |
|  27  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) |   160.20   |
|  28  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   160.20   |
|  29  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   158.50   |
|  30  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    |   155.10   |
|  31  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   155.10   |
|  32  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   147.96   |
|  33  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   147.28   |
|  34  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   146.94   |
|  35  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   146.26   |
|  36  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   141.84   |
|  37  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   139.04   |
|  38  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   138.78   |
|  39  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   137.76   |
|  40  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   136.05   |
|  41  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   124.83   |
|  42  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   123.81   |
|  43  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   112.59   |
|  44  |       [Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)       |         [Phi-2](https://github.com/BAAI-DCAI/Bunny)          |   108.50   |
|  45  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   |   99.32    |
|  46  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   84.01    |
|  47  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   79.59    |
|  48  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   76.53    |
|  49  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   65.99    |
|  50  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   64.97    |
|  51  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   57.82    |
|  52  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |   41.84    |

### Celebrity

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **[-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **184.12** |
|  🏅️   | **[Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **[-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **184.12** |
|  🥈   |         **[PureMM](https://github.com/Q-MM/PureMM)**         |       **[Vicuna-13B](https://github.com/Q-MM/PureMM)**       | **182.35** |
|  🥉   |        **[WeMM](https://github.com/scenarios/WeMM)**         |     **[InternLM-7B](https://github.com/scenarios/WeMM)**     | **179.12** |
|  4   | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) |   177.94   |
|  5   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    |   177.65   |
|  6   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   177.06   |
|  7   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   172.65   |
|  8   |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) |   172.06   |
|  9   |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      |   170.00   |
|  10  |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      |   164.41   |
|  10  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   164.41   |
|  11  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   164.12   |
|  12  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      |   162.06   |
|  13  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     |   161.47   |
|  14  | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      |   160.00   |
|  15  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     |   159.41   |
|  16  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   155.59   |
|  17  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     |   154.71   |
|  18  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) |   153.82   |
|  19  | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) |   153.82   |
|  20  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   152.94   |
|  21  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   150.29   |
|  22  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   147.94   |
|  22  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   |   147.94   |
|  23  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) |   147.35   |
|  24  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   145.88   |
|  25  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) |   145.29   |
|  26  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       |   142.65   |
|  27  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   141.76   |
|  28  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   140.88   |
|  28  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   140.88   |
|  29  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      |   136.76   |
|  29  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   136.76   |
|  30  |       [Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)       |         [Phi-2](https://github.com/BAAI-DCAI/Bunny)          |   130.88   |
|  31  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    |   126.47   |
|  32  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   120.59   |
|  33  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   118.24   |
|  34  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   115.29   |
|  35  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   112.65   |
|  36  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   105.59   |
|  37  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   101.18   |
|  38  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   100.29   |
|  39  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   81.76    |
|  40  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   76.47    |
|  41  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   73.82    |
|  42  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   57.06    |
|  43  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |   54.41    |
|  44  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   53.53    |
|  45  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   53.24    |
|  46  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   47.35    |
|  47  | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    |    0.00    |

### Scene

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |     **[InfMLLM](https://github.com/infly-ai/INF-MLLM)**      |    **[Vicuna-13B](https://github.com/infly-ai/INF-MLLM)**    | **176.75** |
|  🥈   |        **[WeMM](https://github.com/scenarios/WeMM)**         |     **[InternLM-7B](https://github.com/scenarios/WeMM)**     | **176.25** |
|  🥉   | **[Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **[-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **173.00** |
|  4   |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) |   168.00   |
|  5   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    |   167.75   |
|  6   |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     |   166.50   |
|  6   |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      |   166.50   |
|  7   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) |   164.75   |
|  8   |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   164.50   |
|  8   | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      |   164.50   |
|  9   |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     |   163.25   |
|  10  |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         |   162.75   |
|  11  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   162.00   |
|  12  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       |   161.75   |
|  12  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    |   161.75   |
|  13  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   161.25   |
|  14  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) |   161.00   |
|  15  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      |   160.25   |
|  16  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) |   160.00   |
|  17  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   159.75   |
|  18  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   159.25   |
|  19  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   158.75   |
|  20  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   158.50   |
|  20  |       [Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)       |         [Phi-2](https://github.com/BAAI-DCAI/Bunny)          |   158.50   |
|  21  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   157.75   |
|  22  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   156.25   |
|  22  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      |   156.25   |
|  23  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   156.00   |
|  24  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     |   155.75   |
|  25  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   |   154.50   |
|  26  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   154.25   |
|  26  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   154.25   |
|  27  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   153.75   |
|  28  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   153.25   |
|  29  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   153.00   |
|  30  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   152.25   |
|  30  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   151.50   |
|  31  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   151.25   |
|  32  | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    |   151.00   |
|  32  | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   151.00   |
|  33  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   147.98   |
|  34  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   146.25   |
|  34  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) |   146.25   |
|  35  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   145.25   |
|  36  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) |   144.75   |
|  37  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   141.75   |
|  38  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   136.75   |
|  39  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   135.50   |
|  40  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   118.00   |
|  41  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   113.25   |
|  42  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |   71.75    |
|  43  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   68.00    |

### Landmark

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **[-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **191.00** |
|  🥈   | **[Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **[-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **187.50** |
|  🥉   | **[ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B)** | **[Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)**  | **185.75** |
|  4   |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       |   176.50   |
|  4   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) |   176.00   |
|  5   |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) |   175.25   |
|  6   | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   175.00   |
|  7   |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      |   174.25   |
|  8   |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) |   174.00   |
|  8   |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      |   174.00   |
|  9   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   172.25   |
|  9   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   172.25   |
|  9   |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         |   172.25   |
|  10  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   172.00   |
|  10  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      |   172.00   |
|  11  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   170.50   |
|  12  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) |   168.09   |
|  13  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     |   168.00   |
|  14  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   167.84   |
|  15  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   167.75   |
|  16  |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      |   166.75   |
|  17  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   165.25   |
|  18  | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      |   165.25   |
|  19  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   164.00   |
|  20  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   162.00   |
|  21  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     |   161.50   |
|  22  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   160.53   |
|  23  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     |   160.00   |
|  24  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   159.25   |
|  25  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) |   159.25   |
|  26  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) |   158.75   |
|  27  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   158.00   |
|  28  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   157.25   |
|  29  |       [Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)       |         [Phi-2](https://github.com/BAAI-DCAI/Bunny)          |   155.00   |
|  30  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    |   150.75   |
|  31  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   |   148.25   |
|  32  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   146.25   |
|  33  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   145.73   |
|  34  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   140.50   |
|  35  | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    |   138.25   |
|  36  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   138.00   |
|  37  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   137.25   |
|  38  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   136.13   |
|  39  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   93.50    |
|  40  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   89.50    |
|  41  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   83.75    |
|  42  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   79.75    |
|  43  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   69.75    |
|  43  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   69.75    |
|  44  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   64.75    |
|  45  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   62.00    |
|  46  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |   54.00    |

### Artwork

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer)** | **[InternLM2-7B](https://github.com/InternLM/InternLM-XComposer)** | **185.50** |
|  🥈   |         **[PureMM](https://github.com/Q-MM/PureMM)**         |       **[Vicuna-13B](https://github.com/Q-MM/PureMM)**       | **183.50** |
|  🥉   |     **[InfMLLM](https://github.com/infly-ai/INF-MLLM)**      |    **[Vicuna-13B](https://github.com/infly-ai/INF-MLLM)**    | **167.50** |
|  4   | [Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   166.00   |
|  5   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    |   159.75   |
|  6   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   156.00   |
|  7   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   156.00   |
|  8   |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) |   150.25   |
|  9   | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    |   148.00   |
|  10  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   146.25   |
|  11  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   145.25   |
|  12  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       |   144.25   |
|  13  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     |   143.50   |
|  14  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      |   140.50   |
|  15  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      |   139.50   |
|  16  | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      |   139.00   |
|  17  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   136.50   |
|  18  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) |   135.75   |
|  19  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   135.50   |
|  20  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   134.75   |
|  21  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   134.25   |
|  22  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   134.25   |
|  23  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) |   134.00   |
|  24  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   133.25   |
|  25  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) |   130.75   |
|  26  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   130.75   |
|  27  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     |   130.25   |
|  28  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   129.00   |
|  29  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) |   128.00   |
|  30  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   126.25   |
|  31  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   125.50   |
|  32  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   123.75   |
|  33  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    |   119.75   |
|  34  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   119.50   |
|  35  |       [Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)       |         [Phi-2](https://github.com/BAAI-DCAI/Bunny)          |   119.25   |
|  36  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      |   119.25   |
|  37  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   117.75   |
|  38  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   116.50   |
|  39  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   116.25   |
|  40  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     |   113.75   |
|  41  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   113.50   |
|  42  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   |   105.50   |
|  43  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   101.25   |
|  44  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   96.25    |
|  45  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   88.75    |
|  46  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   87.25    |
|  47  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   77.25    |
|  48  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   75.25    |
|  49  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   70.75    |
|  50  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |   60.50    |
|  51  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   59.50    |
|  52  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   51.25    |

### OCR

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf)** | **[-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)**  | **185.00** |
|  🏅️   | **[Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf)** | **[-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf)** | **185.00** |
|  🏅️   | **[Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **[-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **185.00** |
|  🥈   |   **[BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)**    |   **[Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)**    | **177.50** |
|  🥈   | **[InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)** |   **[LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)**   | **177.50** |
|  🥉   |     **[Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)**     |       **[Phi-2](https://github.com/BAAI-DCAI/Bunny)**        | **170.00** |
|  4   |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     |   162.50   |
|  4   |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         |   162.50   |
|  4   | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    |   162.50   |
|  4   | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    |   162.50   |
|  5   |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) |   155.00   |
|  5   |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   155.00   |
|  5   |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) |   155.00   |
|  6   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   147.50   |
|  6   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   147.50   |
|  6   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) |   147.50   |
|  6   |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   147.50   |
|  7   |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   140.00   |
|  7   | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      |   140.00   |
|  8   |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     |   132.50   |
|  8   |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) |   132.50   |
|  8   |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   |   132.50   |
|  8   |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      |   132.50   |
|  9   |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   125.00   |
|  9   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   125.00   |
|  10  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   110.00   |
|  10  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   110.00   |
|  10  |       [InfMLLM](https://github.com/infly-ai/INF-MLLM)        |      [Vicuna-13B](https://github.com/infly-ai/INF-MLLM)      |   110.00   |
|  11  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   110.00   |
|  12  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   107.50   |
|  13  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   102.50   |
|  14  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   102.50   |
|  14  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      |   102.50   |
|  14  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   102.50   |
|  15  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   100.00   |
|  15  |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   100.00   |
|  16  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   87.50    |
|  16  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) |   87.50    |
|  17  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   82.50    |
|  18  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   80.00    |
|  18  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       |   80.00    |
|  18  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   80.00    |
|  19  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   77.50    |
|  19  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   77.50    |
|  20  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   72.50    |
|  20  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   72.50    |
|  21  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   65.00    |
|  21  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   65.00    |
|  22  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |   57.50    |
|  22  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   57.50    |
|  23  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   50.00    |
|  24  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   42.50    |

---

## Cognition

Sum of the scores of all cognition subtasks, including commonsense reasoning, numerical calculation, text translation, and code reasoning. The full score of each subtask is 200, and that of all cognition is 800.

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **[-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **643.57** |
|  🥈   | **[InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer)** | **[InternLM2-7B](https://github.com/InternLM/InternLM-XComposer)** | **530.71** |
|  🥉   | **[GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf)** | **[-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)**  | **517.14** |
|  4   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   502.14   |
|  5   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   445.00   |
|  6   | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) |   436.79   |
|  7   |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   428.93   |
|  8   | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   406.07   |
|  9   |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       |   401.43   |
|  10  | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      |   397.14   |
|  11  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   391.07   |
|  12  | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    |   387.86   |
|  13  |       [InfMLLM](https://github.com/mightyzau/InfMLLM)        |      [Vicuna-13B](https://github.com/mightyzau/InfMLLM)      |   368.93   |
|  14  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     |   361.07   |
|  15  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   360.71   |
|  16  |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         |   360.36   |
|  17  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   356.43   |
|  18  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     |   341.07   |
|  19  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      |   332.14   |
|  20  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   331.43   |
|  21  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      |   330.00   |
|  22  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   328.21   |
|  23  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) |   322.14   |
|  24  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   321.07   |
|  25  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   315.36   |
|  26  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) |   314.64   |
|  27  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   314.29   |
|  28  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   313.21   |
|  29  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   313.21   |
|  30  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) |   310.00   |
|  31  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   306.43   |
|  32  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      |   304.29   |
|  33  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) |   303.21   |
|  34  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    |   301.43   |
|  35  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   295.36   |
|  36  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   291.79   |
|  37  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   290.00   |
|  38  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   290.00   |
|  39  |       [Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)       |         [Phi-2](https://github.com/BAAI-DCAI/Bunny)          |   289.29   |
|  40  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     |   286.79   |
|  41  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   276.07   |
|  42  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   274.64   |
|  43  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   |   262.14   |
|  44  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   261.79   |
|  45  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   249.64   |
|  46  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   249.29   |
|  47  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   228.57   |
|  48  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   226.79   |
|  49  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   215.71   |
|  50  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   213.57   |
|  51  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   181.79   |
|  52  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |   144.29   |

### Commonsense Reasoning

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   |     **[InfMLLM](https://github.com/mightyzau/InfMLLM)**      |    **[Vicuna-13B](https://github.com/mightyzau/InfMLLM)**    | **156.43** |
|  🥈   | **[LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/)** |    **[Vicuna-34B](https://github.com/haotian-liu/LLaVA)**    | **152.14** |
|  🥉   | **[Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **[-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **148.57** |
|  4   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) |   145.71   |
|  5   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   142.14   |
|  5   | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    |   142.14   |
|  6   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   140.00   |
|  6   |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      |   140.00   |
|  7   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   138.57   |
|  8   |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         |   137.86   |
|  9   |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   136.43   |
|  9   |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   136.43   |
|  9   | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    |   136.43   |
|  10  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     |   134.29   |
|  10  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      |   134.29   |
|  11  | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    |   132.86   |
|  12  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) |   132.14   |
|  13  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       |   131.43   |
|  14  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   130.71   |
|  15  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) |   130.00   |
|  16  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   129.29   |
|  16  | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) |   129.29   |
|  17  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   128.57   |
|  18  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   127.86   |
|  19  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      |   127.14   |
|  19  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) |   127.14   |
|  20  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) |   125.71   |
|  20  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   125.71   |
|  21  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     |   123.57   |
|  21  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     |   123.57   |
|  22  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   122.86   |
|  23  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   119.29   |
|  24  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   |   117.14   |
|  24  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   117.14   |
|  25  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   115.71   |
|  26  |       [Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)       |         [Phi-2](https://github.com/BAAI-DCAI/Bunny)          |   114.29   |
|  27  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   110.71   |
|  28  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   110.00   |
|  28  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   110.00   |
|  29  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   106.43   |
|  29  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   106.43   |
|  30  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   100.71   |
|  31  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   99.29    |
|  32  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   98.57    |
|  33  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   87.14    |
|  34  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   78.57    |
|  35  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   73.57    |
|  36  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   64.29    |
|  37  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |   59.29    |
|  38  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   49.29    |
|  39  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   48.57    |
|  40  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   39.29    |

### Numerical Calculation

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **[-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **155.00** |
|  🥈   | **[InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer)** | **[InternLM2-7B](https://github.com/InternLM/InternLM-XComposer)** | **137.50** |
|  🥉   | **[GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf)** | **[-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)**  | **130.00** |
|  4   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   85.00    |
|  5   |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   82.50    |
|  6   |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   77.50    |
|  6   | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) |   77.50    |
|  7   |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   72.50    |
|  7   | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      |   72.50    |
|  8   |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   70.00    |
|  8   |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     |   70.00    |
|  9   |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      |   67.50    |
|  10  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   65.00    |
|  11  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   62.50    |
|  12  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   60.00    |
|  12  |       [InfMLLM](https://github.com/mightyzau/InfMLLM)        |      [Vicuna-13B](https://github.com/mightyzau/InfMLLM)      |   60.00    |
|  12  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   60.00    |
|  13  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   57.50    |
|  13  |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   57.50    |
|  13  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   57.50    |
|  14  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   55.00    |
|  14  | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   55.00    |
|  14  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) |   55.00    |
|  14  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) |   55.00    |
|  14  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) |   55.00    |
|  15  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   50.00    |
|  15  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   50.00    |
|  15  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   50.00    |
|  15  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   |   50.00    |
|  16  |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   47.50    |
|  16  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     |   47.50    |
|  16  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      |   47.50    |
|  16  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   47.50    |
|  16  |       [Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)       |         [Phi-2](https://github.com/BAAI-DCAI/Bunny)          |   47.50    |
|  17  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |   45.00    |
|  17  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   45.00    |
|  18  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   45.00    |
|  18  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) |   45.00    |
|  18  |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         |   45.00    |
|  18  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   45.00    |
|  18  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    |   45.00    |
|  19  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   42.50    |
|  19  |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       |   42.50    |
|  20  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   40.00    |
|  20  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   40.00    |
|  20  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   40.00    |
|  20  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     |   40.00    |
|  20  | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    |   40.00    |
|  21  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      |   37.50    |
|  22  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   35.00    |
|  23  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   32.50    |
|  24  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   17.50    |

### Text Translation

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **[-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **185.00** |
|  🥈   | **[Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **[-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **170.00** |
|  🥈   | **[MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v)** | **[MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)** | **170.00** |
|  🥉   | **[ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B)** | **[Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)**  | **162.50** |
|  4   |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   147.50   |
|  4   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) |   147.50   |
|  5   | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) |   145.00   |
|  6   |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       |   137.50   |
|  7   |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   132.50   |
|  8   |          [WeMM](https://github.com/scenarios/WeMM)           |       [InternLM-7B](https://github.com/scenarios/WeMM)       |   130.00   |
|  9   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   112.50   |
|  9   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   112.50   |
|  10  |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     |   110.00   |
|  11  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   102.50   |
|  11  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      |   102.50   |
|  11  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     |   102.50   |
|  12  |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         |   92.50    |
|  12  |       [Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)       |         [Phi-2](https://github.com/BAAI-DCAI/Bunny)          |   92.50    |
|  13  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   87.50    |
|  13  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      |   87.50    |
|  14  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   85.00    |
|  15  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   82.50    |
|  16  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   80.00    |
|  16  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) |   80.00    |
|  16  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    |   80.00    |
|  17  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   77.50    |
|  17  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   77.50    |
|  17  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   77.50    |
|  17  |       [InfMLLM](https://github.com/mightyzau/InfMLLM)        |      [Vicuna-13B](https://github.com/mightyzau/InfMLLM)      |   77.50    |
|  17  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) |   77.50    |
|  18  | [GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf) |   [-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)    |   75.00    |
|  18  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) |   75.00    |
|  18  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   75.00    |
|  19  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   72.50    |
|  19  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      |   72.50    |
|  19  | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      |   72.50    |
|  20  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     |   70.00    |
|  21  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   67.50    |
|  22  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   65.00    |
|  22  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   65.00    |
|  23  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   62.50    |
|  24  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   60.00    |
|  25  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   57.50    |
|  25  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   57.50    |
|  25  |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   57.50    |
|  25  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   |   57.50    |
|  26  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) |   55.00    |
|  27  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   50.00    |
|  27  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   50.00    |
|  28  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   47.50    |
|  29  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   42.50    |
|  30  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |    0.00    |

### Code Reasoning

| Rank |                            Model                             |                           Version                            |   Score    |
| :--: | :----------------------------------------------------------: | :----------------------------------------------------------: | :--------: |
|  🏅️   | **[GPT-4V](https://cdn.openai.com/papers/GPTV_System_Card.pdf)** | **[-](https://cdn.openai.com/papers/GPTV_System_Card.pdf)**  | **170.00** |
|  🥈   | **[Qwen-VL-Max](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **[-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start)** | **170.00** |
|  🥉   |        **[WeMM](https://github.com/scenarios/WeMM)**         |     **[InternLM-7B](https://github.com/scenarios/WeMM)**     | **117.50** |
|  4   | [InternLM-XComposer2-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM2-7B](https://github.com/InternLM/InternLM-XComposer) |   100.00   |
|  4   | [LLaVA-1.6](https://llava-vl.github.io/blog/2024-01-30-llava-1-6/) |      [Vicuna-34B](https://github.com/haotian-liu/LLaVA)      |   100.00   |
|  5   |   [LLaMA-Adapter V2](https://arxiv.org/pdf/2304.15010.pdf)   | [LLaMA-Adapter-v2.1-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/llama_adapter_v2_multimodal7b) |   90.00    |
|  5   |     [Monkey-Chat](https://arxiv.org/pdf/2311.06607.pdf)      |       [Qwen-7B](https://github.com/Yuliang-Liu/Monkey)       |   90.00    |
|  5   | [Qwen-VL-Plus](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) | [-](https://help.aliyun.com/zh/dashscope/developer-reference/vl-plus-quick-start) |   90.00    |
|  6   |       [Cheetor](https://arxiv.org/pdf/2308.04152.pdf)        |       [Vicuna-7B](https://github.com/DCDmllm/Cheetah)        |   87.50    |
|  7   | [InternLM-XComposer-VL](https://github.com/InternLM/InternLM-XComposer) | [InternLM-7B](https://github.com/InternLM/InternLM-XComposer) |   85.00    |
|  7   | [Gemini Pro](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) | [-](https://storage.googleapis.com/deepmind-media/gemini/gemini_1_report.pdf) |   85.00    |
|  7   |           [PureMM](https://github.com/Q-MM/PureMM)           |         [Vicuna-13B](https://github.com/Q-MM/PureMM)         |   85.00    |
|  8   |  [DataOptim-LLaVA](https://github.com/BAAI-DCAI/DataOptim)   |     [Vicuna-13B](https://github.com/BAAI-DCAI/DataOptim)     |   80.00    |
|  9   |        [MMICL](https://arxiv.org/pdf/2309.07915.pdf)         |        [FlanT5xxl](https://github.com/HaozheZhao/MIC)        |   77.50    |
|  10  |        [BLIP-2](https://arxiv.org/pdf/2301.12597.pdf)        | [Flant5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/blip2) |   75.00    |
|  11  |       [InfMLLM](https://github.com/mightyzau/InfMLLM)        |      [Vicuna-13B](https://github.com/mightyzau/InfMLLM)      |   75.00    |
|  11  | [MiniCPM-V-2](https://github.com/OpenBMB/MiniCPM/#minicpm-v) | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   75.00    |
|  12  |   [LRV-Instruction](https://arxiv.org/pdf/2306.14565.pdf)    |    [LRV-7B](https://github.com/FuxiaoLiu/LRV-Instruction)    |   72.50    |
|  13  |  [TransCore-M](https://github.com/PCIResearch/TransCore-M)   | [PCITransGPT-13B](https://github.com/PCIResearch/TransCore-M) |   72.50    |
|  14  |        [Otter](https://arxiv.org/pdf/2305.03726.pdf)         |    [OTTER-Image-MPT7B](https://github.com/Luodian/Otter)     |   70.00    |
|  15  |   [MiniCPM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [MiniCPM-2B](https://github.com/OpenBMB/MiniCPM/#minicpm-v)  |   65.00    |
|  16  |          [Muffin](https://github.com/thunlp/Muffin)          |        [Vicuna-13B](https://github.com/thunlp/Muffin)        |   62.50    |
|  16  |   [OmniLMM](https://github.com/OpenBMB/MiniCPM/#minicpm-v)   | [Zephyr-7B-beta](https://github.com/OpenBMB/MiniCPM/#minicpm-v) |   62.50    |
|  17  | [ImageBind_LLM](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main) | [LLaMA-7B](https://github.com/OpenGVLab/LLaMA-Adapter/tree/main/imagebind_LLM) |   60.00    |
|  17  |        [BLIVA](https://arxiv.org/pdf/2308.09936.pdf)         |       [FlanT5xxl](https://github.com/mlpc-ucsd/BLIVA)        |   60.00    |
|  17  |      [mPLUG-Owl2](https://arxiv.org/pdf/2311.04257.pdf)      | [LLaMA2-7B](https://github.com/X-PLUG/mPLUG-Owl/tree/main/mPLUG-Owl2) |   60.00    |
|  18  |      [mPLUG-Owl](https://arxiv.org/pdf/2304.14178.pdf)       | [LLaMA-7B](https://huggingface.co/MAGAer13/mplug-owl-llama-7b) |   57.50    |
|  18  |     [InstructBLIP](https://arxiv.org/pdf/2305.06500.pdf)     | [FlanT5xxl](https://github.com/salesforce/LAVIS/tree/main/projects/instructblip) |   57.50    |
|  18  |       [VPGTrans](https://arxiv.org/pdf/2305.01278.pdf)       |      [Vicuna-7B](https://github.com/VPGTrans/VPGTrans)       |   57.50    |
|  19  |    [Multimodal-GPT](https://arxiv.org/pdf/2305.04790.pdf)    | [Multimodal-GPT-9B](https://github.com/open-mmlab/Multimodal-GPT) |   55.00    |
|  19  |     [BELLE-VL](https://huggingface.co/BELLE-2/BELLE-VL)      |     [Qwen-14B](https://huggingface.co/BELLE-2/BELLE-VL)      |   55.00    |
|  20  |      [ShareGPT4V](https://arxiv.org/pdf/2311.12793.pdf)      | [Vicuna-13B](https://github.com/InternLM/InternLM-XComposer/tree/main/projects/ShareGPT4V) |   52.50    |
|  20  |        [CogVLM](https://arxiv.org/pdf/2311.03079.pdf)        |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   52.50    |
|  21  | [ChatTruth-7B](https://huggingface.co/mingdali/ChatTruth-7B) |   [Qwen-7B](https://huggingface.co/mingdali/ChatTruth-7B)    |   52.50    |
|  22  |        [LaVIN](https://arxiv.org/pdf/2305.15023.pdf)         |       [LAVIN-13B](https://github.com/luogen1996/LaVIN)       |   50.00    |
|  23  | [SPHINX](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) | [LLaMA2-13B](https://github.com/Alpha-VLLM/LLaMA2-Accessory/tree/main/SPHINX) |   50.00    |
|  23  |       [RBDash](https://github.com/RBDash-Team/RBDash)        |     [Vicuna-13B](https://github.com/RBDash-Team/RBDash)      |   50.00    |
|  23  |       [CogAgent](https://arxiv.org/pdf/2312.08914.pdf)       |         [Vicuna-7B](https://github.com/THUDM/CogVLM)         |   50.00    |
|  24  |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |    [VisualGLM-6B](https://github.com/THUDM/VisualGLM-6B)     |   47.50    |
|  25  |       [PandaGPT](https://arxiv.org/pdf/2305.16355.pdf)       |       [Vicuna-7B](https://github.com/yxuansu/PandaGPT)       |   47.50    |
|  25  |        [LLaVA](https://arxiv.org/pdf/2304.08485.pdf)         |      [Vicuna-13B](https://github.com/haotian-liu/LLaVA)      |   47.50    |
|  25  |       [Honeybee](https://arxiv.org/pdf/2312.06742.pdf)       |     [Vicuna-13B](https://github.com/kakaobrain/honeybee)     |   47.50    |
|  26  |         [Lynx](https://arxiv.org/pdf/2307.02469.pdf)         |      [Vicuna-7B](https://github.com/bytedance/lynx-llm)      |   45.00    |
|  26  |         [GIT2](https://arxiv.org/pdf/2205.14100.pdf)         | [VQAv2-finetuned](https://github.com/microsoft/GenerativeImage2Text) |   45.00    |
|  26  |  [InternVL-Chat-V1.1](https://arxiv.org/pdf/2312.14238.pdf)  |     [LLaMA2-13B](https://github.com/OpenGVLab/InternVL/)     |   45.00    |
|  26  |      [HyperLLaVA](https://arxiv.org/pdf/2403.13447.pdf)      |     [Vicuna-13B](https://github.com/dcdmllm/hyperllava)      |   45.00    |
|  27  |      [Qwen-VL-Chat](https://github.com/QwenLM/Qwen-VL/)      |         [Qwen-7B](https://github.com/QwenLM/Qwen-VL)         |   42.50    |
|  27  |   [LVIS-INSTRUCT4V](https://arxiv.org/pdf/2311.07574.pdf)    |    [Vicuna-13B](https://github.com/X2FD/LVIS-INSTRUCT4V)     |   42.50    |
|  28  |      [MiniGPT-4](https://arxiv.org/pdf/2304.10592.pdf)       |    [Vicuna-13B](https://github.com/Vision-CAIR/MiniGPT-4)    |   40.00    |
|  28  | [MindSource-VL-Chat](https://github.com/luogen1996/LLaVA-HR) |   [MindSource-7B](https://github.com/luogen1996/LLaVA-HR)    |   40.00    |
|  29  |      [MoE-LLaVA](https://arxiv.org/pdf/2401.15947.pdf)       |   [Phi-2.7B×4](https://github.com/PKU-YuanGroup/MoE-LLaVA)   |   37.50    |
|  30  |       [Bunny-3B](https://arxiv.org/pdf/2402.11530.pdf)       |         [Phi-2](https://github.com/BAAI-DCAI/Bunny)          |   35.00    |
